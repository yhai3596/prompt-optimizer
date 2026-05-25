# 安装与维护说明

## 本地安装

1. 选择需要安装的版本 zip，例如 `Alan_Prompt_Launcher_v1_0_0.zip`。
2. 解压 zip。
3. 打开 Chrome / Edge：`chrome://extensions/` 或 `edge://extensions/`。
4. 开启“开发者模式”。
5. 点击“加载已解压的扩展程序”。
6. 选择解压后的插件目录。

## 更新版本

建议先删除旧版扩展，再加载新版目录，避免浏览器缓存旧脚本。

## 历史版本恢复

从 `releases/archives/` 选择对应 zip，解压后重新加载。

## 校验文件

使用 `releases/SHA256SUMS.txt` 校验 zip 是否完整。

Windows PowerShell 示例：

```powershell
Get-FileHash .\Alan_Prompt_Launcher_v1_0_0.zip -Algorithm SHA256
```

## LLM 语义路由

v1.0.0 支持 OpenAI-compatible Chat Completions 接口。未配置 API Key 时，插件仍使用本地规则路由。
