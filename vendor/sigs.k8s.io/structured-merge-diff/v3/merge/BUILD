load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conflict.go",
        "update.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/sigs.k8s.io/structured-merge-diff/v3/merge",
    importpath = "sigs.k8s.io/structured-merge-diff/v3/merge",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/sigs.k8s.io/structured-merge-diff/v3/fieldpath:go_default_library",
        "//vendor/sigs.k8s.io/structured-merge-diff/v3/typed:go_default_library",
    ],
)
