<template>
  <SimpleGallery galleryID="my-test-gallery" :images="images" />
</template>

<script>
import SimpleGallery from './SimpleGallery.vue';

export default {
  name: 'App',
  components: {
    SimpleGallery,
  },
  data() {
    return {
      images: [
        {
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/alex.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/alex-thumb.jpg?raw=true',
          width: 640,
          height: 480,
        },
        {
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/art.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/art-thumb.jpg?raw=true',
          width: 960,
          height: 960,
        },
        {
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon-thumb.jpg?raw=true',
          width: 2048,
          height: 1152,
        },
        {
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band-thumb.jpg?raw=true',
          width: 640,
          height: 640,
        },
      ],
    };
  },
};
</script>
