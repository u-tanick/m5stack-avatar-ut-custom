# M5Stack-Avatar Custom Face

M5Stack-Avatarを元に、オリジナルのカスタムフェイスを作成した版です。

カスタムフェイス以外のコードは、M5Stack-Avatarからは変更してません。
（なのでトップのReadmeもオリジナルのまま）

## AAFace

デフォルトの顔 [・＿・] をベースに、ショボーン (´・ω・\`) やシャキーン(\`・ω・´)にカスタムしたものです。

- スケッチファイル
  - /example/custom-face-aa/custom-face-aa.ino
- カスタムフェイス定義
  - /src/faces/AAFace.h

スケッチファイルは、face-and-colorをベースに従来のDogFaceの部分をAAFaceを読み込むように改変したものです。
そのため、このスケッチを書き込んだ初期状態はデフォルトの顔 [・＿・]が表示されます。

AAFaceを表示させるには、Aボタンを押してください。

また、感情毎に眉毛の有無などもカスタマイズしていおり、face-and-color同様、Cボタンを押して表情を変更・確認することができます。

