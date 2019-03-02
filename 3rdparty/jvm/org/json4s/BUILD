load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "json4s_ast_2_12",
    exports = [
        "//external:jar/org/json4s/json4s_ast_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scala_lang:scala_library"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "json4s_core_2_12",
    exports = [
        "//external:jar/org/json4s/json4s_core_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/thoughtworks/paranamer:paranamer",
        "//3rdparty/jvm/org/scala_lang/modules:scala_xml_2_12",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        ":json4s_ast_2_12",
        ":json4s_scalap_2_12"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "json4s_jackson",
    jars = [
        "//external:jar/org/json4s/json4s_jackson_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/fasterxml/jackson/core:jackson_databind",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        ":json4s_core_2_12"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "json4s_scalap_2_12",
    exports = [
        "//external:jar/org/json4s/json4s_scalap_2_12"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scala_lang:scala_library"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


