<script>
import image from "@/assets/img/cookie.png";
export default {
  data: function () {
    return {
      image: image,
    };
  },
};
</script>

<template>
  <div class="cookie-fofo">
    <img class="image" :src="image" />
  </div>
</template>
<style>
.image {
  max-width: 100%;
  height: 400px;
  object-fit: contain;
}

.cookie-fofo {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 10%;
}
</style>
