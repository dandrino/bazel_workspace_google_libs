load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

# Protobuf

git_repository(
  name = "bazel_skylib",
  remote = "https://github.com/bazelbuild/bazel-skylib",
  branch = "master",
)

git_repository(
  name = "com_google_protobuf",
  remote = "https://github.com/google/protobuf",
  commit = "master",
  init_submodules = 1,
)

load("@com_google_protobuf//:protobuf_deps.bzl", "protobuf_deps")

protobuf_deps()


# ABSL

git_repository(
  name = "com_google_absl",
  remote = "https://github.com/abseil/abseil-cpp.git",
  branch = "master",
  init_submodules = 1,
)
