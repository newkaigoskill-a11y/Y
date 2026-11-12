# 介護発信チーム

Claude Code で動かす、介護に関する発信をつくるAIチームです。

- **リーダー**:メインのClaude。行動指針は [`CLAUDE.md`](CLAUDE.md) に書いてあります
- **部下(6名)**:[`.claude/agents/`](.claude/agents/)

| 社員 | 役職 |
|---|---|
| kaigo-planner | 企画・リサーチ担当 |
| kaigo-writer | ライター |
| kaigo-checker | 品質チェック担当 |
| kaigo-video-director | 動画ディレクター |
| kaigo-video-editor | 動画編集担当 |
| kaigo-designer | デザイナー |

## 頼み方の例

- 「今週の発信テーマを企画して」
- 「『夜勤の眠気対策』で、現場職員向けにYouTube・インスタ・LINEを一式作って」
- 「この台本をチェックして」
- 「管理者向けに、処遇改善加算のnote記事を書いて」

成果物は `outputs/YYYY-MM-DD_テーマ名/` に保存されます。
