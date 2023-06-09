# 職歴概要

## 担当プロジェクト
- ID認証基盤API（画面あり・なし）

## プロジェクト概要
- グループ内複数サービスにて各サービスごとに会員管理を行っておりアカウントを別で作る必要があるためグループ内共通IDに対応させ一元化することが目的
- APIの機能としては、ログイン、ログアウト、新規登録、会員情報参照、会員情報更新、パスワードリセット、退会など

## 開発規模
- 3~5名

## 担当業務
- API仕様書作成
- 詳細設計書の作成
- 実装(PHP)
- テスト仕様書作成・テスト実行

## 開発環境
- PHP
- SAP CDC
- PostgresSQL
- Docker
- Git
- backlog
- nginx

## 取り組んだ課題
- レスポンスタイムの改善。横展開するシステムで過去のプロジェクトを参考にして開発を進めていくため、不必要な動作を含んでいる可能性があった。

## 工夫
- 開発したAPI内でSAP CDCとの連携する際のデータ登録、参照の回数をできるだけ減らすようにして改善を行った。

## 取り組んだ成果
- 結果としては動作5秒以上になっていたレスポンスタイムを2秒台にまで最適化を行い、機能は削らず改善を行うことができた。