# MEMORY.md - 小说家

## 用户偏好

- **喜欢《恶搞一家人》(Family Guy)** 的内核精神
  - 喜欢 Stewie Griffin（中国粉丝叫他"饺子"），但更喜欢这部动画的讽刺幽默风格

## GitHub 仓库

- **ai_novel**: https://github.com/FunkyGod/ai_novel (master)
  - **唯一内容仓库**，短篇 + 长篇连载都在这里
  - **短篇路径**：`/Users/gudaixin/Code/ai_novel/src/content/short/`（真实GitHub仓库，唯一写作位置）
  - 长篇连载 → `src/content/chapters/`
  - novelist 仓库保留作为 workspace，内容已合并到 ai_novel（2026-03-27）
  - **以后所有小说（短篇+长篇）都在 ai_novel 的 master 分支编写和推送**
  - **Frontmatter 格式要求（重要！）**：
    - short 类型：title, description, author, publishedAt, tags, cover
    - chapters 类型：title, series, seriesTitle, chapterNumber(正整数), description, publishedAt, status(ongoing/completed), tags

- **喜欢《恶搞一家人》(Family Guy)** 的内核精神
  - 喜欢 Stewie Griffin（中国粉丝叫他"饺子"），但更喜欢这部动画的讽刺幽默风格

## 定时写作任务（2026-03-27更新）

### ai-novelist agent
- **Agent workspace**: `/Users/gudaixin/Code/ai_novel`
- **短篇写作**: 每1小时，写科幻+魔幻+现实主义混合风格
- **GitHub推送**: 每12小时，推送到 ai_novel master 分支
- **保存路径**: `src/content/short/`

## 写作任务调整

- **《招魂：台湾之旅》长篇连载已永久取消**（2026-03-27）
  - 用户要求永久停止，任务已从cron中移除
  - 已写至第1021章（共十三个小故事）
  - 仅保留短篇故事和每日写作反思任务

## 已完成任务

- 2026-03-14: 写了恐怖小说《招魂：台湾之旅》并发布到番茄小说
