# Contributing Guide / 貢献ガイド

[日本語](#日本語) | [English](#english)

---

## 日本語

### バグ報告

1. [Issues](../../issues) で既存のバグ報告がないか確認
2. 新しい Issue を作成（テンプレート: Bug Report）
3. 再現手順、期待する動作、実際の動作を記載

### 機能リクエスト

1. [Issues](../../issues) で既存のリクエストがないか確認
2. 新しい Issue を作成（テンプレート: Feature Request）
3. 機能の詳細と理由を記載

### 翻訳貢献

#### 既存言語の修正

1. このリポジトリをフォーク
2. `locales/{言語コード}/` 内の該当ファイルを編集
3. Pull Request を作成

#### 新しい言語の追加

1. Issue を作成して追加したい言語を提案
2. 承認後、`locales/{言語コード}/` ディレクトリを作成
3. `locales/en/` 内のファイルをコピーして翻訳
4. Pull Request を作成

#### 翻訳ルール

- **キーは変更しない**: `"error.generic"` などのキーはそのまま
- **プレースホルダーを保持**: `{{action}}` などはそのまま残す
- **自然な表現**: 直訳ではなく、その言語で自然な表現を使用
- **一貫性**: 同じ用語は統一して翻訳

**例:**
```json
{
  "error": {
    "generic": "エラーが発生しました",
    "withDetail": "{{action}}に失敗しました: {{detail}}"
  }
}
```

---

## English

### Bug Reports

1. Check [Issues](../../issues) for existing bug reports
2. Create a new Issue (template: Bug Report)
3. Include reproduction steps, expected behavior, and actual behavior

### Feature Requests

1. Check [Issues](../../issues) for existing requests
2. Create a new Issue (template: Feature Request)
3. Describe the feature and why it would be useful

### Translation Contributions

#### Fixing Existing Translations

1. Fork this repository
2. Edit the relevant files in `locales/{language_code}/`
3. Create a Pull Request

#### Adding New Languages

1. Create an Issue to propose the new language
2. After approval, create `locales/{language_code}/` directory
3. Copy files from `locales/en/` and translate
4. Create a Pull Request

#### Translation Rules

- **Keep keys unchanged**: Keys like `"error.generic"` should not be modified
- **Preserve placeholders**: Keep `{{action}}` and similar placeholders as-is
- **Natural expressions**: Use natural expressions in the target language, not literal translations
- **Consistency**: Use consistent terminology throughout

**Example:**
```json
{
  "error": {
    "generic": "An error occurred",
    "withDetail": "Failed to {{action}}: {{detail}}"
  }
}
```

---

## Code of Conduct

- Be respectful and constructive
- Focus on the issue, not the person
- Help others when you can
