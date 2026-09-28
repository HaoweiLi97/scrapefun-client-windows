# ScrapeFun Client for Windows

[产品主页](https://github.com/HaoweiLi97/ScrapeFun) · [稳定版下载](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/latest) · [全部发行](https://github.com/HaoweiLi97/scrapefun-client-windows/releases) · [在线文档](https://scrapefun.com/#/docs)

> 文档更新：2026-09-28。下列版本和资产为核对当日的稳定版；后续以对应 Release 为准。

Windows 桌面客户端，连接已有 ScrapeFun Server，浏览影视资源、使用原生播放器并阅读漫画。Client 与 Server 分别安装和更新。

## 下载与系统环境

| 项目 | 当前稳定版 |
| --- | --- |
| 版本 | [0.0.5](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/tag/v0.0.5) |
| 架构 | 当前安装程序同时支持 x64 / ARM64 |
| 手动安装 | `scrapefun-client-electron-windows-0.0.5-stable-x64-setup.exe` |
| 更新资产 | `latest.yml`、安装包 `.blockmap` |

从[稳定版下载页](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/latest)下载 setup。0.0.5 的安装包虽带 `x64` 文件名，发行说明明确支持 x64 与 ARM64；其他版本应重新核对，不应沿用这一判断。

0.0.5 未进行 Windows 代码签名，首次安装可能显示未知发布者提示。下载后核对官方来源和 Release；不要把该提示当作包已获得发布者签名。

## 安装与连接

1. 运行 setup，按向导安装并启动 ScrapeFun Client。
2. 输入 Server 地址，例如 `http://192.168.1.10:8096`。
3. 使用 Server 账号登录。

0.0.5 可在连接页面“发现服务器”。该功能需要局域网中的 Server 支持发现；没有结果时仍可手动填写地址。发现结果不会代替正常连接检查和登录。

## 更新与配置

可使用客户端更新机制，或运行新版 setup 覆盖安装。同一用户下通常保留服务器连接配置；不要主动删除客户端用户配置目录。更新过程中退出播放，完成后重新连接 Server。

## 故障排查

连接问题先检查 Server 状态、地址、端口及防火墙。播放问题请提供 Windows 版本、CPU 架构、Server 与 Client 版本、媒体编码和脱敏日志。

## 支持与授权

本仓库提供平台安装说明和官方发行资产。使用问题与功能建议请提交到[主仓库 Issues](https://github.com/HaoweiLi97/ScrapeFun/issues)；账号、激活或私密日志请联系 `scrapefun@outlook.com`。报告安全问题请按[安全说明](./SECURITY.md)私密提交。

新的商业许可声明见 [LICENSE](./LICENSE)，完整条款见[软件使用许可协议](./EULA.md)。个人、家庭及组织内部可正常使用；Pro 需有效授权，软件再分发、转售、客户交付和收费托管须单独书面授权。该声明不追溯改变既有授权；现有资产以其随包许可为准，第三方组件继续适用各自许可证。

[发行与兼容性说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.md) · [第三方组件说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.md) · [支持流程](./SUPPORT.md)
