package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "daemonset.go",
        "deployment.go",
        "deployment_expansion.go",
        "doc.go",
        "extensions_client.go",
        "generated_expansion.go",
        "ingress.go",
        "job.go",
        "podsecuritypolicy.go",
        "replicaset.go",
        "scale.go",
        "scale_expansion.go",
        "thirdpartyresource.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//pkg/api:go_default_library",
        "//pkg/api/meta:go_default_library",
        "//pkg/api/v1:go_default_library",
        "//pkg/apimachinery/registered:go_default_library",
        "//pkg/apis/extensions/v1beta1:go_default_library",
        "//pkg/client/restclient:go_default_library",
        "//pkg/runtime/schema:go_default_library",
        "//pkg/runtime/serializer:go_default_library",
        "//pkg/watch:go_default_library",
    ],
)
