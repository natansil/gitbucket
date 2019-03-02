load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_import(
    name = "database_commons",
    jars = [
        "//external:jar/org/testcontainers/database_commons"
    ],
    runtime_deps = [
        ":testcontainers"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "jdbc",
    jars = [
        "//external:jar/org/testcontainers/jdbc"
    ],
    runtime_deps = [
        ":database_commons"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "mysql",
    jars = [
        "//external:jar/org/testcontainers/mysql"
    ],
    runtime_deps = [
        ":jdbc"
    ],
    visibility = [
        "//visibility:public"
    ]
)



scala_import(
    name = "postgresql",
    jars = [
        "//external:jar/org/testcontainers/postgresql"
    ],
    runtime_deps = [
        ":jdbc"
    ],
    visibility = [
        "//visibility:public"
    ]
)



scala_import(
    name = "testcontainers",
    jars = [
        "//external:jar/org/testcontainers/testcontainers"
    ],
    runtime_deps = [
        "//3rdparty/jvm/javax/annotation:javax_annotation_api",
        "//3rdparty/jvm/javax/xml/bind:jaxb_api",
        "//3rdparty/jvm/junit:junit",
        "//3rdparty/jvm/net/java/dev/jna:jna_platform",
        "//3rdparty/jvm/org/apache/commons:commons_compress",
        "//3rdparty/jvm/org/jetbrains:annotations",
        "//3rdparty/jvm/org/rnorth/duct_tape:duct_tape",
        "//3rdparty/jvm/org/rnorth/visible_assertions:visible_assertions",
        "//3rdparty/jvm/org/rnorth:tcp_unix_socket_proxy",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


