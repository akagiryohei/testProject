---
description: 学習内容を記録する
argument-hint: <科目 内容 時間 演習結果など>
---
次の学習報告を CLAUDE.md の「記録ルール」に従って記録してください。

報告: $ARGUMENTS

1. 科目を科目IDに対応付け、今日（JST）の日付で `logs/YYYY/YYYY-MM.md` に追記する。
2. 単元完了・演習結果があれば `progress/subjects/<科目ID>.md` を更新する。
3. 間違えた論点があれば `weak-points/weak-points.md` に追記する。
4. `progress/dashboard.md` の数値を更新する。
5. 更新したファイルと内容を簡潔に報告する。時間や科目が読み取れなければ確認する。
