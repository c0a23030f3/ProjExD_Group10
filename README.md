# Last of Kokaton

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公が敵を倒すことでスコアを獲得しながら、一定のスコアで次のステージに移行する。全3面クリアすることでゲームクリアとなる。ステージをクリアしていくように難化していくように設定。

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* 主人公キャラの攻撃手段の描画
* 敵機の攻撃手段の描画
* 敵機の攻撃手段と主人公キャラの攻撃手段の衝突時の爆発の描画
* スコアの増加についての設定と描画
*  スコア消費によって特殊機能発生
*  スコア200消費で画面全体に重力場設置
* スコア20消費で発動時に存在する鉄器と爆弾の無効化
* スコア100消費で無敵化

### 担当追加機能
* BGM,SE (担当:小川) : 面ごとのBGM、爆発時やビーム発射時、ゲームクリア時などに効果音を付与する機能

### ToDo
- [ ] ほげほげ機能
- [ ] ふがふが関数内の変数名の統一

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
* 参考サイト https://shizenkarasuzon.hatenablog.com/entry/2019/02/24/090652
