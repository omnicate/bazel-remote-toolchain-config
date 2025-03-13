# bazel-remote-toolchain-config
This hosts a publicly-accessible toolchain for remote bazel builds


```bash
../../bazelbuild/bazel-toolchains/rbe_configs_gen \
--bazel_version=7.4.0 \
--toolchain_container=registry.wgtwo.com/pub/bazel-builder:prod-4f92974f0a-1704809442 \
--output_src_root=./ \
--output_config_path=./ \
--exec_os=linux \
--target_os=linux \
--docker_platform=linux/amd64 \
--cpp_env_json cpp_env.json
```
