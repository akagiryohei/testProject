---
description: 模試・過去問の結果を記録する
argument-hint: <日付 模試名 科目別得点など>
---
次の模試・過去問結果を記録してください。

結果: $ARGUMENTS

1. `templates/mock-exam.md` をもとに `mock-exams/YYYY-MM-DD_<模試名>.md` を作成する。不明な科目別得点は空欄にし、ユーザーに確認する。
2. `progress/dashboard.md` の「直近の模試」に追記する。
3. 前回の模試があれば比較し、基準点割れ・伸びた科目を報告する。
