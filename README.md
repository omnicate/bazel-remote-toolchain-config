# bazel-remote-toolchain-config
This hosts a publicly-accessible toolchain for remote bazel builds


```bash
../../bazelbuild/bazel-toolchains/rbe_configs_gen \
--bazel_version=6.4.0 \
--toolchain_container=registry.wgtwo.com/reg/infra/ci/bazel:dev-c388948d7a-1704801285 \
--output_src_root=./ \
--output_config_path=./ \
--exec_os=linux \
--target_os=linux \
--cpp_env_json cpp_env.json
```