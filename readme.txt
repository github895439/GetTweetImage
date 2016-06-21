1　ChromeでTwitter公式の自分のメディアページを開く。
　バックアップしたい分だけ下にスクロールして追加表示させる。
2　ページ内でコンテキストメニュー「検証」を選ぶ。
3　下部に開いたデベロッパーツールの画面で、一番上ら辺のHTMLタグの行を選択する。
　タブはElements。
4　コンテキストメニュー「Copy outerHTML」を選ぶ。
5　サクラエディタにペーストする。
6　サクラエディタのマクロget_image_url.macを実行する。
7　下部の空行を削除する。
8　ファイルに保存する。
9　Cygwinのwgetを、保存したファイルを入力として実行する。
　　例　wget -i <保存したファイル> -o log.txt

※サクラエディタ
サクラエディタ   Ver. 2.2.0.1

      Share Ver: 166
      Compile Info: V1500 WR WIN500/I501/C000/N500
      Last Modified: 2015/7/19 11:33:53

※wget
$ wget -V
GNU Wget 1.17.1 built on cygwin.

※Cygwin
$ uname -a
CYGWIN_NT-6.1 * 2.5.1(0.297/5/3) 2016-04-21 22:14 x86_64 Cygwin
