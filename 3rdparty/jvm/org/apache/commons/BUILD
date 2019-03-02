load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "commons_compress",
    exports = [
        "//external:jar/org/apache/commons/commons_compress"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
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


