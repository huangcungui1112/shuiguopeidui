# shuiguopeidui
 フルーツペアリング
ゲームの説明：
１６枚写真から、同じな写真をペアリングすることです.記憶力を強くなるためのプログラミグ

![](/水果图片.png) 
1.	時間要素：ゲームの継続時間を制限する（60秒など）、勝ったら、残りの時間は最終得点に加算する；
2.	空間的要因：ユーザーインタフェースには16個のカードがあり、4×4のマトリックスに配置され、パターンの背面（Androidロボット）を表示し、16枚のカードの前面は8種類の果物であり、互いに対になることができます。
3.	ゲーム操作 - フロップ：最初にカードを開き、別のカードを開きます。2枚のカードが同じ前面パターンを持っている場合、2枚のカードは開いたままです; 2枚のカードのフロントパターンが異なる場合、 2枚のカードはしばらくの間点滅し、後ろに戻ってパターンを表示します。
4.	得点計算：開かれた各カードの対10点、指定された時間内にすべてのカードが開かれた場合、得点は80点、残りのゲーム時間はボーナス10点、フロップの得点は合計得点に含まれます。 指定された時間内にカードが開かれていない場合、得点は得られません。
5.	履歴レコード：最初のゲームスコアが携帯電話に保存されます。各ゲームが完了すると、現在のスコアが履歴レコードと比較され、高いスコアが保存され、プレーヤーはゲーム結果の履歴レコードをクリアできます。
6.	ゲームを終了する：ゲームのラウンドを完了した後、プレーヤーはゲームからオプトアウトすることができます。

	インタフェース設計：
画面の上部には、水平方向のレイアウト構成要素が使用され、スコアを表示するためのラベルとゲームの残りの時間を表示するための数字スライダが内部に配置され、画面の中央には4×4の表レイアウト構成要素が使用され、 クリックフロップ機能を実装するために各セルにボタンを配置します。
![](/效果图.jpg)![](/3.jpg)
   
ゲームで使用するリソースファイルをアップロードする

![](/1.png)![](/2.png)

プログラムの説明
以下の画面コピーと同様に、このアプリケーションはプロジェクトの最小仕様を満たしています。 2つのグローバル変数（グローバル変数）、4つのリストデータ（マップデータ）、2つのプロシージャー（関数）、2つのif / else構造体が含まれています。
![](/4.png)![](/図1.png)   

下载链接.
这个应用程序是WordPress REST API使用，所有的功能测试，WordPress上REST接口的必要。可自由使用这边的测试网站。应用软件下载，MIT AI 2 Companion应用程序或扫描仪应用在使用QR码扫描这个下载，或点击以下链接。https://drive.google.com/file/d/0B_lKiLz22m3xMVJDdEdaRXE0RDQ/view?usp=sharing

二维码下载链接：

![](/wwww.PNG)
 
Appendix
WP REST APIはWordPressのプラグイン、 将来は WordPressコアに組み入れ、WordPressを ブログプラットフォーム/CMS から、本格的なアプリケーション・フレームワークへ変身するために一歩である。
WP REST API は OAuth 1.0a とBasic Auth 認証方法サポートする。 しかしApp InventorはOAuth 1.0a対応できないため, Basic Authを利用した。Basic Auth はbase64 encodeを利用するが、それもApp Inventorだけでは計算できない, だからこのアプリは、グローバル変数（global variable）に 予めbase64 encode計算した値を入れる。



