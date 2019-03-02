load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "commons_compress",
    jars = [
        "//external:jar/org/apache/commons/commons_compress"
    ],
    visibility = [
        "//visibility:public"
    ]
)



scala_import(
    name = "commons_email",
    jars = [
        "//external:jar/org/apache/commons/commons_email"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/sun/mail:javax_mail"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "commons_lang3",
    exports = [
        "//external:jar/org/apache/commons/commons_lang3"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


