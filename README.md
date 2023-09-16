# ソースコード参照URIの考察と作成したツールの紹介

2023-09-16に開催された[松江Ruby会議10](https://matsue.rubyist.net/matrk10/)での発表資料

---

ソースコードを参照するURIは，ブランチ名を使ったものよりもコミットIDを使ったもの（permalink）がよく，さらにはタグ名を使ったものがより望ましいと考える．本発表ではその説明と作成したツールの紹介を行う．

## 作者向け

### 表示

    rake

### 公開

    rake publish

## 閲覧者向け

### インストール

    gem install rabbit-slide-nishidayuya-2023-09-16-matrk10-permanent_uri_and_dpu

### 表示

    rabbit rabbit-slide-nishidayuya-2023-09-16-matrk10-permanent_uri_and_dpu.gem
