# Podcast用テンプレート

## Talk script
A/Bは隔週入れ替わりで、原則以下のルールで担当する.
- 偶数回の収録時は A:yaginuuun, B:takapy
- 奇数回の収録時は A:takapy, B:yaginuuun

音源の編集, 公開のスケジューリング, Twitterの投稿は基本的にAが担当.

```
### opening
A) みなさんこんにちは. Aです.
B) Bです.

A) Work In Progressは、テクノロジーを中心に、キャリア・ビジネスなどの話題についてカジュアルに話すPodcastです.

〜雑談〜（2〜5分くらい）

ということで、今回のトピックはhogeです.  
〜本編〜（10分~20分くらい）

### ending
今日はこの辺りで終わりですかね.

A) というわけで本日は◯◯◯についてお話しました.
A) 質問・コメントはGoogleフォームやTwitterの #wipfm（ハッシュタグ ウィップエフエム） でお待ちしております.
A) ご視聴ありがとうございました。来週またお会いしましょう.

```

## Anchor Description
関連箇所を更新してそのままペーストする.  
※URLはAnchor上で意図的にリンクを貼り直す必要あり※

基本的に月曜日のAM 7:00に公開スケジューリングする.

```
こんにちは！今回は、hogeについて話しました.
========================
◎関連リンク
・タイトル
リンク
・タイトル
リンク
========================
◎質問や感想、扱って欲しいトピックなど、お気軽にコメントお待ちしております.
・Googleフォーム
http://urx.space/VNOD
・Twitterのハッシュタグ
https://twitter.com/hashtag/wipfm
・Twitterアカウント
https://twitter.com/wipfm0509
========================
◎"Work In Progress"とは
機械学習エンジニアの@takapyとデータアナリストの@yaginuuunが、テクノロジーやキャリア、ビジネスなどの話題についてカジュアルに話すPodcast番組です.

公式サイト: https://bit.ly/2UbGXIX
@takapy: https://twitter.com/takapy0210
@yaginuuun: https://twitter.com/yaginuuun

```

## Twitter
その回の💭 サマリを3行くらいで書く.  
anchorのリンクは短縮URLを使ってなるべく文字数を削減する.

以下簡単な手順

1. [anchorで対象のエピソード](https://anchor.fm/geek-engineer-future)のURLをコピーする
2. [このサイト](https://qr.quel.jp/form_shorten.php)で 1.でコピーしたURLの短縮URLを作成する.1日5回しか発行できないので回数に注意（アクセス数も[ここ](https://qr.quel.jp/pv.php?b=)からチェックできる）
    - （2021.08.08 追記）なんかサイトの仕様が変わっててそのままだと短縮URLコピーできなくなってたので、上記サイトで発行された数字7桁を`http://bit.ly/`にくっつける感じにすれば良い.
3. [Twitter](https://twitter.com/wip__fm)を開いてツイートボタンを押し、2.で生成したリンクを文末にペーストしてから下記文言を追加する

```
\ #podcast 更新🎙 /
今回はhogeの話をしました！

💭 サマリ1
💭 サマリ2
💭 サマリ3

お便りはこちら
📮 http://urx.space/VNOD
🔖 #wipfm

※ここにanchorのリンクを貼る（Tweetの文末に貼らないとOGPがうまく表示されないので注意）※
```

## Notionブログの更新Tips
- URL: https://www.notion.so/takapy/Work-In-Progress-Portal-3623f6bc1b1e4f48960fbaa915703da5
- 短縮URL: https://bit.ly/2UbGXIX
    - 短縮URLのアクセス集計: https://qr.quel.jp/pv.php?b=2UbGXIX

※シェアする場合は基本的に短縮URLを用いること

### ギャラリーに追加するOGP画像を手軽につくる

サイト: https://ogpng.vercel.app/

上記サービスに下記コードを貼り付けると良い感じの画像が生成される.
```html
<div style="
    background: radial-gradient(#263B42, #263B42);
    width: 440px;
    height: 230px;
    padding: 20px;
    text-align: center;
    color: #FFBD59;
    font-size: 28px;
    font-family: 'ヒラギノ角ゴ ProN W3';
    display: flex;
    flex-direction: column;
    justify-content: center;
    "
>
   <p>ここにタイトルを記載</p>
</div>
```
