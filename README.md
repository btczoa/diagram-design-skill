# diagram-design-skill

`diagram-design` スキルを別 PC やチーム環境に `npx skills add` で 1 コマンド導入するための配布用 Git リポジトリです。

---

## 概要

Standalone HTML + Inline SVG によるプロフェッショナルな図解・アーキテクチャ図（45 種のビジュアルタイプ）を生成するスキルです。

---

## インストール方法

### 1. GitHub リポジトリから直接インストール
```bash
npx skills add <GITHUB_USER>/<REPO_NAME>
```

または明示的にスキル名を指定する場合：
```bash
npx skills add <GITHUB_USER>/<REPO_NAME> --skill diagram-design
```

### 2. ローカル環境からの検証・追加
```bash
npx skills add ./path/to/diagram-design-skill
```

---

## インストール後の確認

```bash
# スキル一覧の確認
npx skills list

# スキルの実行確認
npx skills run diagram-design
```

---

## ディレクトリ構成

```text
diagram-design-skill/
├── README.md
├── skill.json                  # スキル定義マニフェスト
├── SKILL.md                    # ルート定義
└── skills/
    └── diagram-design/         # diagram-design スキル本体
        ├── SKILL.md            # スキル仕様・プロンプト定義
        ├── assets/             # テンプレート・アイコン・HTMLアセット
        ├── references/         # ガイドライン・設計仕様
        └── scripts/            # 検証・チェック用スクリプト
```
