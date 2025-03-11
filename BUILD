load("@score_cr_checker//:cr_checker.bzl", "copyright_checker")

copyright_checker(
    name = "copyright_check",
    srcs = ["src"],
    template = "@score_cr_checker//resources:templates",
    config = "@score_cr_checker//resources:config",
    visibility = ["//visibility:public"],
)
