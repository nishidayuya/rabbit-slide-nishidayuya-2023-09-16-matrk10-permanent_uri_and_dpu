# 準備

## 画面1

### スライド

```console
bundle exec rake &
```

F11での全画面とウィンドウのトグル

### 端末

C-+を7回

Tmux上で最後のセッション

ディレクトリは以下

- rabbit ~/private/presentations/2023-09-16
    - `bundle exec rake &`
- ruby_matrk10 ~/src/github.com/nishidayuya/test_202309_3_matrk10_ruby

### ブラウザ

#### pull-request

https://github.com/nishidayuya/test_202309_1_matrk10_sample/pull/2/files を表示して次のJavaScriptを実行して投稿した日付を見かけ上，変える．

```js
[...document.querySelectorAll('relative-time[datetime]')].forEach((node) => node.setAttribute('datetime', node.getAttribute('datetime').replace(/.*T/, '2021-01-07T')))
```

200%で開いておく．

#### ruby/rubyのfork

https://github.com/nishidayuya/test_202309_3_matrk10_ruby

#### pull-request改

https://github.com/nishidayuya/test_202309_1_matrk10_sample/pull/3/files を表示して同様のJavaScriptを実行する．

## 画面2

### ブラウザ

- 空のURI

### Emacs

`emacsclient -c`で起動

以下をそれぞれC-x C-0で+を5回

- ~/src/github.com/nishidayuya/test_202309_3_matrk10_ruby/lib/net/http.rb
- `*Messages*`
    - 2行程度表示できる高さ

## 画面3

### ブラウザ

- 空のURI

### Visual Studio Code

C-+を4回ぐらい

- ~/src/github.com/nishidayuya/test_202309_3_matrk10_ruby/lib/net/http.rb
    - 開く
