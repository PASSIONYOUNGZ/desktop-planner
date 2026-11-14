# 桌面日程 · Desktop Planner

一个可以贴在屏幕边缘的 Windows 日程组件。鼠标移上去就能看计划、记任务，用完自动收起。

An edge-docked Windows planner for daily tasks and weekly goals. Hover over the edge tab to open it, then let it tuck away when you move on.

[简体中文](#下载) · [English](README.en.md)

## 下载

**当前版本 v1.2.2** · Windows 10 1903 及更新版本、Windows 11（x64）

| 版本 | 功能 | ZIP 下载 | 解压后 | 下载入口 |
| --- | --- | ---: | ---: | --- |
| **本地版** | 日程、任务颜色、贴边、总览、格言、导出 | 0.71 MB | 1.92 MB | [GitHub](https://github.com/PASSIONYOUNGZ/desktop-planner/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-local.zip) · [CNB](https://cnb.cool/passionyoungz/desktop-planner/-/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-local.zip) |
| **完整版** | 本地版全部功能，加上可选的飞书文档双向同步 | 13.94 MB | 49.83 MB | [GitHub](https://github.com/PASSIONYOUNGZ/desktop-planner/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-full.zip) · [CNB](https://cnb.cool/passionyoungz/desktop-planner/-/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-full.zip) |

两个版本都是 ZIP 便携包。完整解压后双击 `桌面日程.exe`，保留旁边的 DLL 和配置文件。两版使用 Windows 自带的 .NET Framework 4.8 或 4.8.1，无需单独安装 .NET 10 或 Codex。两版均可离线做本地计划，完整版按需在「高级设置 → 数据」连接飞书。

首次下载也可选 7z，完整解压后用法相同。本地版 0.52 MB（[GitHub](https://github.com/PASSIONYOUNGZ/desktop-planner/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-local.7z) · [CNB](https://cnb.cool/passionyoungz/desktop-planner/-/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-local.7z)），完整版 9.86 MB（[GitHub](https://github.com/PASSIONYOUNGZ/desktop-planner/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-full.7z) · [CNB](https://cnb.cool/passionyoungz/desktop-planner/-/releases/download/v1.2.2/desktop-planner-1.2.2-windows-x64-full.7z)）。

在「高级设置 → 常规 → 关于与更新」检查新版。无论最初从哪里下载，软件内更新统一走 CNB，并自动选择已安装的版本类型。

## 界面预览

| 今日计划 | 周计划 | 进度总览 |
| :---: | :---: | :---: |
| <img src="screenshots/daily-zh.png" width="229" alt="今日计划，任务带颜色标记与勾选状态"> | <img src="screenshots/weekly-zh.png" width="229" alt="周计划，显示一周目标和完成进度"> | <img src="screenshots/overview-zh.png" width="229" alt="总览，按天显示完成比例与任务回顾"> |

[个性化设置截图](screenshots/settings-zh.png) · [英文界面](README.en.md#screenshots)

## 可以做什么

- **日计划和周计划**。添加、编辑、完成、删除任务，拖动排序或跨天移动，给任务上色。今天清单为空时，可以接续前一天未完成的任务。
- **贴边和托盘**。靠近屏幕任意一边收起，悬停展开。支持置顶、调整窗口大小、开机自启和自定义新建任务快捷键。
- **回看和导出**。查看近七天、自然周、自然月或全部进度，按日期回顾任务，按全部、本周或本月导出 Markdown 或 Word。
- **个性化**。支持中英文界面、主题配色、每日轮换格言、固定格言和自定义格言库。
- **飞书双向同步**。完整版可以连接自己有编辑权限的飞书文档，后台同步日计划和周计划。两台 Windows 电脑分别授权同一文档后，可同步该文档内的任务和完成状态。

[使用说明](docs/usage.zh-CN.md) · [版本记录](CHANGELOG.md) · [问题反馈](https://github.com/PASSIONYOUNGZ/desktop-planner/issues)

## 致谢

谢谢每一位试用并反馈的朋友。完整版使用[飞书官方 CLI](https://github.com/larksuite/cli)，分发包内附第三方许可。
