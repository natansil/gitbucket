load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "markedj",
    jars = [
        "//external:jar/io/github/gitbucket/markedj"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/jsoup:jsoup"
    ],
    visibility = [
        "//visibility:public"
    ]
)



scala_import(
    name = "solidbase",
    jars = [
        "//external:jar/io/github/gitbucket/solidbase"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/liquibase:liquibase_core"
    ],
    visibility = [
        "//visibility:public"
    ]
)


