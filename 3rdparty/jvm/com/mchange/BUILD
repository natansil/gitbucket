load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "c3p0",
    exports = [
        "//external:jar/com/mchange/c3p0"
    ],
    runtime_deps = [
        ":mchange_commons_java"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "mchange_commons_java",
    exports = [
        "//external:jar/com/mchange/mchange_commons_java"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


