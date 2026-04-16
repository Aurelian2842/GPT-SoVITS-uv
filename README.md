<div align="center">

<h1>GPT-SoVITS</h1>
A Powerful Few-shot Voice Conversion and Text-to-Speech WebUI (refactored with uv).<br><br>

[![madewithlove](https://img.shields.io/badge/made_with-%E2%9D%A4-red?style=for-the-badge&labelColor=orange)](https://github.com/Aurelian2842/GPT-SoVITS)

<!-- img src="https://counter.seku.su/cmoe?name=gptsovits&theme=r34" /><br> -->

[![Python](https://img.shields.io/badge/python-3.10-blue?style=for-the-badge&logo=python)](https://www.python.org)
[![GitHub release](https://img.shields.io/github/v/release/Aurelian2842/gpt-sovits?style=for-the-badge&logo=github)](https://github.com/RVC-Boss/gpt-sovits/releases)

[![License](https://img.shields.io/badge/LICENSE-MIT-green.svg?style=for-the-badge&logo=opensourceinitiative)](https://github.com/RVC-Boss/GPT-SoVITS/blob/main/LICENSE)

**English** | [**中文简体**](./docs/cn/README.md)

</div>

---

## Previous Summary

You can find the full information about this project from [origin repository](https://github.com/RVC-Boss/GPT-SoVITS). This project is a fork of it (using uv for better compatibility)

## Installation

First, you need to install the [uv](https://docs.astral.sh/uv/getting-started/installation/). The project uses uv to manage the dependencies.

Then, you need to ensure that you have installed the Python 3.10 (If you did not, you can install it with `uv python install 3.10`), and it'll install the dependencies automatically by using following command:

```shell
uv sync
```

In the next step, you need to install some pretrained models:

```shell
uv run install.py -s <source>
```

* `<source>`: The source of the model. Available options: `HF`, `HF-Mirror`, `ModelScope`

In the end, you can run the project:

```shell
uv run webui.py # Launch the Web UI
# Other commands ...
```