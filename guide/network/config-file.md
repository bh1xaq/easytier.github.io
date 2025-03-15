# 配置文件

支持使用 -c 参数指定配置文件路径。

```sh
easytier-core -c ./config.yaml
```

::: warning 注意
注意：配置文件的优先级更高，当运行时指定了配置文件，则命令行中除 `-c` 的其他参数将被忽略，只对配置文件生效。
:::

使用参数运行可以获得对应参数的配置文件。配置文件会打印在命令行中，可以手动复制对应配置保存为toml文件即可。

在不使用参数的情况下直接运行 `easytier-core` 可以获得最小配置文件。

## 配置文件生成工具

官网提供了配置文件生成工具，可以通过访问 <a target="_blank" href="https://easytier.cn/web/index.html#config_generator">配置文件生成工具</a> 来生成配置文件。
