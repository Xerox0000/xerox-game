# ゲーム典型 (C++ & Siv3D)

様々なゲームのプログラムを C++ & Siv3D で書いていくプロジェクトです。ほとんどの行にコメントが付いていて、学習の参考にしやすいコードになっています。

- コードのライセンスはパブリックドメインで、自由に再利用できます
- 派生 / 改造プログラムを作ったら、ぜひ Zenn や Qiita に投稿してみてください
  - その際に、このリポジトリにリンクしてもらえるとありがたいです。
- ゲームの番号 (001A など) は一意 & 将来にわたって固定です
- バグや改善案の提案、リクエストなどはこのリポジトリの Issue をご利用ください

| 番号 | ゲーム | 難易度 | キーワード |
|:---:|:---|:---:|:---|
| 001A | [ブロックくずし](games/001/A.md) | ★2 | 図形クラスを活用しよう |
| 001B | [再挑戦可能なブロックくずし](games/001/B.md) | ★2 | 初期状態を作る関数を再利用しよう |
| 001C | ボールの貫通が起こりにくく、フレームレート変動に強いブロックくずし | ★4 | 1 フレーム内で微小時間の更新を繰り返そう |
| 002A | [タイピングゲーム](games/002/A.md) | ★1 | `TextInput::Update()` を活用しよう |
| 003A | [神経衰弱](games/003/A.md) | ★3 | トランプの描画は `PlayingCard` |
| 004A | [ハノイの塔](games/004/A.md) | ★2 | 配列を使ってコードを短くしよう |
| 005A | [2D 物理演算による破壊ゲーム](games/005/A.md) (Angry Birds など) | ★2 | `P2Body::setVelocity()` で発射速度を設定 |

### 参考リンク
- [Siv3D 公式リポジトリ](https://github.com/Siv3D/OpenSiv3D)
- [Siv3D 公式サイト](https://siv3d.github.io/ja-jp/)
- [Siv3D 公式リファレンス](https://zenn.dev/reputeless/books/siv3d-documentation)

### 姉妹プロジェクト
- [競プロ典型 90 問 練習 (C++17)](https://github.com/Reputeless/tenkei_90)
