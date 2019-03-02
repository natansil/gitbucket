load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "akka_quartz_scheduler",
    jars = [
        "//external:jar/com/enragedginger/akka_quartz_scheduler_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/quartz_scheduler:quartz",
        "//3rdparty/jvm/org/scala_lang:scala_library"
    ],
    visibility = [
        "//visibility:public"
    ]
)


