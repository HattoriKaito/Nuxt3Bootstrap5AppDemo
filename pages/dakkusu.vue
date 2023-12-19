<template>
  <div class="text-center">
    <h2 class="h2-title">ミニチュアダックスフンド</h2>
    <iframe width="640" height="360" src="https://www.youtube.com/embed/qF_Uqh73cDg" title="服がイヤで落ち込む犬#ミニチュアダックス #shorts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <div class="tips-container">
      <ul>
        <li class="tip">年間の医療費が他の犬と比べて少ないと言われており、活発で人気な犬種です。</li>
        <li class="tip">飼い主が大好きでなつきやすいですが、知らない人には吠える傾向があるため、子犬期からのしつけが求められます。</li>
        <li class="tip">定期的なブラッシングで抜け毛を綺麗に取り除く必要がありますが、一定の長さで伸びが止まるため、トリミング頻度は少ないです。</li>
        <!-- Add more tips as needed -->
      </ul>
    </div>
    <nuxt-link to="/" class="back-link">ホームに戻る</nuxt-link>
  </div>
</template>

<style scoped>
  .h2-title {
    font-size: 36px;
    margin-bottom: 20px;
    color: #333;
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
    background-color: #4CAF50;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .back-link:hover {
    background-color: #45a049;
  }
</style>
