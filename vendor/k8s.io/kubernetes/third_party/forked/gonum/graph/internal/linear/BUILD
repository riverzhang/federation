load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["linear.go"],
    importpath = "k8s.io/kubernetes/third_party/forked/gonum/graph/internal/linear",
    visibility = ["//vendor/k8s.io/kubernetes/third_party/forked/gonum/graph:__subpackages__"],
    deps = ["//vendor/k8s.io/kubernetes/third_party/forked/gonum/graph:go_default_library"],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
