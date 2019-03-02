load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "mockito_core",
    jars = [
        "//external:jar/org/mockito/mockito_core"
    ],
    runtime_deps = [
        "//3rdparty/jvm/net/bytebuddy:byte_buddy",
        "//3rdparty/jvm/net/bytebuddy:byte_buddy_agent",
        "//3rdparty/jvm/org/objenesis:objenesis"
    ],
    visibility = [
        "//visibility:public"
    ]
)


