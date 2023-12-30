这个项目包含了 Leptos 新的入门指南核心。

它是由 `mdbook` 构建。你可以安装 `mdbook` 来查看本地副本。

```sh
cargo install mdbook
```

这本书还使用了一个名为 `mdbook-admonish` 的 mdbook 预处理器来设置文本块的样式，如注释，警告等。

安装 mdbook admonish 来使用：

```sh
cargo install mdbook-admonish
```

然后用以下命令运行本书

```sh
mdbook serve
```

他应该可以在 `http://localhost:3000` 上可用。