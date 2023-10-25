load("@bazel_tools//tools/build_defs/cc:cc_rules.bzl", "cc_binary", "cc_library", "cc_test")

# Define an executable
cc_binary(
    name = "terminal-tones",
    srcs = ["terminal-tones.cc"],
    deps = [
        "//external:portaudio",  # An external dependency defined in WORKSPACE
        "//external:googletest",  # An external dependency defined in WORKSPACE
    ],
)

# Define a C++ library
# cc_library(
#     name = "my_library",
#     srcs = ["my_code.cc", "helper.cc"],
#     hdrs = ["my_code.h", "helper.h"],
# )

# Define a test
# cc_test(
#     name = "my_test",
#     srcs = ["my_test.cc"],
#     deps = [
#         ":my_library",
#         "//external:googletest",
#     ],
# )
