# NodeInject

适用于 Typora v1.9.5 及以前版本

## 构建

需要 Rust 开发环境，在根目录和 license-gen 目录下分别执行构建命令得到 node_inject.exe 和 license-gen.exe 程序。

```bash
cargo build
```

## 使用

将生成的 \target\debug 目录中的 node_inject.exe 和 license-gen.exe 复制到 Typora 安装目录下执行

```bash

.\node_inject.exe

.\license-gen.exe
```

最终在 Typora 中填入生成的 License 就行了。


### Thank
https://github.com/DiamondHunters/NodeInject 
