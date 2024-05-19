load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
  name = "com_google_googletest",
  urls = ["https://github.com/google/googletest/archive/5ab508a01f9eb089207ee87fd547d290da39d015.zip"],
  strip_prefix = "googletest-5ab508a01f9eb089207ee87fd547d290da39d015",
  integrity = "sha256-dV+aObxyBfWgxCjpIN2tCSwzyKG0aZfe8/HUqCre1uE=",
)

http_archive (
  name = "glfw",
  urls = ["https://github.com/glfw/glfw/archive/refs/tags/3.4.tar.gz"],
  sha256 = "c038d34200234d071fae9345bc455e4a8f2f544ab60150765d7704e08f3dac01",
  strip_prefix = "glfw-3.4",
  build_file = "@//:glfw.BUILD",
)
