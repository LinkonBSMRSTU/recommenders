# Placeholder for internal Python library.
# Placeholder for internal Python test library.

package(
    default_visibility = [
        "//tensorflow_recommenders:__subpackages__",
    ],
)

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

py_library(
    name = "layers",
    srcs = ["__init__.py"],
    srcs_version = "PY3",
    deps = [
        ":corpus",
        ":loss",
        ":scoring",
    ],
)

py_library(
    name = "corpus",
    srcs = ["corpus.py"],
    srcs_version = "PY3",
    deps = [
        # py/numpy dep,
        # py/tensorflow dep,
    ],
)

py_library(
    name = "loss",
    srcs = ["loss.py"],
    srcs_version = "PY3",
    deps = [
        # py/numpy dep,
        # py/tensorflow dep,
    ],
)

py_library(
    name = "scoring",
    srcs = ["scoring.py"],
    srcs_version = "PY3",
    deps = [
        # py/tensorflow dep,
    ],
)

# Tests
py_test(
    name = "corpus_test",
    srcs = ["corpus_test.py"],
    python_version = "PY3",
    srcs_version = "PY3",
    deps = [
        ":corpus",
        # py/absl/testing:parameterized dep,
        # py/numpy dep,
        # py/tensorflow dep,
    ],
)

py_test(
    name = "loss_test",
    srcs = ["loss_test.py"],
    python_version = "PY3",
    srcs_version = "PY3",
    deps = [
        ":loss",
        # py/absl/testing:parameterized dep,
        # py/numpy dep,
        # py/tensorflow dep,
    ],
)