load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "junixsocket_common",
    exports = [
        "//external:jar/com/kohlschutter/junixsocket/junixsocket_common"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "junixsocket_native_common",
    exports = [
        "//external:jar/com/kohlschutter/junixsocket/junixsocket_native_common"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scijava:native_lib_loader",
        ":junixsocket_common"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


