---
title: "about-aglaus"
titleja: "About Aglaus"
eyecatch: "hugo.png"
date: 2015-01-06
comments: true
tags: ["hugo", "golang", "aglaus"]
---

## About hugo theme [Aglaus]

**Aglaus** is theme for [Hugo](http://gohugo.io).

### Comment

You can use [Disqus](https://disqus.com/).

Set `Disqus` to `config.yaml`, and set `comments: true` to Markdown.

[<img src="/hugo_theme_aglaus/images/desc_disqus.png" class="image" alt="disqus">](/hugo_theme_aglaus/images/desc_disqus.png)

If you did not set, the comments section is not displayed.

If you want to deny a comment only particular article, you can either unset the `comments`, please set the `false`.

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
comments: false
---

## About hugo theme [Aglaus]
 :
 :
```

### Eyecatch image

Eye-catching image can be set to the article unit.

[<img src="/hugo_theme_aglaus/images/desc_eyecatch.png" class="image" alt="eyecatch">](/hugo_theme_aglaus/images/desc_eyecatch.png)

Set the `eyecatch` to Markdown file of articles, please deploy the image to `static/images/` below.

``` markdown
---
title: "about-aglaus"
eyecatch: "hugo.png"
date: 2015-01-06
---

## About hugo theme [Aglaus]
 :
 :
```

If you did not set, default image is displayed.

### Tag

By setting the `tags`, you can tag the article.

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
tags: ["hugo", "aglaus"]
---

## About hugo theme [Aglaus]
 :
 :
```

Tag is displayed at the bottom of the article individual pages, will be used in the indexing of related posts.

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

### Related Post

Display posts associated with the reference tags.

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

You can hide it by the `ShowRelatedPost` of `config.yaml` to `False`.

In that case, also will not be displayed tag.

### Profile

Profile is displayed at the bottom of the page.

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

Information of profile getting from [Gravatar](https://gravatar.com/).

Please set the `GravatarHash` to `config.yaml`.

Please refer to the [Creating the Hash](https://ja.gravatar.com/site/implement/hash/) for hash of the acquisition.

If you did not set, profie is not displayed.

### Social Links

You can place a link on [Facebook](https://www.facebook.com/) and [Twitter](https://twitter.com/) and [GitHub](https://github.com/).

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

You need to set the ID of the 'Facebook' and 'Twitter' and 'Github' to 'config.yaml'.

### Share Buttons

Share buttons is displayed at the bottom of the page.

[<img src="/hugo_theme_aglaus/images/desc_share.png" class="image" alt="share">](/hugo_theme_aglaus/images/desc_share.png)

Using the plugin [SHAREBUTTON](http://sharebutton.net/).

## Contact Me

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

[https://twitter.com/dim0627](https://twitter.com/dim0627)

---

## Hugo用テーマ[Aglaus]について

Golangで書かれた静的サイトジェネレータ、[Hugo](http://gohugo.io)用のテーマです。

### コメント

[Disqus](https://disqus.com/)が導入出来ます。

`config.yaml`の`Disqus`を設定し、記事のMarkdownに`comments: true`を設定してください。

[<img src="/hugo_theme_aglaus/images/desc_disqus.png" class="image" alt="disqus">](/hugo_theme_aglaus/images/desc_disqus.png)

設定されなかった場合、コメント欄は表示されません。

特定の記事のみコメントを拒否する場合は、`comments`を未設定にするか、`false`を設定してください。

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
comments: false
---

## About hugo theme [Aglaus]
 :
 :
```

### 日本語用の記事タイトル

Hugoは記事のパーマリンク設定に`:title`を含めた場合、Markdownに記述された`title`をURLに設定します。

日本語を設定するとパーセントエンコードされた形でURLが生成されますが、`Aglaus`では`titleja`を設定することで、記事のタイトルを別途設定出来ます。

``` markdown
---
title: "about-aglaus" // URLに設定される
titleja: "Aglausについて" // 記事のタイトルとして表示される
date: 2015-01-06
---

## About hugo theme [Aglaus]
 :
 :
```

titlejaタグを設定しなかった場合は`title`が設定されます。

### アイキャッチ画像

記事単位にアイキャッチ画像が設定出来ます。

[<img src="/hugo_theme_aglaus/images/desc_eyecatch.png" class="image" alt="eyecatch">](/hugo_theme_aglaus/images/desc_eyecatch.png)

記事のMarkdownファイルに`eyecatch`を設定し、`static/images/`以下に画像を配備してください。

``` markdown
---
title: "about-aglaus"
eyecatch: "hugo.png"
date: 2015-01-06
---

## About hugo theme [Aglaus]
 :
 :
```

不要な場合は記述を削除することでデフォルト画像が表示されます。

### タギング

`tags`を設定することで、記事にタグをつけることが出来ます。

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
tags: ["hugo", "aglaus"]
---

## About hugo theme [Aglaus]
 :
 :
```

タグは記事個別ページの下部に表示され、関連する投稿のインデクシングに利用されます。

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

### 関連する投稿

タグを基準に関連する投稿を表示します。

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

`config.yaml`の`ShowRelatedPost`を`False`にすることで非表示にできます。

その場合、タグも表示されなくなります。

### プロフィール

ページ下部にプロフィールを表示出来ます。

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

表示する情報は[Gravatar](https://gravatar.com/)から取得しているため、`config.yaml`に`GravatarHash`を設定する必要があります。

ハッシュの取得については[Creating the Hash](https://ja.gravatar.com/site/implement/hash/)を参照してください。

設定がない場合、プロフィールは表示されません。

### ソーシャルリンク

プロフィールに[Facebook](https://www.facebook.com/)、[Twitter](https://twitter.com/)、[GitHub](https://github.com/)のリンクを配置出来ます。

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

`config.yaml`に`Facebook`、`Twitter`、`Github`のIDを設定する必要があります。

設定がない場合、リンクは表示されません。

### シェアボタン

ページ最下部にシェアボタンが表示されます。

[<img src="/hugo_theme_aglaus/images/desc_share.png" class="image" alt="share">](/hugo_theme_aglaus/images/desc_share.png)

[SHAREBUTTON](http://sharebutton.net/)のプラグインを利用しています。

## お問い合わせ

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

[https://twitter.com/dim0627](https://twitter.com/dim0627)

