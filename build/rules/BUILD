package(default_visibility = ["//visibility:public"])

platform(
    name = "remote-amd64",
    constraint_values = [
        "@platforms//cpu:x86_64",
        "@platforms//os:linux",
    ],
    exec_properties = {
        "container-image": "docker://389791687681.dkr.ecr.eu-west-1.amazonaws.com/wekanode-builder:e86494dc98a286d9_x86_64",
        "OSFamily": "linux",
    },
)
