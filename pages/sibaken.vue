<template>
  <div class="text-center">
    <h2 class="h2-title">柴犬</h2>
    <iframe width="640" height="360" src="https://www.youtube.com/embed/E6KHGaUHK5Y" title="お迎え柴犬　#柴犬 #柴犬てぃーだ #かわいい" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <div class="tips-container">
      <ul>
        <li class="tip">忠実で勇敢な性格が魅力的で、中型犬の大きさや、小さい豆柴も人気です。</li>
        <li class="tip">飼い主に従順で飼いやすいですが、縄張り意識が強いので初対面の犬や人への関わり方は注意が必要です。</li>
        <li class="tip">換毛期の抜け毛が多いため、定期的なブラッシングでお手入れが必要です。</li>
        <!-- Add more tips as needed -->
      </ul>
    </div>
    <nuxt-link to="/" class="back-link">ホームに戻る</nuxt-link>
  </div>
</template>

<style>
  .h2-title {
    font-size: 36px;
    margin-bottom: 20px;
    color: #333; /* タイトルの色を変更 */
  }

  .tips-container {
    max-width: 600px;
    margin: 0 auto;
    text-align: left;
  }

  .tip {
    font-size: 18px;
    margin-bottom: 10px;
  }

  .back-link {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #4CAF50; /* ボタンの背景色 */
    color: #fff; /* ボタンの文字色 */
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease; /* ホバー時のトランジション */
  }

  .back-link:hover {
    background-color: #45a049; /* ホバー時の背景色変更 */
  }
</style>
