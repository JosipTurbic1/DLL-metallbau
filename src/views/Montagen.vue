<template>
  <section>
    <h2>Montagen</h2>
    <LightBox
      :thumbnails="lightbox.images.thumbnails"
      :largeImages="lightbox.images.large"
      :thumbnailsPath="lightbox.thumbnailsPath"
      :largePath="lightbox.largePath"
      :captions="lightbox.captions"
      class="lightBox"
    />
    <hr>
  </section>
</template>

<script>
import LightBox from "@/components/LightBox.vue";

export default {
  name: "app",
  data() {
    return {
      lightbox: {
        images: {
          thumbnails: ["1.jpeg", "2.jpeg", "3.jpeg", "4.jpeg", "5.jpeg", "6.jpeg"],
          large: ["1.jpeg", "2.jpeg", "3.jpeg", "4.jpeg", "5.jpeg", "6.jpeg"]
        },
        captions: [],
        thumbnailsPath: "/img/sea/thumbnails/MO/",
        largePath: "/img/sea/large/MO/"
      }
    };
  },
  components: {
    LightBox
  }
};
</script>

<style lang ="scss">
.light-box {
  &__thumbnail {
    margin: 20px;
    width: 200px;
  }
}
img {
  max-width: 100%;
}
</style>