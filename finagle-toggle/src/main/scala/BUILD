scala_library(
    sources = globs(
        "com/twitter/finagle/toggle/*.scala",
        "com/twitter/finagle/toggle/flag/*.scala",
    ),
    fatal_warnings = True,
    provides = scala_artifact(
        org = "com.twitter",
        name = "finagle-toggle",
        repo = artifactory,
    ),
    dependencies = [
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations",
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind",
        "3rdparty/jvm/com/fasterxml/jackson/module:jackson-module-scala",
        "finagle/finagle-toggle/src/main/scala/com/twitter/finagle/server",
        "util/util-app/src/main/java",
        "util/util-app/src/main/scala",
        "util/util-core/src/main/scala",
        "util/util-logging",
        "util/util-registry",
        "util/util-stats",
    ],
    exports = [
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations",
        "finagle/finagle-toggle/src/main/scala/com/twitter/finagle/server",
    ],
)
