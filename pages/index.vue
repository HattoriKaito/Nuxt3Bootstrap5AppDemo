<template>
  <div class="text-center">
    <h1>飼いやすい犬種！</h1>
    
    <div class="container">
      <div class="row">
        <div class="col-md-4 mb-3">
          <nuxt-link to="/sibaken">
            <img
              src="https://1.bp.blogspot.com/-WPATRPUzFks/Ur1KwoeD4hI/AAAAAAAAELA/PgDgKwCxI50/s1600/0095-17.jpg"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="handleImageClick"
            />
          </nuxt-link>
        </div>
        <div class="col-md-4 mb-3">
          <nuxt-link to="/bi-guru">
            <img
              src="https://www.restonnow.com/files/2015/06/CustisDOG2-600x399.jpeg"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="sImageClick"
            />
          </nuxt-link>
        </div>
        <div class="col-md-4 mb-3">
          <nuxt-link to="/tiwawa">
            <img
              src="https://wanchan-life.com/wp-content/uploads/2019/08/IMG_3985.jpg"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="sImageClick"
            />
          </nuxt-link>
        </div>
      </div>

      <div class="row">
        <div class="col-md-4 mb-3">
          <nuxt-link to="/dakkusu">
            <img
              src="https://www.moo-pon.com/main/wp-content/uploads/2017/06/DSC00182.jpg"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="sImageClick"
            />
          </nuxt-link>
        </div>
        <div class="col-md-4 mb-3">
          <nuxt-link to="/toipu-doru">
            <img
              src="https://www.petoffice.co.jp/_uploads/livingBody/190/0554%E3%83%88%E3%82%A4%E3%83%97%E3%83%BC%E2%99%82%E6%A8%AA.JPG"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="sImageClick"
            />
          </nuxt-link>
        </div>
        <div class="col-md-4 mb-3">
          <nuxt-link to="/yo-kusha-">
            <img
              src="https://pettimes.jp/wp-content/uploads/2019/05/yorkshire-terrier_feature-768x511.jpeg"
              alt="Mastery Guide Image"
              class="img-fluid equal-image"
              style="margin-top: 15px;"
              @click="sImageClick"
            />
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    handleImageClick() {
      this.$router.push('/rank-tips'); // /rank-tips ページに移動
    },
    sImageClick() {
      this.$router.push('/s');
    },
  },
};
</script>

<style scoped>
  .title {
    font-size: 36px; /* フォントサイズを適切な値に変更 */
  }

  .equal-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease-in-out; /* アニメーションの追加 */
  }

  .equal-image:hover {
    transform: scale(1.1); /* クリック時の拡大アニメーション */
  }
</style>