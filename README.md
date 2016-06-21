# openFrameworks

## 1. openFrameworksの基本

### プロジェクトジェネレータ


プロジェクトを作成するときはプロジェクトジェネレータを使います。
プロジェクトジェネレータはopenFrameworksの中のprojectGenerator - [osの名前]の所にあります。
作成されたプロジェクトはopenFrameworksの中にあるapps/myAppsへ保存されます。

![projectGenerator](https://github.com/Muratchi/MediaArtDengiken/blob/master/projectGenerator.png)


### プロジェクトフォルダーの中身

![folder](https://github.com/Muratchi/MediaArtDengiken/blob/master/folder.png)

1. main.cpp  : 画面の大きさなどの設定を変更するファイル、基本いじらない
2. ofApp.cpp : 実際の動作を記述するファイル 
3. ofApp.h   : ofApp.cppのヘッダーファイル

### openFrameworksの関数

1. setup()  : プロジェクトを実行した時に一度だけ呼ばれる (viDidloadみたいな感じ)
2. update() : 1フレームごとにdraw()と交互に呼ばれる　数値の変更をここで行う
3. draw()   : 実際の描画をここで行う

その他は自分で意味を理解してください。

### 基本的な描画

背景色の変更

``` c++
ofBackground(red, green, blue);
```

描画する色の変更

```
ofSetColor(red, green, blue);
```

直線

``` c++
ofDrawLine(始点のx座標, 始点のy座標, 終点のx座標, 終点のy座標);
```

四角形

``` c++
ofDrawRect(左上のx座標, 左上のy座標, 横幅, 縦幅)
```

丸

```
ofDrawCircle(中心のx座標, 中心のy座標, 半径の大きさ);
```





 





