load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "testcontainers_scala",
    jars = [
        "//external:jar/com/dimafeng/testcontainers_scala_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/testcontainers:testcontainers"
    ],
    visibility = [
        "//visibility:public"
    ]
)


