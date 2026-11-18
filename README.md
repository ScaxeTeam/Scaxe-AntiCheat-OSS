# Scaxe-AntiCheat-OSS

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans)

基于 Conformer 架构的 Minecraft 时序行为反作弊模型权重（`PRC-Open-0.5.5-1M`）。

## 模型信息

| 项目 | 参数 |
| --- | --- |
| 模型文件 | [`PRC-Open-0.5.5-1M.safetensors`](./PRC-Open-0.5.5-1M.safetensors) |
| 网络结构 | Conformer（`d_model=192`, `layers=4`, `heads=8`） |
| 参数规模 | `983,546` |
| 输入维度 | `[B, 80, 84]`（`float32`） |
| SHA-256 | `91afc7bbaf9c195f39eb6c883f15d9de54d5e7735ace9493e11852a55af9692d` |

## 许可协议

本仓库采用 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans)**（署名-非商业性使用-相同方式共享 4.0 国际）协议开源，详见 [`LICENSE`](./LICENSE)：

- **署名（BY）**：分发或衍生修改须保留 **SCAXE Team** 原始署名及本仓库链接；
- **非商业性使用（NC）**：禁止用于任何商业用途；
- **相同方式共享（SA）**：任何衍生作品须以相同的 **CC BY-NC-SA 4.0** 协议开源。
