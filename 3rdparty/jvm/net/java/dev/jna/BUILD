load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "jna",
    exports = [
        "//external:jar/net/java/dev/jna/jna"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jna_platform",
    exports = [
        "//external:jar/net/java/dev/jna/jna_platform"
    ],
    runtime_deps = [
        ":jna"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


