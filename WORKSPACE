workspace(name = "javamelody")

load("//:bazlets.bzl", "load_bazlets")

load_bazlets(
    commit = "70530b6a10375bbc65245f3c0582d90ac8acf05a",
    local_path = "/home/<user>/projets/bazlets",
)

#Snapshot Plugin API
load(
   "@com_googlesource_gerrit_bazlets//:gerrit_api_maven_local.bzl",
   "gerrit_api_maven_local",
)

# Load snapshot Plugin API
gerrit_api_maven_local()

# Release Plugin API
# load(
#     "@com_googlesource_gerrit_bazlets//:gerrit_api.bzl",
#     "gerrit_api",
# )

# Load release Plugin API
# gerrit_api()

load("//:external_plugin_deps.bzl", "external_plugin_deps")

external_plugin_deps()
