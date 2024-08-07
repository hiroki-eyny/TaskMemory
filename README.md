# TaskMemory

アラームアプリに 1日の目標を入力する機能を導入したアプリです。1日に何か目標を決めてその目標を達成できるようにしたい人に向けたアプリであり、ユーザが目標を達成できるようにすることを目的としています
 
## 使用方法動画
 
アプリの使用方法動画を載せさせていただきます(リポジトリ内にあ「るシステム紹介.mp4」と同じ内容です)

https://www.youtube.com/watch?v=c47kKjQxDTM
 
## 特徴
 
他のアラームアプリと違い、目標を入力できます

また、その目標に対して達成できたことを入力しフレンドと競ったり(ランキング形式)、達成できた数値がグラフになって視覚的にわかります
 
## ハードウェア構成と利用したOS
 
ハードウェア構成：Google Pixel 8 Pro

利用したOS　　：Android 14 (API Level 34)
 
## 使用方法
 
TaskMemoryの実行方法を説明します。

```
(cmdにて)
git clone https://github.com/hiroki-eyny/TaskMemory.git
cd TaskMemoryProject
code .
(Vscodeにて)
Ctrl-shiflt-P
Flutter: Launch Emulatorと検索
Pixel 8 Pro API 34を選択
(cmdにて)
flutter clean
flutter pub get
flutter run
```
## 注意事項
 
android studioにてPixel 8 Pro API 34エミュレータをダウンロードしてください

## 作成者
 
* 作成者:大学の講義にて自分含め6人で作成。私はサインアップ、ログイン、フレンド機能を担当
* 所属:芝浦工業大学
* E-mail:al22082@shibaura-it.ac.jp
