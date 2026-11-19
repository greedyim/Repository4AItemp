# Lavaurs × Mandelbrot — Interactive Explorer

スマートフォン / PC のブラウザから操作できる、Lavaurs のラミネーションとマンデルブロ集合の対応図。

## すぐに開く

- **[操作できる可視化（GitHack・即時プレビュー）](https://raw.githack.com/greedyim/Repository4AItemp/main/index.html)**
- [GitHub Pages（Pages を有効化した後）](https://greedyim.github.io/Repository4AItemp/)

GitHack は公開リポジトリの HTML をブラウザで実行するための第三者のプレビューサービスです。GitHub Pages が有効になれば Pages の URL をおすすめします。

## 使い方

- 左のラミネーションの弧、または右のマンデルブロ集合上の根をタップすると、両方が同時に切り替わります。
- 最大周期を 2〜8 に変更して、周期弦を段階的に増やせます。
- 角度の組、複素座標、周期軌道、近傍拡大、外部射線の近似経路を確認できます。
- iPhone では縦並びになるようにレイアウトを調整しています。

## GitHub Pages の有効化

リポジトリの [Settings → Pages](https://github.com/greedyim/Repository4AItemp/settings/pages) を開き、**Build and deployment → Source → GitHub Actions** を選択します。コミット済みの `.github/workflows/pages.yml` が自動的に公開を行います。

## 数学的注意

円周上で周期角を非交差ペアに結び、両端を同じパラメータ平面の根に対応付けます。有限周期のラミネーションは集合そのものではなく、その組合せ的なモデルです。すべての周期について得られる商空間と実際の集合の同相性は MLC に関係します。

単一ファイル `index.html` に表示用データと背景画像を埋め込んでいるため、外部 JS ライブラリは不要です。
