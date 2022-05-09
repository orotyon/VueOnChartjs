# VueとChart.jsを使ったプログラム
## viteプロジェクトの作成 
[vite公式サイト](https://ja.vitejs.dev/guide/)

プロジェクトを作成
```sh
npm init vite@latest -y VueOnChartjs -- --template vue
```

npm installして動作確認
```sh
cd VueOnChartjs
npm install
npm run dev
```

## Chartjsの設定
vue-chartjsをインストール
```sh
npm i vue-chartjs chart.js
```

## firebase のセットアップ
### ツールのインストール
```sh
npm install firebase
firebase init
# Hostingだけ使う
# 事前にgitリポジトリを作っておく
# gitの設定で作っておいたリポジトリを指定する
# publicの設定はviteのコンパイル先のdistにしておく？

# 以下はYesにして[npm run build]を入れる？
? Set up the workflow to run a build script before every deploy? Yes
```

### gitの設定
```sh
git init
git add *
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/orotyon/VueOnChartjs.git
git push -u origin main

