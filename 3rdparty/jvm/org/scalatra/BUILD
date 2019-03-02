load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "scalatra_common_2_12",
    exports = [
        "//external:jar/org/scalatra/scalatra_common_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scala_lang:scala_library"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "scalatra_scalatest",
    jars = [
        "//external:jar/org/scalatra/scalatra_scalatest_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/junit:junit",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scalatest:scalatest_2_12",
        ":scalatra_test"
    ],
    visibility = [
        "//visibility:public"
    ]
)



scala_import(
    name = "scalatra_test",
    jars = [
        "//external:jar/org/scalatra/scalatra_test_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/javax/servlet:javax_servlet_api",
        "//3rdparty/jvm/org/apache/commons:commons_lang3",
        "//3rdparty/jvm/org/apache/httpcomponents:httpclient",
        "//3rdparty/jvm/org/apache/httpcomponents:httpmime",
        "//3rdparty/jvm/org/eclipse/jetty:jetty_webapp",
        "//3rdparty/jvm/org/mockito:mockito_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        ":scalatra_common_2_12"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


