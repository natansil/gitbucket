load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "logback_classic",
    jars = [
        "//external:jar/ch/qos/logback/logback_classic"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/slf4j:slf4j_api",
        ":logback_core"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "logback_core",
    exports = [
        "//external:jar/ch/qos/logback/logback_core"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


