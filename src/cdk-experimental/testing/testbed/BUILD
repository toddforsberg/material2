package(default_visibility = ["//visibility:public"])

load("//tools:defaults.bzl", "ts_library")

ts_library(
    name = "testbed",
    srcs = glob(
        ["**/*.ts"],
        exclude = ["**/*.spec.ts"],
    ),
    module_name = "@angular/cdk-experimental/testing/testbed",
    deps = [
        "//src/cdk-experimental/testing",
        "//src/cdk/testing",
        "@npm//@angular/core",
    ],
)
