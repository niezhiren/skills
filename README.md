# ClassIn Agent Skills

用 AI 开发适用于 ClassIn 桌面端内置浏览器和 Windows 大屏 ClassIn X 的网页课件。技能涵盖 Chromium 版本兼容、单指触控、浏览与批注模式、课堂共享和真机验收。

| 技能 | 适用场景 |
| --- | --- |
| [ClassIn 网页课件开发](skills/classin-web-courseware/SKILL.md) | 开发、改造和验收互动练习、课堂小游戏与在线教具 |

## 安装

在课件项目目录运行以下命令，然后选择你使用的 AI 编程工具。

```bash
npx skills add niezhiren/skills --skill classin-web-courseware
```

## 使用示例

在 AI 编程工具中输入：

> 使用 classin-web-courseware 技能，帮我做一个小学英语单词和图片配对课件。老师要能在 ClassIn PC 内置浏览器里用鼠标操作，也能在 ClassIn X 大屏上用一根手指作答。拖拽之外，请提供先点单词、再点图片的操作方式，并给出真机验收步骤。

## TTS 口音测试

复制 [TTS 口音测试页](https://niezhiren.github.io/skills/) 的地址，在 ClassIn 或 ClassIn X 的内置浏览器打开。选「美式」或「英式」，从下拉框选择本地音色，再点「指定本地声音播放」。页面会显示这次传入的音色和地区。缺少对应地区的声音时，可在系统中添加语音包后重开客户端。

[查看测试页源码](docs/index.html)

## 阅读和下载

- [在线阅读 SKILL.md](skills/classin-web-courseware/SKILL.md)
- [从 GitHub 下载 SKILL.md](https://raw.githubusercontent.com/niezhiren/skills/refs/heads/main/skills/classin-web-courseware/SKILL.md)（打开原文后可另存为文件）

下载后可把 `SKILL.md` 附到 AI 对话里，并请它按文档开发或检查课件。
