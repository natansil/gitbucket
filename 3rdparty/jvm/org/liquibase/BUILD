load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "liquibase_core",
    jars = [
        "//external:jar/org/liquibase/liquibase_core"
    ],
    runtime_deps = [
        "//3rdparty/jvm/ch/qos/logback:logback_classic",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


