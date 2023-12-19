<template>
  <div>
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>飼いやすい犬種！</title>
      <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    </head>
    <body class="text-center">
      <h1 style="font-weight: bold;">飼いやすいおすすめ犬種！</h1>

      <div class="container">
        <div class="row">
          <div v-for="(image, index) in images" :key="index" class="col-md-6 mb-3">
            <nuxt-link :to="image.link">
              <img
                :src="image.src"
                alt="Mastery Guide Image"
                class="img-fluid"
                @click="handleImageClick(image.link)"
              />
            </nuxt-link>
          </div>
        </div>
      </div>
    </body>
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: [
        {
          src: "https://1.bp.blogspot.com/-WPATRPUzFks/Ur1KwoeD4hI/AAAAAAAAELA/PgDgKwCxI50/s1600/0095-17.jpg",
          link: "/sibaken",
        },
        {
          src: "https://www.restonnow.com/files/2015/06/CustisDOG2-600x399.jpeg",
          link: "/bi-guru",
        },
        {
          src: "https://wanchan-life.com/wp-content/uploads/2019/08/IMG_3985.jpg",
          link: "/tiwawa",
        },
        {
          src: "https://www.moo-pon.com/main/wp-content/uploads/2017/06/DSC00182.jpg",
          link: "/dakkusu",
        },
        {
          src: "https://www.petoffice.co.jp/_uploads/livingBody/190/0554%E3%83%88%E3%82%A4%E3%83%97%E3%83%BC%E2%99%82%E6%A8%AA.JPG",
          link: "/toipu-doru",
        },
        {
          src: "https://pettimes.jp/wp-content/uploads/2019/05/yorkshire-terrier_feature-768x511.jpeg",
          link: "/yo-kusha-",
        },
      ],
    };
  },
  methods: {
    handleImageClick(link) {
      this.$router.push(link);
    },
  },
};
</script>
