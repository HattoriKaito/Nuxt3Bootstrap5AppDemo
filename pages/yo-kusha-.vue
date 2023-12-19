<template>
  <div class="text-center">
    <h2 class="h2-title">ヨークシャーテリア</h2>
    <iframe width="640" height="360" src="https://www.youtube.com/embed/imS_K3O51E0" title="ヨークシャーテリアの子犬の俊敏さと運動量がスゴイ！まるで室内ドッグラン状態！？" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <div class="tips-container">
      <ul>
        <li class="tip">元気で活発な性格で、飼い主への愛情深い犬種です。</li>
        <li class="tip">長くて艶のある毛が魅力的ですが、日々のブラッシングや定期的なトリミングでのお手入れが必要になります。</li>
        <li class="tip">大きな音にストレスを感じるような、怖がりな面もあるため、よくみて注意しましょう。</li>
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
