# rules_protobuf
git_repository(
  name = "org_pubref_rules_protobuf",
  remote = "https://github.com/pubref/rules_protobuf",
  tag = "v0.7.1",
)

# rules_go
git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.4.4",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories")
go_repositories()

# C++
load("@org_pubref_rules_protobuf//cpp:rules.bzl", "cpp_proto_repositories")
cpp_proto_repositories()

# Go
load("@org_pubref_rules_protobuf//go:rules.bzl", "go_proto_repositories")
go_proto_repositories()

# Java
load("@org_pubref_rules_protobuf//java:rules.bzl", "java_proto_repositories")
java_proto_repositories()

# Python
load("@org_pubref_rules_protobuf//python:rules.bzl", "py_proto_repositories")
py_proto_repositories()
