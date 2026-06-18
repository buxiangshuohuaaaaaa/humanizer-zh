# humanizer-zh

> 基于 [Humanizer: Remove AI Writing Patterns](https://github.com/nicholasgasior/humanizer) 本土化改造的中文版 skill，原框架来自维基百科 [WikiProject AI Cleanup](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)。

去除中文文本里的 AI 味。覆盖 36 个中文 AI 写作典型模式，支持按语境切换判断标准。

## 覆盖的模式

| 类别 | 典型问题 |
|------|---------|
| 内容 | 意义拔高、媒体堆砌、"-着"分析、宣传腔、模糊出处、"挑战与展望"套路 |
| 语言 | 高频 AI 词（赋能/旨在/打造/夯实）、回避"是"、"不仅……更……"成瘾、排比强迫、同义词循环、假范围、被动无主语、翻译腔 |
| 格式 | 破折号滥用、加粗滥用、"**标题：**内容"列表、标题对仗成癖、emoji 装饰、引号混乱、中英文空格 |
| 沟通 | 助手协作残留、知识截止说明、谄媚语调 |
| 填充 | 填充短语、过度对冲、通用乐观结尾、四字成语堆砌、权威感修辞、路标语、小标题复述段、差异锚定、金句轰炸、格言公式、假坦诚开场、互联网黑话（赋能/抓手/闭环） |

## 语境驱动

改写前先判断语境，标准完全不同：

- **A 个人 / 社交**：朋友圈、小红书、知乎、个人博客 → 要有观点、节奏变化、允许口语
- **B 商业 / 实用**：商品描述、邮件、广告文案、周报 → 具体、简洁、信息密度高，中性即正确的人声
- **C 学术 / 公文**：报告、论文、官方说明 → 中立、平实、有出处

## 使用方式

将 `SKILL.md` 放入你的 Claude skill 目录（如 `~/.claude/skills/` 或项目内 `skills/`），在 Claude Code 或支持 skill 的客户端里调用即可。

## 致谢

- 原版 skill：**Humanizer: Remove AI Writing Patterns**（基于维基百科 Signs of AI writing 框架）
- 维基百科：[Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)，由 WikiProject AI Cleanup 维护

## License

MIT
