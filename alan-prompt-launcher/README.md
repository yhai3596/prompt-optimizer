# Alan Prompt Launcher

AI 场景提示词快速调用器：从 Prompt Launcher 逐步升级到本地 Prompt Router，并在 v1.0.0 增加可选 LLM 语义路由。

## 当前版本

- Latest: **v1.0.0**
- Latest source: `latest/`
- Historical archives: `releases/archives/`
- Checksums: `releases/SHA256SUMS.txt`
- Changelog: `CHANGELOG.md`

## 核心能力

- 场景分类、搜索、收藏、最近使用
- ChatGPT / Claude 输入框读取、插入、复制兜底
- 本地智能路由、路由校准、批量测试集
- 提示词组合推荐
- 提示词库新增、编辑、导入、导出
- 诊断面板、展开大屏、演示模式
- 页面风格切换
- 可选 LLM 语义路由，失败自动回退本地规则

## 安装方式

1. 下载 `releases/archives/Alan_Prompt_Launcher_v1_0_0.zip`。
2. 解压到本地目录。
3. 在 Chrome / Edge 扩展管理页打开“开发者模式”。
4. 点击“加载已解压的扩展程序”。
5. 选择解压后的 `Alan_Prompt_Launcher_v1_0_0` 文件夹。

## 目录说明

```text
alan-prompt-launcher/
├── latest/                  # v1.0.0 最新源码
├── releases/
│   ├── archives/            # 所有历史版本 zip 包
│   └── SHA256SUMS.txt       # 历史版本校验值
├── docs/
│   └── INSTALL.md           # 安装与维护说明
├── CHANGELOG.md             # 历史版本更新记录
└── README.md
```

## 注意

- API Key 只保存在浏览器本地存储中。
- 不启用 LLM 语义路由时，插件完全使用本地规则和校准数据。
- 客户演示建议使用演示模式，不配置真实 API Key。
