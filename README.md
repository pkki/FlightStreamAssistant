# FlightStreamAssistant(マイクロソフトフライトシュミレーター2020専用配信支援ソフト)
<img width="1382" height="852" alt="Image" src="https://github.com/user-attachments/assets/3df065b1-2b1b-4da8-b0af-797ddcae0c55" />
<p>
  <img src="https://img.shields.io/badge/Javascript-276DC3.svg?logo=javascript&style=flat">
  <img src="https://img.shields.io/badge/-Python-F9DC3E.svg?logo=python&style=flat">
  <img src="https://img.shields.io/badge/-CSS3-1572B6.svg?logo=css3&style=flat">
  <img src="https://img.shields.io/badge/-HTML5-333.svg?logo=html5&style=flat">
  </p>
MicrosoftFlightSimulator2020(マイクロソフトフライトシュミレーター2020)(MSFS2020)に対応している配信(主にYoutube)支援ソフトです。

# 目玉機能
## 配信オーバーレイ＆着陸リザルト表示

<img width="1358" height="495" alt="Image" src="https://github.com/user-attachments/assets/3045a5f3-dd3b-43b0-858c-112c159c22db" />
このように、Volantaの様にオーバーレイを表示することが可能で、Volantaと違い自由にカスタマイズできるところが特徴です。
また、着陸リザルト表示機能は地面に設置した際にV/S・G・フレアの評価をカードで効果音付きで表示することができます。※効果音は変更可

## 棒読みちゃん＆Youtubeライブ配信コメント連携

棒読みちゃんを導入する必要がありますが、Youtubeのコメントを読み上げてくれます。

## 視聴者用マップ

<img width="1920" height="911" alt="Image" src="https://github.com/user-attachments/assets/b7a4b7c3-aef9-46d9-a40e-3de1ac52bbb5" />
画像の様に、視聴者に配信中のフライトやその履歴を表示したりMSFSの機体を自動取得し、表示する機能も備えております。
また、ngrokで無料のAPIを取得するだけでワンボタンで公開する機能も備えております。

# 機能一覧

- 棒読みちゃんと連携可能で、YoutubeLive配信コメント読み上げ
- AquesTalk10＆AquesTalk1対応(開発ライセンスキーまたは使用ライセンスがなければ、な・ま行が「ぬ」に置き換わります)
- Simconnect対応
- LLMとも連携可能でAIが自動で返信(プロンプト編集可)
- LLMで現在の状況のテロップを生成可能(プロンプト編集可)
- Simbrief連携
- 空港情報をMETARと滑走路情報(AirportDB Token)から視覚的に分かりやすく表示する
- 配信オーバーレイ(カスタマイズ自由自在！)
- 着陸リザルト表示(設置した瞬間、垂直速度・G・フレアの評価をカード表示します。また、効果音も設定いただけます)
- Go-Around警告(ファイナルアプローチに入りますとMetarを10秒おきに取得し、着陸するのが困難な状態となると警告がでます)
- 視聴者マップ(Simbrief情報、オーバーレイ情報、MSFSの所有機体一覧、フライト履歴をご覧いただけます)
- 保有機体一覧取得(視聴者マップでご覧いただけます)
- ワンボタンで外部公開(ngrok)(APIを取得＆入力し「ワンボタンで公開する」をクリックすると全世界に公開できます)
- 自動アップデート

# もしバグなどございましたら[Issues](https://github.com/pkki/FlightStreamAssistant/issues)の方でよろしくお願いします！
