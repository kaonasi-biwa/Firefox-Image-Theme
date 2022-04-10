# Firefox-Image-Theme
お気に入りの画像を背景にするやつです

images/0.pngをお気に入りの画像に変えてください。

色はFloorpのダークと同じになっています。

これ( https://gist.github.com/kaonasi-biwa/e735e864feb9d4691b73378799257638 )と使うことを想定しています

リンク先のCSSは、プロファイルフォルダ/chrome/userChrome.cssに書き込んでください

その後about:configでtoolkit.legacyUserProfileCustomizations.stylesheetsをtrueにしたらCSS側の準備は整います。

画面いっぱいに表示したいときにはリンク先のCSSのbodyに background-size:cover; を追加してください

画像を繰り返し表示したい場合は、manifest.jsonのno-repeatをrepeatに変更してください

内容をいじったあと、zipファイルに圧縮し、「ファイルからアドオンをインストール」でインストールしてください

なお、無印Firefox及びFirefox Betaでは使えないと思います。

Firefox Nightly,Developer Edition,Floorp Legacyなら、about:configでxpinstall.signatures.requiredをfalseにすることでインストールできます。