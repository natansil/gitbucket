load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "accessors_smart",
    exports = [
        "//external:jar/net/minidev/accessors_smart"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/ow2/asm:asm"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "json_smart",
    exports = [
        "//external:jar/net/minidev/json_smart"
    ],
    runtime_deps = [
        ":accessors_smart"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


