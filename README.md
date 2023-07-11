# ゲーム のタイトル
* コインゲッター
## 実行環境の必要条件
* python >= 3.10.9
* pygame >= 2.1

## ゲームの概要
* 上から落ちてくるコインを集めてスコアを稼ぐ

## ゲームの実装
###共通基本機能
* 主人公キャラクターと移動
* 普通のコイン（スコア、落下速度など）
* スコア
### 担当追加機能
* super_coin(魯珺生担当)：集めたら普通のコインの2倍のスコアをもらえる。普通のコインより集めしにくい。
* 防壁(魯珺生担当)：tabを押すとplayerの上に防壁が現れる。コインは防壁にぶつかると消える。
### ToDo
- [ ] コードを綺麗にする
### メモ
* 防壁は追加機能「爆弾」に合わせるために作った機能です。
