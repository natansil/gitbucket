load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "tcp_unix_socket_proxy",
    exports = [
        "//external:jar/org/rnorth/tcp_unix_socket_proxy"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/kohlschutter/junixsocket:junixsocket_common",
        "//3rdparty/jvm/com/kohlschutter/junixsocket:junixsocket_native_common",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


