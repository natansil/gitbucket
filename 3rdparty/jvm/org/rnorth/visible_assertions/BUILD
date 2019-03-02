load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "visible_assertions",
    exports = [
        "//external:jar/org/rnorth/visible_assertions/visible_assertions"
    ],
    runtime_deps = [
        "//3rdparty/jvm/net/java/dev/jna:jna"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


