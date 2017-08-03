# 諸々
## 参考サイトURL
https://www.youtube.com/

## 設定時間
15分
## 実時間
10分

# 意識したこと
- 構造が分かりにくいので整理してから記述

# 総評
- 以外にもyoutubeはhtml5での新要素を用いていなかった。
- クラス名の先頭にytという言葉が。たぶんyoutubeの頭文字。クサイ。
- body-containerというクラスを付与するdivが存在。僕で言うcontainerとは違って、body-というまであるのだから、全体を覆う用のクラスなのだろうか
- header群の並びとマークアップに関して、見た感じは「ロゴとナビ」、フォーム、ログイン群の順番だが、マークアップは、「ロゴとナビ」、ログイン群、フォームの順番に鳴っている。なぜ順番を変えたのか。
- ハンバーガーアイコンは個人的に嫌いだが、実装するならbuttonタグで囲む。youtubeもbuttonタグで囲んでいた。そしてハンバーガーがまさかの背景画像
- ナビの構成が、div>ul>liで全体を囲んでいる。liの中は、divをかませてからのul>liになっている。自分はnav>section>ul>liにした。そもそもnavの中にsectionは入れてよいのだろうか。 http://www.tagindex.com/html5/section/section.html この記事内ではaside>h2+nav>section>h3+ul>liにしている。ナビゲーションはリストで構成されている場合は、sectionタグの代わりにliタグを使ったほうが良いのだろうか