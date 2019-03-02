load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "akka_actor",
    jars = [
        "//external:jar/com/typesafe/akka/akka_actor_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/typesafe:config",
        "//3rdparty/jvm/org/scala_lang/modules:scala_java8_compat_2_12",
        "//3rdparty/jvm/org/scala_lang:scala_library"
    ],
    visibility = [
        "//visibility:public"
    ]
)


