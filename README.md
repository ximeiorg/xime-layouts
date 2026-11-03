# Xime 键盘布局合集

给 [Xime](https://github.com/ximeiorg/Xime)（Android 输入法，Rime 内核）做的键盘布局预设。每个目录是一份完整的 `xime.custom.yaml`，放进 Xime 的用户配置目录就能用；目录名即布局风格。

> Keyboard layout presets for Xime. Each folder holds one `xime.custom.yaml` that overrides the built-in layout by style (WeChat / Sogou).

![license](https://img.shields.io/badge/license-GPL--3.0-blue)

## 布局一览

| 目录 | 风格 | 覆盖范围 | 主色 |
|---|---|---|---|
| [`wetype/xime.custom.yaml`](wetype/xime.custom.yaml) | 微信输入法 | 26 键、九键、数字面板、通用符号；亮/暗双套配色 | 微信绿 `#07C160` |
| [`sougou/xime.custom.yaml`](sougou/xime.custom.yaml) | 搜狗输入法 | 26 键、九键、数字面板、通用符号；亮色按截图实测 | 搜狗蓝 `#4C8DFF` |

两份配置都只写「和内置 `xime.yaml` 不一样的部分」，没写的字段自动回退内置值。

## 安装

请到app 扩展商店->布局安装下载

## 发布

在 GitHub 发布 Release 时，[`release.yml`](.github/workflows/release.yml) 会把每个包含 YAML 的目录分别打成 `dist/<目录名>.zip` 并上传为 Release 附件，方便直接下载对应风格。

## 许可证

[GPL-3.0](LICENSE)，与上游 Xime 一致。

```
Copyright (C) 2026 kingzcheung
```
