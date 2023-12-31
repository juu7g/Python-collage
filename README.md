# Python-collage
Collage of 4 images

## 概要 Description
4つの画像をコラージュ

## 特徴 Features

- 画面上でコラージュ画像の出来上がりを確認できます
- 生成画像の幅を指定できます
- 境界線の幅を指定できます
- 境界線の色を指定できます
	- 色選択ダイアログで色を指定できます
	- 色選択コンボボックスで色名で色を選択できます

## 依存関係 Requirement

- バイナリ
	- Windows 64bit OS
- プログラム
	- Python 3.8.5
	- Pillow 10.0.0

## 使い方 Usage
- 起動方法
	- collage_by_pillow.exe を実行します
	- または collage_by_pillow.exe のアイコンにコラージュしたい画像をドラッグアンドドロップします  
		※エクスプローラーでドラッグする場合、画像の表示順は、エクスプローラーに表示されている順です。  
		&emsp;表示順を調整したい場合、エクスプローラーの表示を名前順にし、ファイル名を変更して希望の順にしてください。

- 操作方法  
	- ドラッグ＆ドロップでの操作
		- アプリ画面上の4つの枠ににコラージュしたい画像をドラッグ＆ドロップ  
	- 生成画像の幅を指定
		- テキストボックスに生成画像の幅を入力しEnterを押します
			- 画面が指定した幅に変わります
	- 境界線の幅を指定
		- テキストボックスに境界線の幅を入力しEnterを押します
			- 画面が指定した幅に変わります
	- 色の選択
		- 色選択ボタンで選択  
			- 色選択ボタンを押すと色選択ダイアログが表示されます
			- 希望の色を選択して OK ボタンを押します
		- 色選択コンボボックスで選択
			- コンボボックスの▼を押すと色名の選択肢が出るので選択します
			- コンボボックスに色名の一部を入れて↓キーを押すと入力した文字を持つ色名を出力します  
	- 画像の生成
		- 作成ボタンを押します  
			一つ目にコラージュ画像のあるフォルダに `collageyymmddhhmm.jpg` 画像が作成されます

  - 画面の説明  
	- 作成ボタン　　　　　：コラージュした画像を作成します
	- 色選択ボタン　　　　：境界線の色を指定します
	- 色選択コンボボックス：境界線の色を色名で指定します
	- 生成画像の幅　　　　：生成画像の幅を px で指定します
	- 境界線の幅　　　　　：境界線の幅を px で指定します
	- ４つの四角　　　　　：コラージュする画像を表示します


## 制限事項  

- 横向きでアスペクト比が 4:3 の画像が対象  

## プログラムの説明サイト Program description site

- [画像(写真)を４分割レイアウトにコラージュ【Python】 - プログラムでおかえしできるかな](https://juu7g.hatenablog.com/entry/Python/image/collage)  
  
## 作者 Authors
juu7g

## ライセンス License
このソフトウェアは、MITライセンスのもとで公開されています。LICENSEファイルを確認してください。  
This software is released under the MIT License, see LICENSE file.

