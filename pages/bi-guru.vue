<template>
  <div class="text-center" >
    <h2 class="h2-title">ビーグル</h2>
    <iframe width="640" height="360" src="https://www.youtube.com/embed/WpG4kdlcC_c" title="ジョン日記242◇ジョン日記241のショート動画、10回目の巾着田お散歩◇#ビーグル#dogshorts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <div class="tips-container">
      <ul>
        <li class="tip">陽気で愛嬌のある性格が特徴で、家族との絆を大切にします。</li>
        <li class="tip">優れた嗅覚を活かし、獲物を追う獣猟犬としても活躍した歴史があるため、吠えやすくしつけが必要です。</li>
        <li class="tip">運動が好きなので散歩やお出掛けに連れていくと喜ぶでしょう。</li>
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
