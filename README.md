# My ToDoList

タスク管理とリマインダー機能を備えたWebアプリケーションです。

日々の予定やタスクを整理し、忘れずに管理できることを目的として開発しました。

細部まで拘りました、ぜひ使ってみてください！

## アプリ

**[My ToDoListを開く](https://todolist-ckm.pages.dev)**

ブラウザからアクセスして利用できます。

※ 初回利用時はアカウント登録が必要です。

！通知を受け取るには、ブラウザで開いてからホーム画面に追加->サインインして通知を有効にするを押してください。
アプリと同じように利用することができます。

## 主な機能

### 1. ユーザー認証
- メールアドレスとパスワードによる新規登録
- ログイン・ログアウト

### 2. タスク管理
- カテゴリー（タイトル）の作成・削除
- タスクの追加・削除
- タスクの完了状態の管理
- タスクの期限・時刻の設定

### 3. リマインダー・通知
- タスクの予定時刻にプッシュ通知を送信
- 対応端末での通知許可・端末登録
- iPhoneのホーム画面に追加したWebアプリでの通知に対応

### 4. データ保存・同期
- Cloud Firestoreを使用したデータ保存
- 同じアカウントでログインした端末間でのデータ共有

## 使用技術

| 分野 | 使用技術 |
|---|---|
| フロントエンド | HTML / CSS / JavaScript |
| ユーザー認証 | Firebase Authentication |
| データベース | Cloud Firestore |
| プッシュ通知 | Firebase Cloud Messaging |
| 通知の定期処理 | Cloudflare Workers |
| ホスティング | Cloudflare Pages |
| バージョン管理 | Git / GitHub |

## スクリーンショット

ここにアプリの画面画像を掲載する予定です。

- ログイン画面
- タイトル一覧画面
- タスク管理画面
- 通知画面

## 開発で工夫した点

**直感的に操作できるUI**

タスクの追加や管理を簡単に行えるよう、画面構成やボタンの配置を考えました。

**複数端末での利用**

Firebaseを利用し、ログインしたアカウントに紐づくタスクデータを保存する仕組みを実装しました。

**プッシュ通知機能**

アプリを閉じている状態でもリマインダーを受け取れるよう、Firebase Cloud MessagingとCloudflare Workersを組み合わせました。

## ソースコードについて

本リポジトリはアプリケーションの紹介を目的としています。
  
  
  Hey! Wanna try my new ToDoList app? 💗

Click here to check it out! 👉🏻 https://todolist-ckm.pages.dev/

If you wanna try the notification feature, make sure to add the app to your Home Screen and sign up first! 🔔✨
