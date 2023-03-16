# javascript
Created with CodeSandbox

# ①明確な定義はないが以下にあたりを指すことが常
・ Reavt vue angular Riot等の仮想DOMを用いるライブラリ/フレームワークを使用<br>
・ npm/yarm等のパッケージマネージャを使用<br>
・ 主にES2015(ES6以降)の記法を使用<br>
・ webpack等のモジュールバンドラーを使用<br>
・ Babel等のトランスパイラを使用<br>

# ②そもそもDOMって？
・ Document Object Modelの略。ドムと読む<br>
・ HTMLなどを解釈し木構造で表現したもの<br>

### これまでのDOMを直接操作していた
・ 素のjavascriptやjquery等<br>
※デメリット：レンダリングコスト高、コードの複雑化<br>

## 仮想DOMとは
### javascriptのオブジェクトで仮想的に作られたDOM
・ いきなりDOMを操作せず、JS上で仮想DOMを操作し差分を出してからDOMに反映<br>

# ③npm/yarm等のパッケージマネージャを使用
### かつてのjavascriptは1つのJSファイルに全ての処理を記述していた
・　処理が複雑になるにつれてコードがカオス化<br>
・　コードの再利用ができない<br>

### ちょっと改善されたjavascript、他のJSファイルを読み込んで使っていた
・　コードの再利用、共通化ができるようになった<br>
・　読み込み順を意識しないとエラーになる(依存関係)<br>
・　何がどこから読み込まれたものかわからない<br>

### 試行錯誤があったモダンJavaScript、npm/yarn等のパッケージマネージャーを使用
・　内部ではNode.js(サーバサイドに実行されるJavaScript)が動いている<br>
・　依存関係を勝手に解決してくれる<br>
・　import先に明示的にわかる<br>
・　世界中で公開されているパッケージをコマンド1つで利用可能<br>
・　チーム内での共有も簡単に<br>
<img width="100" alt="スクリーンショット 2022-08-26 17 33 48" src="https://user-images.githubusercontent.com/65487059/225487898-51973cce-3fb1-4219-a224-3e96c141645d.jpeg">


# ④主にES2015(ES6以降)の記法を使用
### ECMAScriotとは
・　えくますくりぷと<br>
・　JavaScriptの標準規格(こういうルールで書くぜ！)<br>
・　欧州電子計算機工業会<br>
・　毎年1回発表される<br>
・　ES5=ES2014、ES6=ES2015、<br>
・　ES20XXの呼び方を一般化<br>
・　ES2015で機能追加が多くあり、近代JSの転換期と言える<br>

## ★ES2015で追加された規格
・　let、constを用いた変数宣言<br>
・　アローファンクション<br>
・　Class構文(オブジェクト指向でよくでてくる)<br>
・　分割代入<br>
・　テンプレート文字列<br>
・　スレッド構文<br>
・　Promise<br>



