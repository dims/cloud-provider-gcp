load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cloudprovider.go",
        "debugging.go",
        "generic.go",
        "kubecloudshared.go",
        "servicecontroller.go",
    ],
    importpath = "k8s.io/cloud-provider-gcp/cmd/controller-manager/app/options",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/spf13/pflag:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/sets:go_default_library",
        "//vendor/k8s.io/component-base/cli/flag:go_default_library",
        "//vendor/k8s.io/component-base/config:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/leaderelectionconfig:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/controller/apis/config:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/controller/service/config:go_default_library",
    ],
)
