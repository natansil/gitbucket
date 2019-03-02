load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "lang_tag",
    exports = [
        "//external:jar/com/nimbusds/lang_tag"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "nimbus_jose_jwt",
    exports = [
        "//external:jar/com/nimbusds/nimbus_jose_jwt"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/github/stephenc/jcip:jcip_annotations",
        "//3rdparty/jvm/net/minidev:json_smart"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "oauth2_oidc_sdk",
    jars = [
        "//external:jar/com/nimbusds/oauth2_oidc_sdk"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/github/stephenc/jcip:jcip_annotations",
        "//3rdparty/jvm/com/sun/mail:javax_mail",
        "//3rdparty/jvm/net/minidev:json_smart",
        ":lang_tag",
        ":nimbus_jose_jwt"
    ],
    visibility = [
        "//visibility:public"
    ]
)


