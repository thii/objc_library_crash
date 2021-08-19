load("//rules:hmap.bzl", "headermap")

headermap(
    name = "hmap",
    hdrs = [],
)

objc_library(
    name = "lib",
    srcs = ["dummy.m"],
    deps = [":hmap"],
    copts = ["-I$(execpath :hmap)"],
)
