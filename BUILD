platform(
  name = "rbe_ubuntu1804_java11_platform",
  exec_properties = {
    "dockerNetwork": "standard",
    "dockerPrivileged": "true",
    "Pool": "default",
  },
  parents = ["@rbe_ubuntu1804_java11//config:platform"],
)

cc_binary(
  name = "hello",
  srcs = ["hello.cc"],
)
