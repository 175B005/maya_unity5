# maya_unity5
maya unity 連携機能5（モデリングmaya編）


1. 連携機能４で紹介した、モデルの作り方について説明していきます。
1. コンセプトは、「簡単。早い。無機物」です。  
連携機能３では人型、つまり、有機のモデルなので、設定次第で変わるよ。  
ということを伝えるため、二種類やってます。。
1. では、使い方と一緒に、モデルデータを作成していきましょう。
1. 左上メニューの設定が「モデリング」になっているのを確認したら、  
ちょっと下のメニュー、「ポリゴン」も選択しておきましょう。  
これを設定しておくと、ショートカットで機能が使えます。（デフォルトではもうなってる。↑）
1. 何か失敗しちゃったりしたら、Ctrl + Zで戻れます。
1. あと、セーブしておきたいタイミングで、ファイル→保存　で保存しましょう。
1. その後に、上部メニュー< 編集< 種類毎に全て削除< ヒストリ  
これを削除しておかないと、どんどん、ヒストリーデータが増えていきます。  
大きなことやろうとしていると、データが重くなって、maya落ちますｗｗ  
ですが、ヒストリーがなくなるので、戻る操作で、前に戻れなくなります。。

---
1. ポリゴンメニュの立方体アイコンをクリック(Cubeを生成)  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction1-3.jpg)  
1. 右のメニュー、「アトリビュート　エディタ」から、幅、高さ、奥行き（ｘ、ｙ、ｚ）を調整できます。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction1-1-3.png)
1. このオブジェクトを選択後に　Ctrl + Dキーを押すと複製ができます。  
上部メニューの作成< 複製 でも可です。
1. 足の接合パーツを作っていきます。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction2-3.jpg)
1. 一度機能を紹介しておきます。上メニューの四角とか丸のマークを押すと、X線表示などができます。  
色がついてない！。とか表示がおかしい！ってなったときは、ここを疑ってください。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction3-3.jpg)
1. 話をもどして、、さっきの手順で足を複製、４つにします。  
Shift を押しながらにすると、複数選択できます。  
ドラッグで一気に選択ももちろんできます。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction4-3.jpg)
1. もう４つ生成して、第二足（？？っていうのか、、）を作ります。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction6-3.jpg)
1. 形を整えます。ここではフェース（面）の機能を使っていきます。  
オブジェクトの上で右マウスを押しながらにすると、編集機能が選択できます。  
下のフェースというのを選択してマウスを放すと、機能はフェースモードになります。  
（初期でやっていた機能はオブジェクトモードで、物一つ一つを動かすのに便利というか、基本これ。）  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction7-3.jpg)
1. フェースモードでは、選択するのはオブジェクト単位ではなく、面単位で編集します。  
面を選択してから移動させると、選択した面だけが動くので、  
移動させたくない場所があるモデルでも、一部だけを編集できます。（他の機能もそう）

---
1. 補足。面の数、オブジェクトの数、などなど、多くなればなるほど、  
データの容量が多くなるので、少ないデータでいかに表現できるかというのが、  
気になるところ。。今回は、丸みを出す方法を簡単に使っていきたいと思います。
1. べベルエッジを紹介します。  
つけたいオブジェクトを選択　→　上部メニュー< メッシュの編集< べベル< □のメニュー　  
→　べベルのオプション「幅、セグメント、スムージング角度」を調節。→　適用（or べベル）  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction28-3.jpg)
1. 簡単に線を入れることができました。（たぶんこれが一番データ少なく、うまく表現できる機能かと思えます。  
　ただし、無機物が基本、、ものの角をスムージングするだけですので。）  
 
[前ページ](https://github.com/175B005/maya_unity4)| [次ページ](https://github.com/175B005/maya_unity6)|[目次](https://github.com/175B005/maya_unity_index)
