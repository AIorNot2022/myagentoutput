# myagentoutput

AIエージェント（Claude, OpenAI など）で作成した有用なアウトプットを整理・共有するリポジトリです。

A repository for organizing and sharing useful outputs created with AI agents (Claude, OpenAI, etc.).

---

## ディレクトリ構成 / Directory Structure

```
myagentoutput/
├── README.md
├── documents/                # ドキュメント・レポート / Documents & Reports
│   ├── reports/              #   調査レポート・分析結果 / Research & analysis reports
│   ├── notes/                #   メモ・議事録 / Notes & meeting minutes
│   └── summaries/            #   要約・まとめ / Summaries
│
└── prompts/                  # プロンプト・テンプレート / Prompts & Templates
    ├── claude/               #   Claude 用 / For Claude
    ├── openai/               #   OpenAI 用 / For OpenAI
    └── shared/               #   汎用（ツール非依存） / General-purpose
```

## 使い方 / How to Use

### ドキュメントの追加 / Adding Documents

各サブフォルダにファイルを配置してください。ファイル名は以下の規則を推奨します。

Place files in the appropriate subfolder. The following naming convention is recommended:

```
YYYY-MM-DD_short-description.md
```

例 / Example: `2026-02-14_market-analysis.md`

### プロンプトの追加 / Adding Prompts

Markdown 形式で保存し、以下の情報をファイル先頭に含めてください。

Save in Markdown format and include the following metadata at the top of the file:

```markdown
# プロンプト名 / Prompt Title

- **用途 / Purpose**: 何に使うか
- **対象ツール / Target Tool**: Claude / OpenAI / 汎用
- **作成日 / Created**: YYYY-MM-DD

---

（プロンプト本文 / Prompt body）
```

## ライセンス / License

個人利用。必要に応じてライセンスを追加してください。

For personal use. Add a license as needed.
