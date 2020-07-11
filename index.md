## 文屋裕一のGitHub Pagesです。

ご参照いただきありがとうございます。  
  
大学ではLinuxサーバ構築し、JavaとPostgreSQLで飲食店検索やチャットなどを作成しました。  

現職ではWindowsでの自社業務向け開発を行っております。   
- VB.NET+SQLServer(100テーブルほど)による印字データ作成アプリ
- 運用向けメール送信アプリ
- 固定長テキスト->エクセル変換アプリ
- 仕様書->ソースコード自動生成アプリ

拙いですが、自習の中で出来たものを下記にまとめました。

### Node.js + Socket.IO + Redis(NoSQL DB)によるリアルタイムイラストチャット

Node.js、Socket.IO、Redisを用いてリアルタイムのイラストチャットアプリを作成しました。  
2画面以上開き、発言すると同時に全画面に反映されます。  
タッチデバイスでの操作に対応しています。  
描画ログはRedis上で記憶され、再入室の際に再生されます。
言語学習SNSのHelloTalkで公開し、英語でフィードバックを受けました。  

heroku上にデプロイした実際に操作可能なものは[こちら](https://mgn-echat.herokuapp.com/)。  
ソースは[こちら](https://github.com/mgningithub/eChat)。  
制作中の備忘録は[こちら](https://github.com/mgningithub/eChat/blob/master/memo.md)  
Redis導入の備忘録は[こちら](https://github.com/mgningithub/test-redis/blob/master/memo.md)

### HTML5テンプレートのVue.js使用へカスタマイズ

既存のHTML5テンプレートに対して  
画像表示、コメントの表示部分をVue.jsを使用するようHtml, Javascriptを改変しました。

実際の表示は[こちら](https://mgningithub.github.io/photos/)。  
ソースは[こちら](https://github.com/mgningithub/photos)。 

HTML5テンプレートのライセンス使用はCC BY 3.0に準拠し、
写真は私が撮ったものとなります。

### HTML5 + JavaScriptによるマインスイーパ

HTML5のcanvas要素とJavaScriptでマインスイーパを実装しました。  
タッチデバイスでの操作にも対応しています。  
言語学習SNSのHelloTalkで公開し、英語でフィードバック、バグ報告を受けました。

実際に遊べるものは[こちら](https://mgningithub.github.io/js-mineSweeper/)。  
ソースは[こちら](https://github.com/mgningithub/js-mineSweeper)。 

### PHP + MySQLによる一言掲示板

[よくわかるPHPの教科書](https://www.amazon.co.jp/dp/4839964688/)を参考に  
ログイン、投稿、返信機能のある掲示板を作成しました。  

実際に動作するものは[こちら](http://mgoon.php.xdomain.jp/twitter-like/login.php)。  
新規登録するか、メールアドレス"cat@test",パスワード"test"を使用してログインできます。  

### 自習に使用した書籍

- [リーダブルコード ―より良いコードを書くためのシンプルで実践的なテクニック ](https://www.amazon.co.jp/dp/4873115655/)
- [Webを支える技術 -HTTP、URI、HTML、そしてREST](https://www.amazon.co.jp/dp/4774142042/)
- [これからWebをはじめる人のHTML&CSS、JavaScriptのきほんのきほん](https://www.amazon.co.jp/dp/4839959714/)
- [Webプログラミングが面白いほどわかる本](https://www.amazon.co.jp/dp/4046023023/)
- [よくわかるPHPの教科書](https://www.amazon.co.jp/dp/4839964688/)

### 英語学習について
HelloTalkという言語学習SNSで英語で日記を書いています。  
アカウントは下記になります。  
@ho_yuichi_89710
