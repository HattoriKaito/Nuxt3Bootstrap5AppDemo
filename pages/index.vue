<template>
  <div>
    <head>
    <title>飼いやすい犬種！</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  </head>
<body class="text-center">
  <h1>飼いやすい犬種！</h1>
  </body>
    <nuxt-link to="/rank-tips">
      <img
        src="https://1.bp.blogspot.com/-WPATRPUzFks/Ur1KwoeD4hI/AAAAAAAAELA/PgDgKwCxI50/s1600/0095-17.jpg"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="handleImageClick"
      />
    </nuxt-link>
    <nuxt-link to="/s">
      <img
        src="https://www.restonnow.com/files/2015/06/CustisDOG2-600x399.jpeg"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="sImageClick"
      />
    </nuxt-link>
    <nuxt-link to="/gold">
      <img
        src="https://wanchan-life.com/wp-content/uploads/2019/08/IMG_3985.jpg"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="sImageClick"
      />
    </nuxt-link>
    <nuxt-link to="/puratina">
      <img
        src="https://www.moo-pon.com/main/wp-content/uploads/2017/06/DSC00182.jpg"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="sImageClick"
      />
    </nuxt-link>
    <nuxt-link to="/daiya">
      <img
        src="https://www.petoffice.co.jp/_uploads/livingBody/190/0554%E3%83%88%E3%82%A4%E3%83%97%E3%83%BC%E2%99%82%E6%A8%AA.JPG"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="sImageClick"
      />
    </nuxt-link>
    <nuxt-link to="/master">
      <img
        src="https://pettimes.jp/wp-content/uploads/2019/05/yorkshire-terrier_feature-768x511.jpeg"
        alt="Mastery Guide Image"
        width="400"
        height="300"
        @click="sImageClick"
      />
    </nuxt-link>
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
