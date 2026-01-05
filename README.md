# STranslate Claude 翻译插件

基于 Anthropic Claude API 的 STranslate 翻译插件。

## 📦 安装

1. 下载最新的 `.spkg` 文件（在 [Releases](https://github.com/STranslate/STranslate.Plugin.Translate.Claude/releases) 页面）
2. 在 STranslate 中进入 **设置** → **插件** → **安装插件**
3. 选择下载的 `.spkg` 文件并重启 STranslate

## ⚙️ 配置

1. **获取 API Key**: 访问 [Anthropic Console](https://console.anthropic.com/) 注册并获取 API Key
2. **配置插件**: 在 STranslate 中进入 **设置** → **服务** → **Claude** → **设置**
   - **API Key**: 你的 Anthropic API Key
   - **API URL**: `https://api.anthropic.com`（默认）
   - **模型**: `claude-haiku-4-5` / `claude-sonnet-4-5` / `claude-opus-4-5`
   - **温度**: 0-2，默认 0.7

### 提示词模板

支持自定义提示词，内置：
- **翻译** - 专业翻译引擎
- **润色** - 文本润色优化
- **总结** - 文本摘要生成

提示词变量：`$source`（源语言）、`$target`（目标语言）、`$content`（待翻译文本）

## 📄 许可证

[MIT](LICENSE)

---

**Made with ❤️ by [zggsong](https://github.com/zggsong)**
