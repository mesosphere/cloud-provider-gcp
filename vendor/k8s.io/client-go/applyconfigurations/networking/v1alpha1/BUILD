load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1alpha1",
    srcs = [
        "clustercidr.go",
        "clustercidrspec.go",
        "ipaddress.go",
        "ipaddressspec.go",
        "parentreference.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/networking/v1alpha1",
    importpath = "k8s.io/client-go/applyconfigurations/networking/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/networking/v1alpha1",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/client-go/applyconfigurations/core/v1:core",
        "//vendor/k8s.io/client-go/applyconfigurations/internal",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:meta",
    ],
)
