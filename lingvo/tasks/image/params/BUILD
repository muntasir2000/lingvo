package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

py_library(
    name = "mnist",
    srcs = ["mnist.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//lingvo:model_registry",
        "//lingvo/core:base_model_params",
        "//lingvo/tasks/image:classifier",
        "//lingvo/tasks/image:input_generator",
    ],
)

py_library(
    name = "params",
    srcs = ["__init__.py"],
    srcs_version = "PY2AND3",
    deps = [
        ":mnist",
    ],
)
