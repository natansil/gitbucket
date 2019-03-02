load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "javax_mail",
    exports = [
        "//external:jar/com/sun/mail/javax_mail"
    ],
    runtime_deps = [
        "//3rdparty/jvm/javax/activation:activation"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


