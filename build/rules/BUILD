package(default_visibility = ["//visibility:public"])

platform(
    name = "remote-amd64",
    constraint_values = [
        "@platforms//cpu:x86_64",
        "@platforms//os:linux",
    ],
    exec_properties = {
        "OSFamily": "linux",
        "container-image": "docker://fra.ocir.io/fr3hx7l7h3p9/wekanode-builder:ba3fd4833464448a_x86_64",
    },
)
