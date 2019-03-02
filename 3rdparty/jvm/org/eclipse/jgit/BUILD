load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "org_eclipse_jgit",
    exports = [
        "//external:jar/org/eclipse/jgit/org_eclipse_jgit"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/googlecode/javaewah:JavaEWAH",
        "//3rdparty/jvm/com/jcraft:jsch",
        "//3rdparty/jvm/com/jcraft:jzlib",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



scala_import(
    name = "org_eclipse_jgit_archive",
    jars = [
        "//external:jar/org/eclipse/jgit/org_eclipse_jgit_archive"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/apache/commons:commons_compress",
        "//3rdparty/jvm/org/osgi:org_osgi_core",
        ":org_eclipse_jgit"
    ],
    visibility = [
        "//visibility:public"
    ]
)


