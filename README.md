# colabでもローカルでも動くFaster-R-CNN

## これは何

[Ryunosuke-Ikeda/colab_frcnn](https://github.com/Ryunosuke-Ikeda/colab_frcnn)からのフォークです。

[Colabで動く！！Faster R-CNNのPyTorch実装 by lmR0305](https://qiita.com/ImR0305/private/c2674dfe9f5ec1301304)も合わせてご覧ください。

どの環境でも動くように改良しました。

**（ここから原文）**

---
# colabで動くFaster-R-CNN
使いやすいようにColab実装版を書きました。
あまり実行環境に左右されず誰でも動かせると思います。
詳しくは[qiita](https://qiita.com/ImR0305/private/c2674dfe9f5ec1301304)をご参照ください。

データセット展開時の想定ディレクトリ構造

colab_frcnn-main/

┣Faster-R-CNN.ipynb

┣ smallbdd/

　　　┣test/
   
　　　┣xml/
   
　　　┣img/

