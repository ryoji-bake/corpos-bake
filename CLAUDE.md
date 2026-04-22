# CorpOS - Claude Code プロジェクト設定

## プロジェクト概要
- サービス名：CorpOS（コーポレート管理プラットフォーム）
- 運営者：Bakeru
- GitHub Pages URL：https://ryoji-bake.github.io/corpos-bake
- リポジトリ：https://github.com/ryoji-bake/corpos-bake

## 技術構成
- フロントエンド：HTML / CSS / JavaScript（フレームワークなし）
- バックエンド：Supabase（認証・DB・ストレージ）
- デプロイ：GitHub Pages（mainブランチへpushで自動反映）

## ファイル構成
- index.html：ログイン画面
- contracts.html：契約・法務管理（メイン機能）

## デザインルール
- ダークテーマ（背景色 #0a0b0f ベース）
- フォント：Syne（見出し）/ Noto Sans JP（本文）
- アクセントカラー：#4f6ef7（青）/ #7c3aed（紫）
- 既存のCSSクラスを流用すること（新規クラスは最小限に）

## 開発ルール
- 作業後は必ず git add → git commit → git push すること
- コミットメッセージは日本語でもOK
- pushは必ず main ブランチへ
- 機能追加時はコミットメッセージを "feat: " で始める
- バグ修正時は "fix: " で始める
- UI改善時は "style: " で始める

## 担当者メモ
- オーナーはエンジニアではないため、技術的な確認は最小限にすること
- 判断が必要な場合のみ質問する
- 基本的に要件通りに実装して完了報告をする
