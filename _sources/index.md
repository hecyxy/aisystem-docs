---
title: AISystem & AIInfra 
---

::::{grid}
:reverse:
:gutter: 2 1 1 1
:margin: 4 4 1 1

:::{grid-item}
:columns: 4

```{image} ./_static/logo-square.svg
:width: 150px
```
:::

:::{grid-item}
:columns: 8
:class: sd-fs-3

A Sphinx theme with a clean design, support for interactive content, and a modern book-like look and feel.
:::

::::

[Flexible content layout](reference/special-theme-elements.md)
: Inspired by beautiful online books, such as [the Edward Tufte CSS guide](https://edwardtufte.github.io/tufte-css/)

[Visual classes designed for Jupyter Notebooks](reference/notebooks)
: Cell inputs, outputs, and interactive functionality are all supported.

[Launch buttons for online interactivity](content/launch)
: For pages that are built with computational material, connect your site to an online BinderHub for interactive content.

[Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
: To style visual elements and add functionality.

International
: All text integrated in the theme is translated to the specified [Sphinx language](https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language).

:::{seealso}
This is the default theme in [Jupyter Book](https://jupyterbook.org).
:::

# === 一. AI 系统概述 ===

```{toctree}
:maxdepth: 1
:caption: === 一. AI 系统概述 ===

01Introduction/README
01Introduction/01Present
01Introduction/02Develop
01Introduction/03Architecture
01Introduction/04Sample
01Introductio/05Foundation
```

# === 二. AI 硬件体系结构 ===

```{toctree}
:maxdepth: 1
:caption: === 二. AI 硬件体系结构 ===

02Hardware/README
02Hardware01Foundation/README
02Hardware02ChipBase/README
02Hardware03GPUBase/README
02Hardware04NVIDIA/README
02Hardware05Abroad/README
02Hardware06Domestic/README
02Hardware07Thought/README
```

# === 三. AI 编译器 ===

```{toctree}
:maxdepth: 1
:caption: === 三. AI 编译器 ===

03Compiler/README
03Compiler01Tradition/README
03Compiler02AICompiler/README
03Compiler03Frontend/README
03Compiler04Backend/README
03Compiler06PyTorch/README
```

# === 四. 推理系统&引擎 ===

```{toctree}
:maxdepth: 1
:caption: === 四. 推理系统&引擎 ===

04Inference/README
04Inference01Inference/README
04Inference02Mobilenet/README
04Inference03Slim/README
04Inference04Converter/README
04Inference05Kernel/README
```

# === 五. AI 框架核心模块 ===

```{toctree}
:maxdepth: 1
:caption: === 五. AI 框架核心模块 ===

05Framework/README
05Framework01Foundation/README
05Framework02AutoDiff/README
05Framework03DataFlow/README
05Framework04Parallel/README
05Framework05AICluster/README
05Framework06AIAlgo/README
```

# === 附录内容 ===

```{toctree}
:caption: === 附录内容 ===
:maxdepth: 2

00Others/README
00Others/Instruments
00Others/Install
00Others/Inference
00Others/Glossary
00Others/Editors
00Others/Criterion
```
