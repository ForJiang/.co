# .co

> 部署测试草稿仓库
>
> Scratch repo for deployment tests

## 这是什么 / What is this

- `.github/workflows/azure-webapps-node.yml` — Azure Web Apps 的 Node.js 部署工作流（GitHub 自动生成的默认模板，`AZURE_WEBAPP_NAME` 仍是占位符 `your-app-name`，未适配任何实际项目）
- `.github/workflows/Keynote.webarchive` — 一个 Keynote 导出的 web 存档（约 9.8MB），仅作文件暂存
- 没有源码、没有构建、没有部署目标 / No source code, no build, no deploy target.

> [!WARNING]
> 此仓库仅作临时草稿与测试用途，内容可能随时清空。
> This repo is a scratch pad for tests; contents may be wiped at any time.

> [!NOTE]
> 工作流在 push 到 `main` 时触发，但因为没有配置 `AZURE_WEBAPP_PUBLISH_PROFILE` 也不存在可构建的应用，Actions 里的部署运行注定失败，可忽略。
> The workflow triggers on push to `main`, but with no publish profile configured and no app to build, its Actions runs are expected to fail and can be ignored.

## Author / 作者

**ForJiang** · [github.com/ForJiang](https://github.com/ForJiang)

License: [GPL-3.0](LICENSE) © 2026 ForJiang
