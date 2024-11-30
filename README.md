# pure-python-extension-pack README

[English](README.md) | [简体中文](README-zh.md)

This pack only adds extensions that are strongly related to Python,
so that users can disable the relevant extensions with one click when needed.

Although VS Code already provides tools like [profiles](https://code.visualstudio.com/docs/editor/profiles) to help users manage extensions,
imagine a scenario where I create two profiles for Rust and Python separately.
The Rust profile includes all the extensions I need for Rust development,
and the Python profile also contains the necessary extensions for developing Python applications.
However, if I need to use Rust to develop modules callable by Python,
then I have no choice but to create a new profile that includes all the extensions from both the Rust and Python profiles.

This situation is not uncommon; seeing more and more profiles is frustrating, and switching between different profiles increases cognitive load on users.
Given that [VSCode has no plans to develop categorized extension management](https://github.com/microsoft/vscode/issues/20599), using an extension pack seems like a good solution.

## Extensions

- **Python**: The core extension for Python development in VS Code. [GitHub](https://github.com/microsoft/vscode-python)
- **Pylance**: A fast, feature-rich language support extension for Python. [GitHub](https://github.com/microsoft/pylance-release)
- **mypy**: A static type checker for Python to ensure type correctness. [GitHub](https://github.com/python/mypy)
- **debugpy**: The debugger for Python used in VS Code. [GitHub](https://github.com/microsoft/debugpy)
- **Jupyter**: An extension to work with Jupyter Notebooks in VS Code. [GitHub](https://github.com/microsoft/vscode-jupyter)
- **Ruff**: A fast Python linter and formatter for enforcing code style. [GitHub](https://github.com/astral-sh/ruff)
- **VizTracer**: A powerful tool for visualizing Python code execution and performance. [GitHub](https://github.com/gaogaotiantian/viztracer)
- **autoDocstring**: Automatically generate Python docstrings for your functions and classes. [GitHub](https://github.com/NilsJPWerner/autoDocstring)