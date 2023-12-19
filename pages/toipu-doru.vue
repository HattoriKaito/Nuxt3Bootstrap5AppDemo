<template>
  <div class="text-center">
    <h2 class="h2-title">トイプードル</h2>
    <iframe width="640" height="360" src="https://www.youtube.com/embed/5uUp7camTNs" title="お勉強やる気満々のトイプードル　#Shorts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <div class="tips-container">
      <ul>
        <li class="tip">知能が高く、しつけがしやすい犬種です。</li>
        <li class="tip">カールした毛が可愛らしくて抜け落ちにくいため、お手入れは簡単ですが、月に1回程度はトリミングをする必要があります。</li>
        <li class="tip">飼い主が大好きでなつきやすいですが、構いすぎると分離不安にもなりやすいでしょう。</li>
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
