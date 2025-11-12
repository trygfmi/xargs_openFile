
<h2 class="wp-block-heading">前書き</h2>



<p>このリポジトリは、xargsコマンドを実行して|(パイプ)から受け取った文字列でファイルを開く体験ができます</p>



<h2 class="wp-block-heading">インストールする必要のあるコマンド</h2>



<ol class="wp-block-list">
<li>git</li>
</ol>



<h2 class="wp-block-heading">クイックスタート</h2>



<p>上記のコマンドをインストール済みの方は、以下のコマンドを実行してリポジトリからダウンロード後、ディレクトリを移動し、xargsコマンドを実行してopenコマンドでファイルを開いてください</p>



<h3 class="wp-block-heading">ubuntu</h3>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs -n 1 open</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>example1.txt
example2.txt
example3.txt
example4.txt
example5.txt
#5つのファイルが開きます</code></pre>
</details>



<h3 class="wp-block-heading">macos</h3>



<h4 class="wp-block-heading">MacPorts</h4>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>source ~/bashrc_folder/macports_aliasgit clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs open</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>example1.txt
example2.txt
example3.txt
example4.txt
example5.txt
#5つのファイルが開きます</code></pre>
</details>



<h3 class="wp-block-heading">windows</h3>



<h4 class="wp-block-heading">WSL2</h4>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>不可</code></pre>
</details>



<h4 class="wp-block-heading">MSYS2 MINGW64</h4>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs -n 1 start</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>example1.txt
example2.txt
example3.txt
example4.txt
example5.txt
#5つのファイルが開きます</code></pre>
</details>



<h2 class="wp-block-heading">実行手順</h2>



<h3 class="wp-block-heading">ubuntu</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<p>以下のコマンドを端末に打ち込んでcommand not foundが出なければokです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git --version</code></pre>



<h4 class="wp-block-heading">preinstall</h4>



<p>端末でcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>sudo apt install git</code></pre>



<h4 class="wp-block-heading">コマンド</h4>



<p>以下のコマンドを実行することで詳細のファイルが開かれるはずです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs -n 1 open</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>example1.txt<br>example2.txt<br>example3.txt<br>example4.txt<br>example5.txt<br>#5つのファイルが開きます</code></pre>
</details>
</details>



<h3 class="wp-block-heading">macos</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<p>以下のコマンドをターミナルに打ち込んでcommand not foundが出なければokです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>source ~/bashrc_folder/macports_aliasgit --version</code></pre>



<p>※macosはMacPortsパッケージマネージャを使用してコマンドを管理します。もしインストールしていない方は以下のリンクからMacPortsのインストール手順をご覧ください</p>



<p>またコマンドに別名を設定して既存の環境と競合しないでコマンドを呼び出せるようにします。</p>



<p>初めてこのブログを利用する方は、以下の2つの記事を参考に環境構築してください</p>



[![MacPortsをインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports_title_1920_1080_2.png,)](https://ss523971.stars.ne.jp/todo/how-to-install-macports)



[![MacPortsでインストールしたコマンドのエイリアス設定](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports2.png,)](https://ss523971.stars.ne.jp/todo/how-to-setup-macports-alias)



<h4 class="wp-block-heading">preinstall</h4>



<p>ターミナルでcommand not foundが出たコマンドを以下のコマンドでインストールしてエイリアスを設定してください</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>sudo port install gitecho 'alias git="/opt/local/bin/git"' >> ~/bashrc_folder/macports_alias</code></pre>



<h4 class="wp-block-heading">コマンド</h4>



<p>以下のコマンドを実行することで詳細のファイルが開かれるはずです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>source ~/bashrc_folder/macports_aliasgit clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs open</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>example1.txt<br>example2.txt<br>example3.txt<br>example4.txt<br>example5.txt<br>#5つのファイルが開きます</code></pre>
</details>
</details>



<h3 class="wp-block-heading">windows</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<p>以下のコマンドをプロンプトに打ち込んでcommand not foundが出なければokです</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git --version</code></pre>



<p>※windowsはWSL2とMSYS2 MINGW64で確認しています。可能な限りWSL2をインストールしていただいて、もし設定できなかった場合はMSYS2をインストールすることで実行できますが、所々WSL2でしか実行できないコマンドが出てくるかもしれません。WSL2とMSYS2のインストール方法は下記の記事を参考にしてください</p>



[![[windows] msys2をインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_WSL2_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-wsl2/)



[![](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/msys2_thumbnail_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-msys2)



<h4 class="wp-block-heading"><strong>preinstall</strong></h4>



<p>プロンプトでcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>pacman --sync git</code></pre>



<h4 class="wp-block-heading"><strong>コマンド</strong></h4>



<p>以下のコマンドを実行することで詳細のファイルが開かれるはずです</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>不可</code></pre>
</details>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/xargs_openFilecd xargs_openFilefind . -type f -name "*.txt" | xargs -n 1 start</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>example1.txt<br>example2.txt<br>example3.txt<br>example4.txt<br>example5.txt<br>#5つのファイルが開きます</code></pre>
</details>
</details>



<h2 class="wp-block-heading">後書き</h2>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>find . -type f -name "*.txt"</code></pre>



<p>と</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>find . -type f -name "*.txt" | xargs</code></pre>



<p>を実行してみてください。出力されたファイルパスの文字列をxargsコマンドが空白区切りに処理して、openコマンドで開けるようにしてくれています。windowsとubuntuのxargs -n 1は、コマンドが引数を一つしか認識しないのでオプションで1つずつ渡しています。windowsのstartは、openコマンドを使用できないため使用しています</p>



<p></p>



<p></p>
