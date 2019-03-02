load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "quartz",
    exports = [
        "//external:jar/org/quartz_scheduler/quartz"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/mchange:c3p0",
        "//3rdparty/jvm/com/mchange:mchange_commons_java",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


