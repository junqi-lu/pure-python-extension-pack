# pure-python-extension-pack README

[English](README.md) | [简体中文](README-zh.md)

这个 pack 中只添加了与 python 强相关的扩展。
以便在需要的时候用户能够一键禁用相关扩展。

尽管 vs code 已经提供了像 [profile](https://code.visualstudio.com/docs/editor/profiles) 这样的工具来帮助用户管理扩展。
但是设想这样一个场景，我分别创建了 rust 和 python 两个 profile。
rust profile 中包含了所有我在 rust 开发中需要用到的所有扩展。
python profile 也包含了开发 python 应用所需要的扩展。
但是假如我需要使用 rust 开发可供 python 调用的模块，
那么我就不得不创建一个新的 profile，
包括 rust 和 python profile 中的所有扩展。

这种情况并不少见，看到越来越多的 profile 是令人沮丧的，
在不同的 profile 之间切换也增加了用户的心智负担。
鉴于 [vscode 没有开发为扩展分类的计划](https://github.com/microsoft/vscode/issues/20599)，
使用 extension pack 来实现这一功能似乎是一个不错的办法。

## 扩展

- **Python**: VS Code 中进行 Python 开发的核心扩展。 [GitHub](https://github.com/microsoft/vscode-python)
- **Pylance**: 一个快速、功能丰富的 Python 语言支持扩展。 [GitHub](https://github.com/microsoft/pylance-release)
- **mypy**: 用于 Python 的静态类型检查器，确保类型的正确性。 [GitHub](https://github.com/python/mypy)
- **debugpy**: VS Code 中用于 Python 的调试工具。 [GitHub](https://github.com/microsoft/debugpy)
- **Jupyter**: 在 VS Code 中使用 Jupyter Notebook 的扩展。 [GitHub](https://github.com/microsoft/vscode-jupyter)
- **Ruff**: 一个快速的 Python 代码风格检查和格式化工具。 [GitHub](https://github.com/astral-sh/ruff)
- **VizTracer**: 一个强大的工具，用于可视化 Python 代码的执行和性能。 [GitHub](https://github.com/gaogaotiantian/viztracer)
- **autoDocstring**: 自动为您的函数和类生成 Python 文档字符串。 [GitHub](https://github.com/NilsJPWerner/autoDocstring)