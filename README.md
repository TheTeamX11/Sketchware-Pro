<p align="center">
  <img src="assets/Sketchware-Pro.png" style="width: 30%;" />
</p>

# Sketchware Pro
[![GitHub contributors](https://img.shields.io/github/contributors/TheTeamX11/Sketchware-Pro)](https://github.com/TheTeamX11/Sketchware-Pro/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/TheTeamX11/Sketchware-Pro)](https://github.com/TheTeamX11/Sketchware-Pro/commits/)
[![Discord server stats](https://img.shields.io/discord/790686719753846785)](http://discord.gg/kq39yhT4rX)
[![Total downloads](https://img.shields.io/github/downloads/TheTeamX11/Sketchware-Pro/total)](https://github.com/TheTeamX11/Sketchware-Pro/releases)
[![Repository Size](https://img.shields.io/github/repo-size/TheTeamX11/Sketchware-Pro)](https://github.com/TheTeamX11/Sketchware-Pro)

欢迎来到 Sketchware Pro！在这里，你可以找到 Sketchware Pro 中许多类的源代码，更重要的是，这是一个为 Sketchware Pro 做出贡献的地方。

## 构建应用
要构建此应用，你必须使用 Gradle。强烈推荐使用 Android Studio 以获得最佳体验。

### 源代码结构

| 类名           | 作用                                        |
| -------------- | ------------------------------------------- |
| `a.a.a.ProjectBuilder` | 用于编译整个项目的辅助类                  |
| `a.a.a.Ix` | 负责生成 AndroidManifest.xml               |
| `a.a.a.Jx` | 生成 Activity 的源代码                     |
| `a.a.a.Lx` | 生成组件（例如监听器等）的源代码           |
| `a.a.a.Ox` | 负责生成布局的 XML 文件                    |
| `a.a.a.qq` | 内置库依赖的注册表                         |
| `a.a.a.tq` | 负责编译对话框中的提示/问答                |
| `a.a.a.yq` | 组织 Sketchware 项目的文件路径             |

> [!TIP]
> 你也可以查看 `mod` 包，其中包含了大多数贡献者的更改。

## 贡献

如果你想为 Sketchware Pro 做出贡献，请按照以下步骤操作：

1. Fork 此仓库。
2. 在你 Fork 的仓库中进行更改。
3. 测试这些更改。
4. 在此仓库中创建 Pull Request。
5. 你的 Pull Request 将由仓库成员审核，并在通过后合并。

我们欢迎任何规模的贡献，无论是大型功能还是错误修复，但请注意所有贡献都会被认真审核。

### 提交信息

当你对一个或多个文件进行更改时，需要使用提交信息（commit message）来提交这些更改。以下是一些指南：

- 保持提交信息简洁且清晰。
- 使用以下提交类型作为前缀之一：
  - `feat:` 用于新功能或对现有功能的改进
  - `fix:` 用于修复问题，例如修复 bug
  - `style:` 用于与样式相关的更改
  - `refactor:` 用于对代码结构的重构
  - `test:` 用于测试相关内容
  - `docs:` 用于文档相关内容
  - `chore:` 用于代码维护（也可以使用表情来表示类型）

示例：
- `feat: 使用新技术加快编译速度`
- `fix: 修复某些设备启动时崩溃的问题`
- `refactor: 重构 File.java 中的代码`

> [!IMPORTANT]
> 如果你想添加新功能，并且不需要修改除 `pro.sketchware` 之外的其他包，请在 `pro.sketchware` 包中进行更改，并遵循现有的目录结构和命名规范。此外，尽管项目可以正常编译你添加的 Kotlin 类，但除非确有必要，请尽量使用 Java 而不是 Kotlin。

## 感谢你的贡献

感谢你为 Sketchware Pro 做出贡献！你的贡献帮助 Sketchware Pro 持续发展。每一个被接受的贡献都会记录在“About Team”活动中。我们会默认使用你的 GitHub 用户名和头像，但当然可以进行更改。

## Discord

想与我们聊天、讨论更改，或者只是放松一下？我们有一个 Discord 服务器供你使用。

[![加入我们的 Discord 服务器！](https://invidget.switchblade.xyz/kq39yhT4rX)](http://discord.gg/kq39yhT4rX)

## 免责声明

此修改版并非出于任何恶意目的（例如损害 Sketchware）；恰恰相反，它是由社区为社区创建的，旨在让 Sketchware 得以延续。请自行决定是否使用，并考虑通过 Patreon 支持开发者。不幸的是，目前其他支持方式已不可用，因此 Patreon 是唯一的支持途径。你可以在这里找到他们的 Patreon 页面：https://www.patreon.com/sketchware

我们不允许将 Sketchware Pro 原样或经过修改后发布到 Play 商店或任何其他应用商店。请注意，该项目仍然是一个修改版（mod）。未经授权对应用进行修改通常被视为非法行为，我们不鼓励这种行为。

我们非常热爱 Sketchware，并感谢其开发者创造了如此优秀的应用。然而，我们已经很长时间没有收到更新。因此，我们决定通过创建这个修改版来让 Sketchware 延续下去，而且它是完全免费的。我们不会收取任何费用 :)
