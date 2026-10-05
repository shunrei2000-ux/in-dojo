# 韻道場 iPhoneアプリ

リポジトリ直下の `index.html` を Capacitor で包んだ iOS アプリです。文字起こしは iPhone 本体の音声認識を使います。

## Mac での準備（初回だけ）

```
brew install node cocoapods
git clone https://github.com/shunrei2000-ux/in-dojo.git
cd in-dojo/app
npm install
npm run sync
npm run open
```

## 画面を更新したとき

```
cd in-dojo && git pull && cd app && npm run sync
```

Bundle ID は `com.shunrei2000.indojo`（`capacitor.config.json` と Xcode の Signing で変更可）。
