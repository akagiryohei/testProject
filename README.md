# 社労士試験 学習進捗管理

Claude Code で社会保険労務士試験の学習進捗を管理するリポジトリです。運用ルールは [CLAUDE.md](CLAUDE.md) を参照。

## 使い方
```
/log 国年 遺族基礎年金 テキスト読了、過去問20問 15問正解 90分
/status
/weekly
/mock 2026-11-15 TAC全国模試 選択式28点 択一式45点
/review
```
自然文で「今日は健保を1時間、傷病手当金まで」と伝えても記録されます。

## 構成
```
.
├── CLAUDE.md                 # Claude Code 用の運用ルール
├── .claude/commands/         # スラッシュコマンド
├── progress/
│   ├── dashboard.md          # 全体サマリ
│   └── subjects/             # 科目別進捗
├── logs/YYYY/YYYY-MM.md      # 日次学習ログ
├── mock-exams/               # 模試・過去問結果
├── weak-points/              # 弱点リスト
├── notes/                    # 科目別まとめノート
└── templates/                # テンプレート
```
