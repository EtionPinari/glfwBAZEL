load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

cc_binary(
  name = "main",
  srcs = ["main.cpp"],
  deps = [
    "@glfw//:glfw",
  ],
  defines = [
    "GLAD_GL_IMPLEMENTATION",
  ],
  visibility = ["//visibility:public"],
)