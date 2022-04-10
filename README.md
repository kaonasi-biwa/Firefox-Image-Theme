# Firefox-Image-Theme
お気に入りの画像を背景にするやつです

images/0.pngをお気に入りの画像に変えてください。

なお、無印Firefox及びFirefox Betaでは使えないと思います。

色はFloorpのダークと同じになっています。

これ( https://gist.github.com/kaonasi-biwa/e735e864feb9d4691b73378799257638 )と使うことを想定しています

## 使い方 1

リンク先のCSSを、プロファイルフォルダ/chrome/userChrome.cssに書き込んでください

その後about:configでtoolkit.legacyUserProfileCustomizations.stylesheetsをtrueにしたらCSS側の準備は整います。

画面いっぱいに表示したいときにはリンク先のCSSのbodyの中に background-size:cover; を追加してください

## 使い方2

まず、このリポジトリをダウンロードして、解凍します(Forkはしなくていいです)

画像を繰り返し表示したい場合は、manifest.json内ののno-repeatをrepeatに変更してください

次に、about:configでxpinstall.signatures.requiredをfalseにします。

内容をいじったものを、zipファイルに圧縮し、「ファイルからアドオンをインストール」でインストールしてください