java_test(
    name = "tests",
    size = "small",
    srcs = glob(["*.java"]),
    data = ["//examples:example_configs"],
    test_class = "build.buildfarm.AllTests",
    deps = [
        "//src/main/java/build/buildfarm/common",
        "//src/main/java/build/buildfarm/common/config",
        "//src/main/java/build/buildfarm/instance",
        "//src/main/java/build/buildfarm/server/services",
        "//src/main/protobuf:build_buildfarm_v1test_buildfarm_java_proto",
        "//src/test/java/build/buildfarm:test_runner",
        "@maven//:com_google_protobuf_protobuf_java",
        "@maven//:com_google_truth_truth",
        "@maven//:io_grpc_grpc_stub",
        "@maven//:org_mockito_mockito_core",
        "@remote_apis//:build_bazel_remote_asset_v1_remote_asset_java_proto",
    ],
)
