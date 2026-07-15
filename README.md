# SkyHanni 汉化补丁

> **你是否曾因为 SkyHanni 没有汉化而烦恼？SkyHanni 汉化来了！**

本项目是基于 [Vault Patcher](https://github.com/3093FengMing/VaultPatcher)（保险库补丁）模组实现的硬编码汉化。由于工程量较大，大部分翻译由 AI 辅助完成，**翻译覆盖率达 99%**。

> **声明**：本项目仅为 SkyHanni 模组的汉化补丁，原模组版权归原作者所有。本项目仅作为语言补充包使用，请勿用于任何商业用途。

---

## 一、使用步骤

1. 下载 [Vault Patcher](https://github.com/3093FengMing/VaultPatcher)（保险库补丁）模组。
2. 将本补丁的所有文件拖入游戏主目录（即包含 `config` 文件夹、`mods` 文件夹等的根目录）。
3. 启动游戏，汉化即可生效。

---

## 二、更新汉化补丁

SkyHanni 更新频繁，若官方更新后汉化失效，请按以下步骤手动适配新版本：

1. 找到文件：

   ```
   vaultpatcher\modules\SkyHanni-xxx.json
   ```

2. 将文件名中的 `SkyHanni-xxx` 替换为你当前的模组版本号，例如：

   ```
   SkyHanni-7.34.0-mc26.1
   ```

3. 找到配置文件：

   ```
   config\vaultpatcher_asm\config.json
   ```

4. 用记事本打开 `config.json`，将 `"modules": ["xxx"]` 中的 `xxx` 替换为你的模组名称，例如：

   ```json
   "modules": ["SkyHanni-7.34.0-mc26.1"]
   ```

5. 保存文件，启动游戏即可。

---

## 三、自定义翻译

如果你对某些翻译不满意，可以自行修改，也可随时对照英文原文进行校对。

### 修改步骤

1. 找到待修改的文件：

   ```
   vaultpatcher\modules\SkyHanni-xxx.json
   ```

2. 用记事本打开对应的 `.json` 文件。

3. 按 `Ctrl + F` 搜索你要修改的文本。

4. 将翻译修改为你喜欢的版本，**保存文件**。

5. 启动游戏即可看到修改后的翻译效果。
