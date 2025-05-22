# 💬 Flutter Chat App

FlutterとFirebaseを使用して開発した、リアルタイムチャットアプリです。  
iOSおよびAndroidの両プラットフォームに対応しています。

## 🧩 主な機能

- 名前と会社名を入力してチャットルームに入室
- LINEのようなUIデザイン（自分のメッセージが一目でわかる）
- メッセージ送信時に日時を自動で表示
- 画像やファイルのアップロード機能
- Firebaseと連携した以下の構成：
  - Firebase Authentication によるユーザー識別
  - Cloud Firestore によるチャット内容の保存
  - Firebase Storage によるファイル保存

## 🔧 使用技術

- Flutter（Dart）
- Firebase（Firestore, Storage, Authentication）
- Provider（状態管理）
- その他：intl, file_picker などのFlutterパッケージ
