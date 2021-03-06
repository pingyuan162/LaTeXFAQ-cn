# LaTeX 格式指南

## 原则

1. 注重内容与格式分离

1. 尽量遵从 [W3C 中文排版需求](https://w3c.github.io/clreq/)

## 字体下载

模板所需的思源字体的下载链接：[https://pan.baidu.com/s/1-9P_UWsV7GF5vEbjdBGlHw](https://pan.baidu.com/s/1-9P_UWsV7GF5vEbjdBGlHw)  密码：ji3i

## 总体样式

1. 所有文件以 UTF-8（无 BOM）保存，行尾使用 LF
    - TeX 系统大多部署在 Linux 上，以 Linux 格式为准

1. 每行不超过 100 字符，其中汉字以两个字符计算
    - 目的在于便于 Git 管理，同时适用于正常的屏幕尺寸，代码中常用的 80 字符宽对文档来说可能较窄
    - 例外：过长的网址，但可采用短域名服务

1. 使用空格缩进，不使用 `Tab`。每层次的缩进使用 2 个空格
    - 遵循 `l3styleguide`

1. 编译使用 XeTeX 引擎
    - LuaTeX 的中文适配仍略有不完备之处，且编译速度较慢

1. 中西文之间留有空格

## 标点、符号

1. 除非必要，不可使用全宽（全角）空格

## 公式

1. 行内公式使用 `$...$`，不使用 `\(...\)`

## 杂项

1. TeX、LaTeX 等使用 `\TeX{}`、`\LaTeX{}`，以保证正确排版以及之后的空格。特例：LaTeX3 使用 `\LaTeX3`
    - 遵循 `l3styleguide`
