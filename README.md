# shuiguopeidui
  水果配对
游戏描述：
从12張図片找２个相同的水果図片

![](/水果图片.png) 
1.	時間因数:限制游戏时长（如60秒），剩余时间是最后得分的奖励因数；
2.	空间因素：用户界面上有16张卡片，排成4×4的方阵，显示背面图案（安卓机器人）；16张卡片的正面图案为8种水果，可以两两配对；
3.	游戏操作——翻牌：玩家先翻开一张卡片，再翻开另一张卡片，如果两张卡片的正面图案相同，则两张卡片保持翻开状态；如果两张卡片的正面图案不同，两张卡片将闪现片刻，然后反转回去，显示背面图案。
4.	计分规则：每翻开一对卡片得10分；如果在规定时间内翻开所有卡片，满分为80分；剩余游戏时间×10作为奖励得分，与翻牌得分一同计入总分；如果在规定时间内没有翻开所有卡片，则不计分；
5.	历史记录：首次游戏得分被保存在手机中，在每次游戏完成时，将本次得分与历史记录进行比较，并保存高的得分；玩家可以清除游戏成绩的历史记录；
6.	退出游戏：玩家在完成一轮游戏后，可以选择退出游戏。

	界面設計：
画面分两个部分：在屏幕顶部，使用了水平布局组件，内部放置了显示分数的标签和显示游戏剩余时间的数字滑动条；在屏幕的中央，使用了4X4表格布局组件，共16个单元格，每个单元格中放置一个按钮，来实现点击翻牌功能。
![](/效果图.jpg)![](/3.jpg)
   
上传游戏中将要用到的资源文件

![](/1.png)![](/2.png)

程序文说明
像下面的屏幕拷贝一样，这个应用软件满足了项目的最低规格。包含了2个全局变量（全球variables）, 4个列表数据（映射data）, 2个函数（procedures or  functions）,还有2个if / else构造（structure）。
![](/4.png)![](/図1.png)   

下载链接.
这个应用程序是WordPress REST API使用，所有的功能测试，WordPress上REST接口的必要。可自由使用这边的测试网站。应用软件下载，MIT AI 2 Companion应用程序或扫描仪应用在使用QR码扫描这个下载，或点击以下链接。https://drive.google.com/file/d/0B_lKiLz22m3xMVJDdEdaRXE0RDQ/view?usp=sharing
二维码下载链接：

![](/2wei.png)
 
Appendix
WP REST APIはWordPressのプラグイン、 将来は WordPressコアに組み入れ、WordPressを ブログプラットフォーム/CMS から、本格的なアプリケーション・フレームワークへ変身するために一歩である。
WP REST API は OAuth 1.0a とBasic Auth 認証方法サポートする。 しかしApp InventorはOAuth 1.0a対応できないため, Basic Authを利用した。Basic Auth はbase64 encodeを利用するが、それもApp Inventorだけでは計算できない, だからこのアプリは、グローバル変数（global variable）に 予めbase64 encode計算した値を入れる。



