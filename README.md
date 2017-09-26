# www.code4.nagoya

このリポジトリは https://www.code4.nagoya のホスティングのためのリポジトリです。

GitHub Pagesを使用し、カスタムドメインとして「www.code4.nagoya」を設定しています。

## HTTPS対応

現在はさくらインターネットのVPS上のnginxでHTTPSを処理してリバースプロキシでGitHub Pagesを読み込んでいます。

よって、ブラウザはhttps://www.code4.nagoyaにアクセスすると、さくらのVPSと通信しています。さくらのVPSはGitHub Pagesと通信しコンテンツを読み込み返します。


