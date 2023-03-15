<template>
  <img :src="imageLink" class="w-8 h-8 object-contain rounded-3xl" />
</template>

<script>
export default {
  name: "ProfileImage",
  data() {
    return {
      imageLink:
        "https://64.media.tumblr.com/5db4bb32db099ddafc2c0c2050518f23/0f9237626e1f76b9-71/s1280x1920/934731ba2cfe575741ce84b79f2e1b1d2edf55c0.jpg",
    };
  },
};
</script>
