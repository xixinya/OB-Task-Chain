# OB Task Chain

**OB Task Chain** 是一个 Windows 应用程序，旨在实时监控并显示 Warframe 日志中的最新任务阶段。该程序读取 Warframe 日志文件，解析 JSON 内容以提取任务阶段，并以用户友好的方式展示，使用颜色编码表示优先级。应用程序作为独立的可执行文件（`.exe`）运行，使用 C++ 和 Python 编写了两个版本。

## 功能特点

- **实时日志监控**：持续读取并根据最新日志条目更新显示内容。
- **颜色编码输出**：根据任务阶段的优先级使用不同颜色进行高亮显示。
- **随机控制台标题**：随机更新控制台窗口标题以增加视觉效果。
- **错误处理**：提供错误反馈，例如文件访问问题或 JSON 解析错误。

## 安装步骤

1. **下载**：从 [发布页面](https://github.com/xixinya/OB-Task-Chain/releases) 获取可执行文件。
2. **运行**：在安装了 Warframe 的 Windows 系统上直接运行 `OB-Task-Chain.exe` 文件。

## 使用说明

1. **启动** 可执行文件。
2. **选择赏金** 在游戏中选择赏金任务。
3. **监控** 控制台以获取任务阶段的实时更新。

## 关键概念

- **任务阶段**：根据预定义的映射将不同的任务阶段翻译并显示。
- **高亮显示**：高优先级的任务阶段用红色显示，中等优先级用黄色显示，其余用绿色显示。
- **文件访问**：使用内存映射高效读取 Warframe 日志文件。

## 常见问题

- **文件访问问题**：确保 Warframe 正在运行，并且日志文件路径正确。
- **JSON 解析错误**：检查日志文件的格式，确保其包含有效的 JSON 数据。
- **控制台显示问题**：检查控制台编码，在部分机型上 C++版本可能会出现乱码问题 请使用utf-8版本或python版本。
- **[发生错误]: [无法打开文件]**：C++版本C:\Users的用户名不能是中文的 请修改为英文后重新运行。
## 警告

**请注意**：如果您通过非官方渠道获取了此软件，可能是伪造品。请确保从可信的来源下载软件。

## 许可证

此项目为闭源软件。作者保留所有权利。禁止重新分发和修改。

## 联系方式

- **作者**：小昕
- **QQ群**：285339589
- **GitHub 仓库**：[xixinya/OB-Task-Chain](https://github.com/xixinya/OB-Task-Chain)

## 致谢

- 感谢 Warframe 开发者提供详细的日志格式。
- 特别感谢开源社区提供的库和工具。

---

享受使用 **OB Task Chain** 监控任务阶段的体验！
