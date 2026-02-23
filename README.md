# OW Scrim Public Repository

[日本語](#日本語) | [English](#english)

---

## 日本語

このリポジトリは **OW Scrim** のコミュニティ向け公開リポジトリです。

### このリポジトリの目的

- **バグ報告**: サービスで発見したバグを報告
- **機能リクエスト**: 新機能や改善の提案
- **翻訳貢献**: 多言語対応への協力
- **質問・議論**: サービスに関する質問やディスカッション

### Issue を作成する

[Issues](../../issues) から新しい Issue を作成できます。

- 🐛 [バグ報告](../../issues/new?template=bug_report.md)
- ✨ [機能リクエスト](../../issues/new?template=feature_request.md)
- 🌐 [翻訳リクエスト](../../issues/new?template=translation_request.md)

### 翻訳に貢献する

翻訳ファイルは `locales/` ディレクトリにあります。

```
locales/
├── ja/          # 日本語
│   ├── common.json       # 共通（エラー、ラベル、ナビ等）
│   ├── calendar.json     # カレンダー
│   ├── lft.json          # LFT（チーム探し）
│   ├── pages.json        # ページ固有テキスト
│   ├── scrim.json        # スクリム
│   ├── team.json         # チーム管理
│   └── tournament.json   # 大会
├── en/          # English
│   └── ...              # (same structure)
├── ko/          # 한국어
│   └── ...              # (same structure)
└── zh/          # 中文（简体）
    └── ...              # (same structure)
```

詳細は [CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。

---

## English

This is the public repository for **OW Scrim** community.

### Purpose of This Repository

- **Bug Reports**: Report bugs found in the service
- **Feature Requests**: Suggest new features or improvements
- **Translation Contributions**: Help with localization
- **Questions & Discussions**: Ask questions or discuss about the service

### Creating Issues

You can create new issues from [Issues](../../issues).

- 🐛 [Bug Report](../../issues/new?template=bug_report.md)
- ✨ [Feature Request](../../issues/new?template=feature_request.md)
- 🌐 [Translation Request](../../issues/new?template=translation_request.md)

### Contributing Translations

Translation files are located in the `locales/` directory.

```
locales/
├── ja/          # Japanese
│   ├── common.json       # Common (errors, labels, nav, etc.)
│   ├── calendar.json     # Calendar
│   ├── lft.json          # LFT (Looking for Team)
│   ├── pages.json        # Page-specific text
│   ├── scrim.json        # Scrim
│   ├── team.json         # Team management
│   └── tournament.json   # Tournament
├── en/          # English
│   └── ...              # (same structure)
├── ko/          # Korean
│   └── ...              # (same structure)
└── zh/          # Chinese (Simplified)
    └── ...              # (same structure)
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.
