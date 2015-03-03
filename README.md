#SublimeText3設定
###Packagecontrlについて
Packagecontrolのインストールが必要です。

(1)ショートカット「Ctrl + Shift + @」でコマンドライン表示。  
(2)コマンドラインに以下を入力してEnter。

***

`import urllib.request,os,hashlib; h = 'eb2297e1a458f27d836c04bb0cbaf282' + 'd0e7a3098092775ccb37ca9d6b2e4b7d'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)`

***

###設定ファイルについて
Application suupport/Sublime Text 3/Packages/Userフィルダの中に配置してください。

###パッケージについて
SublimeText3起動するとパッケージのインストールが自動で開始されます。

###フォントについて
フォントはMigMix 1M Regularを使用しています。  
インストールしていない場合は設定ファイルを編集して下さい。

###テーマについて
itg.flatテーマを使用しています。
お気に入りのテーマを自由に設定してください。

###基本型の展開について
basehtml5 + Tabでhtml5基本型を展開  
basecss + Tabでリセットcssを展開

###キーバインドについて
Ctrl + Enter で`<br>`  
Shift + Enter で`<br/>`




