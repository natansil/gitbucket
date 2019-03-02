load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "jetty_http",
    exports = [
        "//external:jar/org/eclipse/jetty/jetty_http"
    ],
    runtime_deps = [
        ":jetty_io",
        ":jetty_util"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jetty_io",
    exports = [
        "//external:jar/org/eclipse/jetty/jetty_io"
    ],
    runtime_deps = [
        ":jetty_util"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "jetty_security",
    jars = [
        "//external:jar/org/eclipse/jetty/jetty_security"
    ],
    runtime_deps = [
        ":jetty_server"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "jetty_server",
    jars = [
        "//external:jar/org/eclipse/jetty/jetty_server"
    ],
    runtime_deps = [
        "//3rdparty/jvm/javax/servlet:javax_servlet_api",
        ":jetty_http",
        ":jetty_io"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "jetty_servlet",
    jars = [
        "//external:jar/org/eclipse/jetty/jetty_servlet"
    ],
    runtime_deps = [
        ":jetty_security"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jetty_util",
    exports = [
        "//external:jar/org/eclipse/jetty/jetty_util"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "jetty_webapp",
    jars = [
        "//external:jar/org/eclipse/jetty/jetty_webapp"
    ],
    runtime_deps = [
        ":jetty_servlet",
        ":jetty_xml"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "jetty_xml",
    exports = [
        "//external:jar/org/eclipse/jetty/jetty_xml"
    ],
    runtime_deps = [
        ":jetty_util"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


