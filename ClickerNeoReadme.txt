Clicker	V1.03


マウス動作およびキーボード入力をシミュレートするツール。

[メニュー]→[ファイル]→[開く]でテストケースファイルのロードし、
[開始]でテストケースを実行できる。

また、[テストケースフォルダ]を指定して、[テストケース全て実行]を押下すると、
フォルダ内のテストケースファイル（*.tst）を順次読込み実行する。



キーボード入力のエスケープシーケンス一覧：

	\a	Alt
	\c	Ctrl
	\d	Delete
	\e	Esc
	\f1~c	F1～F12
	\k	カウンター（0123...)
	\n	Enter
	\o	置き換え文字列
	\s	Shift
	\t	Tab
	\\	\
	\{	同時押し開始}で同時押し終了


例１：
	Ctrl+Alt+Delを押したい場合は \{\c\a\d} とする。

例２：
	fileName\k.txt
	fileName\k.txt
	fileName\k.txt
	とすると
	fileName0.txt
	fileName1.txt
	fileName2.txt
	となる。
