load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "httpclient",
    jars = [
        "//external:jar/org/apache/httpcomponents/httpclient"
    ],
    runtime_deps = [
        "//3rdparty/jvm/commons_codec:commons_codec",
        "//3rdparty/jvm/commons_logging:commons_logging",
        ":httpcore"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "httpcore",
    exports = [
        "//external:jar/org/apache/httpcomponents/httpcore"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "httpmime",
    jars = [
        "//external:jar/org/apache/httpcomponents/httpmime"
    ],
    runtime_deps = [
        ":httpclient"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


