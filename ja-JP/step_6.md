## ラズベリーパイのツアー

ラズベリーパイのツアーの時間です。

+ あの左上のラズベリーを見ますか？ ここでメニューをアクセスします。クリックすると、たくさんのアプリケーションが見つかります。

+ **Accessories** をクリックし、**Text Editor**を選択します。

![スクリーンショット](images/pi-accessories.png)

+ 表示されたウィンドウに`I just built a Raspberry Pi` を入力します。

![スクリーンショット](images/pi-text-editor.png)

+ **File**をクリックしてから、**Save**を選択し、 **Desktop** をクリックした際、ファイルを `rp.txt`として保存します。

![スクリーンショット](images/pi-save.png)

+ `rp.txt` という名前のアイコンがデスクトップに表示されます。

![スクリーンショット](images/pi-saved.png)

ファイルはラズベリーパイのSDカードに保存されています。

+ ウィンドウの右上隅にある **X** をクリックして、Text Editorを閉じます。

+ ラズベリーのメニューに戻り、**Shutdown**を選択し、**Reboot**を選択します。

+ パイの再起動後、ファイルは残るはずです。

+ Raspberry PiはLinuxと呼ばれるオペレーティングシステムのバージョンを実行します（WindowsとmacOSは別のオペレーティングシステムです）。 メニューでオプションをクリックする代わりに、コマンドを入力して作業を行うことが可能です。 画面上部の **Terminal** をクリックします。

![スクリーンショット](images/pi-command-prompt.png)

+ 表示されるウィンドウで次のように入力します。

    ls
    

キーボードの</kbd> Enter <kbd>を入力してください。</p> 

<p>
  <code>home</code> ディレクトリーにあるファイルが一覧表示されます。
</p>

<ul>
  <li>
    次、Desktopのディレクトリ－へ移動（<strong>c</strong>hange <strong>d</strong>irectory）するのにこのコマンドを入力してください。
  </li>
</ul>

<pre><code>cd Desktop
</code></pre>

<p>
  すべてのコマンドの後に <kbd>Enter</kbd> キーを押す必要があります。
</p>

<p>
  タイプ：
</p>

<pre><code>ls
</code></pre>

<p>
  作成したファイルを見ることができますか？
</p>

<ul>
  <li>
    <p>
      <strong>X</strong>をクリックしてターミナルウィンドウを閉じます。
    </p>
  </li>
  <li>
    <p>
      <code>rp.txt</code> をデスクトップのゴミ箱にドラッグすると、パイは次の人のために準備が整います。
    </p>
    <p>
      <img src="images/pi-waste.png" alt="スクリーンショット" />
    </p>
  </li>
</ul>