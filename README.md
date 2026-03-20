# Polymarket Account Analyzer — 文档站

本目录为 [Mintlify](https://mintlify.com) 项目，对外说明 **Polymarket Account Analyzer**（只读钱包分析、CLI + Axum API）。

- **入口配置**：`docs.json`（站点名、导航、主题色）
- **指南页**：`index.mdx`、`quickstart.mdx`、`architecture.mdx`、`configuration.mdx`、`development.mdx`
- **API**：`api-reference/openapi.json` + `api-reference/*.mdx`

## 本地预览

```bash
npm i -g mint
cd documents
mint dev
```

打开 **http://localhost:3000**。若与本仓库 **`polymarket-account-analyzer serve`** 同时运行，请为其中之一更换端口（二者默认均可能占用 3000）。

## 与源码的关系

分析器实现位于 monorepo 的 **`../polymarket-account-analyzer/`**；权威用法与配置细节以该目录下的 **[README](https://github.com/a9research/Polymarket-Analyzer/blob/main/README.md)** 为准。文档站侧重结构与快速上手，版本化细节以源码及主 README 为准。

## 发布

将本目录推送到已绑定 Mintlify 的 Git 仓库后，由 Mintlify 构建部署；详见 [Mintlify 文档](https://mintlify.com/docs)。
