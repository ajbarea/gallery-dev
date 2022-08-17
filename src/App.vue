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
        { // alex
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/alex.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/alex-thumb.jpg?raw=true',
          width: 640,
          height: 480,
        },
        { // art
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/art.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/art-thumb.jpg?raw=true',
          width: 960,
          height: 960,
        },

        { // band
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band-thumb.jpg?raw=true',
          width: 640,
          height: 640,
        },
        { // band 1
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band1.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band1-thumb.jpg?raw=true',
          width: 600,
          height: 450,
        },
        { // band 2
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band2.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/band2-thumb.jpg?raw=true',
          width: 1106,
          height: 800,
        },
        { // blizzcon
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon-thumb.jpg?raw=true',
          width: 2048,
          height: 1152,
        },
        { // blizzcon1
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon1.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon1-thumb.jpg?raw=true',
          width: 1440,
          height: 2872,
        },
        { // brand new
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/brandnew.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/brandnew-thumb.jpg?raw=true',
          width: 960,
          height: 1280,
        },
        { // brooke
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/brooke.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/brooke-thumb.jpg?raw=true',
          width: 1536,
          height: 2048,
        },
        { // christina
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/christina.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/christina-thumb.jpg?raw=true',
          width: 480,
          height: 640,
        },
        { // con 2
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con2.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con2-thumb.jpg?raw=true',
          width: 1810,
          height: 1890,
        },
        { // con 3
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con3.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con3-thumb.jpg?raw=true',
          width: 1520,
          height: 1889,
        },
        { // con 4
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con4.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con4-thumb.jpg?raw=true',
          width: 1364,
          height: 1890,
        },
        { // con 5
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con5.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con5-thumb.jpg?raw=true',
          width: 1793,
          height: 1486,
        },
        { // con 6
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con6.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con6-thumb.jpg?raw=true',
          width: 1677,
          height: 1889,
        },
        { // con 7
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con7.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/con7-thumb.jpg?raw=true',
          width: 1810,
          height: 1490,
        },
        { // fabian
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fabian.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fabian-thumb.jpg?raw=true',
          width: 453,
          height: 301,
        },
        { // face1
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face1.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face1-thumb.jpg?raw=true',
          width: 720,
          height: 960,
        },
        { // face2
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face2.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face2-thumb.jpg?raw=true',
          width: 560,
          height: 960,
        },
        { // face3
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face3.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face3-thumb.jpg?raw=true',
          width: 720,
          height: 405,
        },
        { // face4
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face4.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/face4-thumb.jpg?raw=true',
          width: 768,
          height: 1024,
        },
        { // fam
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fam.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fam-thumb.jpg?raw=true',
          width: 720,
          height: 960,
        },
        { // fam2
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fam2.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/fam2-thumb.jpg?raw=true',
          width: 3088,
          height: 2320,
        },
        { // games
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/games.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/games-thumb.jpg?raw=true',
          width: 717,
          height: 960,
        },
        { // muzzies
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/muzzies.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/muzzies-thumb.jpg?raw=true',
          width: 960,
          height: 717,
        },
        { // tori
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/tori.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/tori-thumb.jpg?raw=true',
          width: 480,
          height: 640,
        },
        { // tori2
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/tori2.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/tori2-thumb.jpg?raw=true',
          width: 480,
          height: 640,
        },
        { // uncle
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/uncle.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/uncle-thumb.jpg?raw=true',
          width: 720,
          height: 960,
        },
        { // vote
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/vote-thumb.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/vote-thumb.jpg?raw=true',
          width: 540,
          height: 960,
        },
        { // vote1
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/vote1-thumb.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/vote1-thumb.jpg?raw=true',
          width: 895,
          height: 894,
        },
        /*
        { // 
          largeURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon.jpg?raw=true',
          thumbnailURL:
            'https://github.com/ajbarea/gallery-dev/blob/main/src/assets/photos/blizzcon-thumb.jpg?raw=true',
          width: 2048,
          height: 1152,
        },
        */
      ],
    };
  },
};
</script>
