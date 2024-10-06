
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>電通 太郎のホームページ</title>
    <style>
      h1 {
        color: pink;
        background-color: #4abdac;
        padding: 32px;
        text-shadow: 2px 2px 4px black;
        font-size: 64px;
        text-align: center;
      }
      h2 {
        color: darkgreen;
        border-left: 8px solid #4abdac;
        padding-left: 8px;
        margin-top: 32px;
      }
      img{
        border: 4px solid gray;
        width: 480px;
        height: 270px;
        border-radius: 20px;
      }
      main{
        margin: 16px;
      }
      .cycling{
        color: blue;
      }
      .violine{
        color: orange;
      }
      .pictures{
        background-color: black;
      }
      .cycling,
      .violine{
        font-size: 20px;
      }
      .food li{
        color: green;
      }
    </style>
  </head>
  <body>
    <h1>加賀美漣ホームページ</h1>
    <main>
      <h2>人物紹介</h2>
      <p>
      こんにちは。中学三年生の加賀美 漣です。趣味は<span class="cycling">数学の解説動画</span>を見ることと<span class="violine">ゲーム</span>で、
      数学が好きです。よろしくお願いします。
      </p>
      <h2>サイト紹介</h2>
      <p>私がよく使っているサイトは、<a href="https://chatgpt.com/">ChatGTP</a>です。</p>
      <h2>好きな食べ物</h2>
      <ul class="food">
          <li>刺身</li>
          <li>ラーメン</li>
          <li>マヨネーズ</li>
      </ul>
      <h2>おすすめ小説トップ３</h2>
      <ol>
          <li>公開処刑人森のくまさん</li>
          <li>変な家</li>
          <li>隣はシリアルキー</li>
      </ol>
      <h2>写真</h2>
      <div class="pictures">
        <img src="https://i.imgur.com/HIxTKbe.jpg" />
        <img src="https://i.imgur.com/pAQ7QKc.jpg" />
      </div>
      <h2>お問い合わせ</h2>
      <form action="http://soasa.starfree.jp/form.php">
        名前: <input type="text" name="name" placeholder="加賀美漣" />
        <br/>
        <input type="radio" name="animal" value="dog" />犬派
        <input type="radio" name="animal" value="cat" />猫派
        <input type="radio" name="animal" value="other" />その他
        <br/>
        <input type="checkbox" name="music"/>楽器経験がある
        <br/>
        <textarea name="comment"></textarea>
        <br/>
        <input type="submit" value="送信する" />
      </form>
    </main>
  </body>
</html>
チーム開発テストのリポジトリです。
