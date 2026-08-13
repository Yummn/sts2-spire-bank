# 尖塔银行（Spire Bank）

我想给商店里的闲钱增加一点长期规划，于是做了这个银行 MOD。它会在商店左侧放一块紧凑的小木牌，可以存入或取出金币；账户余额跟随当前游戏档案保存，并能跨局继承。

## 玩法

- 每次存款会花费 10 金币，其中 5 金币进入账户，另外 5 金币作为手续费。
- 金币少于 10，或已经是负数时，不能继续存款。
- 每次取款最多取出 10 金币；余额不足 10 时会一次取完。
- 如果金币为负，取出的金币会先用于抵消欠款。
- 不依赖 BaseLib，也不包含 PCK 资源。

当前版本为 [v0.1.6](https://github.com/Yummn/sts2-spire-bank/releases/tag/v0.1.6)。这一版把银行面板进一步收窄并移到商店左侧，尽量不遮挡商品。

## 安装

在 Releases 中下载与游戏版本相符的压缩包：

- `Mobile-v103-PC-v107`：Android v0.103.2 或 PC v0.107.x
- `Mobile-v110.1`：Android v0.110.1

解压后，把完整的 `SpireBank` 文件夹放进游戏的 `mods` 目录。不同版本的 DLL 不要混用。

本仓库目前只保留安装说明；历史包和最新版都可以在 [GitHub Releases](https://github.com/Yummn/sts2-spire-bank/releases) 找到。
