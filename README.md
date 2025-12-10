# ShellGen - 3D Shell Generator

**ShellGen** は、数理モデル（対数螺旋）に基づいて貝殻の形状をシミュレーションし、3Dモデルを生成するWebツールです。
ブラウザ上でパラメータを調整し、リアルタイムに形状を確認しながら、3Dデータ（STL/OBJ）をエクスポートできます。

## ✨ 特徴

* **リアルタイム3Dプレビュー**: パラメータの変更が即座に3Dモデルに反映されます。
* **数理形態学に基づく制御**:
  * **Growth (Length)**: 成長の長さ
  * **Expansion Rate**: 螺旋の広がり率
  * **Shape (Cone)**: 円錐の太さ、曲がり具合（Bend）、傾き（Tilt）、ねじれ（Twist）など
* **断面エディタ (Cross Section Editor)**: 断面の形状を2Dエディタで自由に描画・変形可能。
* **プリセット機能**: アンモナイト、サザエ、二枚貝などの典型的な形状へ瞬時に切り替え。
* **エクスポート**: 作成したモデルを **STL** または **OBJ** 形式でダウンロード可能。
* **Undo/Redo**: `Ctrl+Z` / `Ctrl+Shift+Z` で操作の取り消し・やり直しが可能。

### オンラインデモ
（GitHub Pagesなどで公開する場合はここにURLを記載してください）

## 🛠️ 技術スタック

* **React 18**: UIコンポーネントと状態管理
* **Three.js**: WebGLによる3Dレンダリング
* **Tailwind CSS**: スタイリング
* **Babel Standalone**: ブラウザ内でのJSXコンパイル

## 📚 参考

* **大阪大学大学院生命機能研究科 近藤滋研究室**
  * [巻貝の形のシミュレーター](https://www.fbs.osaka-u.ac.jp/labs/skondo/simulators/shell/ShellShapeForSmartPhone.html)

## 📄 ライセンス

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
