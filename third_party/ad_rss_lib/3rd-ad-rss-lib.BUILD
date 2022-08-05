load("@rules_cc//cc:defs.bzl", "cc_library", "cc_binary")

package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])

cc_library(
    name = "ad_rss",
    srcs = ["lib/libad_rss.so"],
    hdrs = glob(["include/**/*.hpp"]),
    copts = [
        "-fPIC",
        "-std=c++11",
        "-Werror",
        "-Wall",
        "-Wextra",
        "-pedantic",
        "-Wconversion",
        "-Wsign-conversion",
    ],
    strip_include_prefix = "include/ad_rss",
    includes = [
        "include",
    ],
    strip_include_prefix = "include/ad_rss",
)
