package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

py_library(
    name = "one_billion_wds",
    srcs = ["one_billion_wds.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//lingvo:model_registry",
        "//lingvo/core:base_model_params",
        "//lingvo/core:layers",
        "//lingvo/core:optimizer",
        "//lingvo/core:py_utils",
        "//lingvo/core:schedule",
        "//lingvo/core:tokenizers",
        "//lingvo/tasks/lm:input_generator",
        "//lingvo/tasks/lm:layers",
        "//lingvo/tasks/lm:model",
    ],
)

py_library(
    name = "params",
    srcs = ["__init__.py"],
    srcs_version = "PY2AND3",
    deps = [
        ":one_billion_wds",
    ],
)
