# dsh-whale-notify

Chime and a cute whale card when a turn finishes or DSH needs your reply.

DeepSeek Harness（DSH）插件。**本仓库是发布镜像**，源码与开发在 [DIY-code](https://github.com/YYY-DXS/DIY-code) 的 plugins/whale-notify/；两份内容由 	ools/publish-plugin.ps1 同步，不要只改这里。

## 安装

```bash
dsh plugin add github:YYY-DXS/dsh-whale-notify
```

安装后在 **设置 → 插件** 里确认该行已启用；首次使用前按下面「配置」填好路径。

## 配置

```yaml
- insert:
    - id: whale-notify
      name: 'dsh-whale-notify'
```

## 兼容性

- DSH：`>=0.1.0-rc.6 <0.3.0-0`
- Node：`>=18`
- 平台：Windows

## 许可

MIT，见 [LICENSE](LICENSE)。