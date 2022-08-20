# TagLib for Windows

音楽ファイルのタグを扱うライブラリ[TagLib](https://taglib.org)を
QtCrearor、MSVCで組み込めるようにしたプロジェクト一式です。

### 変更点
- 山括弧(<>) は廃止、全て二重引用符("")に変更
- インクルードパスをtaglibを起点としたパスに変更
- 3rdpartyフォルダの場所を移動
- cmake類等、プログラム動作に関係ないファイルはオミット

### ライセンス
- [MPL 1.1](COPYING.MPL)
- [LGPL 2.1](COPYING.LGPL)