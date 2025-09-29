# Reading Notes App Constitution

## Core Principles

### I. User-Centric Design
入力の手間を最小限に抑えることを最優先とする。自動入力補完、音声入力、OCRなどの技術を活用し、ユーザー体験を向上させる。

### II. Accessibility
アプリはすべてのユーザーにとって利用可能であるべき。視覚障害者向けのスクリーンリーダー対応、キーボード操作の最適化、多言語対応を含む。

### III. Test-Driven Development (TDD)
テスト駆動開発を必須とする。すべての機能はテストが記述され、ユーザーによって承認された後に実装されるべき。

### IV. Integration with External Services
外部サービス（例: 書籍データベース、クラウドストレージ）との統合を重視し、シームレスなデータ同期を実現する。

### V. Data Privacy
ユーザーのデータプライバシーを最優先とする。データは暗号化され、ユーザーの明示的な同意なしに共有されない。

## Additional Constraints

### Technology Stack
- フロントエンド: React
- バックエンド: Node.js
- データベース: PostgreSQL
- デプロイ: AWS

### Performance Standards
- 初回ロード時間: 3秒以内
- ユーザー操作の応答時間: 100ms以下

## Development Workflow

### Code Review Process
- すべてのプルリクエストは少なくとも2人のレビューを必要とする。
- コードは自動テストをパスし、静的解析ツールによるチェックをクリアする必要がある。

### Quality Gates
- カバレッジ: 90%以上
- 重大なバグゼロを目指す。

## Governance

この憲法は他のすべてのプラクティスに優先する。修正には文書化、承認、移行計画が必要。

- すべてのプルリクエスト/レビューはこの憲法への準拠を確認する必要がある。
- 複雑さは正当化されなければならない。
- ランタイム開発ガイダンスには[GUIDANCE_FILE]を使用する。

**Version**: 1.0.0 | **Ratified**: 2025-09-29 | **Last Amended**: 2025-09-29