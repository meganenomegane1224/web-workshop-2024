## 付録1. Markdownの主な記法

ここでは、よく使われるMarkdownの記法について紹介します。

なお、Markdownにもいくつかの派生(方言)があるため、あるサイトで使えた記法が別のサイトでは利用できない、といった場合もいくつかあります。

(Markdownのよく使われる派生仕様の例: GitHub Flavored Markdown https://github.github.com/gfm/)

### 見出し

```md
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```

見出しは `#` が少ないほどレベルが高い(大きい)見出しになります。

### 文字装飾

```md
**太字**
*斜体*
~~取り消し線~~
```

### 箇条書き

```md
- 項目1
- 項目2
- 項目3
  - 子項目1
  - 子項目2

1. 番号付き1
2. 番号付き2
3. 番号付き3
```

### 引用

```md
> 引用文
```

### リンク

```md
[リンクタイトル](https://www.example.com/)
```

### 画像

```md
![画像の説明文](./images/image1.png)
```

画像の説明文は基本的に常時表示はされませんが、カーソルを合わせた場合などに表示されることがあります。

相対パスはMarkdownファイルを基準としたパスであることに気をつけてファイルを配置しましょう。

### 区切り線

```md
---
```