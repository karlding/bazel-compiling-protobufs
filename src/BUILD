load("@org_pubref_rules_protobuf//protobuf:rules.bzl", "proto_compile")

filegroup(
    name = "protos",
    srcs = glob([
        "*.proto",
    ]),
)

proto_compile(
    name = "pluriproto",
    protos = [":protos"],
    langs = [
        "@org_pubref_rules_protobuf//python",
        "@org_pubref_rules_protobuf//java",
        "@org_pubref_rules_protobuf//cpp",
        "@org_pubref_rules_protobuf//go",
    ],
    verbose = 2,
    with_grpc = True,
)
