load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "cache2k_all",
    jars = [
        "//external:jar/org/cache2k/cache2k_all"
    ],
    runtime_deps = [
        ":cache2k_api",
        ":cache2k_core"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "cache2k_api",
    exports = [
        "//external:jar/org/cache2k/cache2k_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "cache2k_core",
    exports = [
        "//external:jar/org/cache2k/cache2k_core"
    ],
    runtime_deps = [
        ":cache2k_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


