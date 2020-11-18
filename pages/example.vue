<template>
  <hooper>
    <slide>
      slide 11111
    </slide>
    <slide>
      slide 22222
    </slide>
    <slide>
      slide 33333
    </slide>
    <slide>
      slide 44444
    </slide>
    <slide>
      slide 55555
    </slide>
    <slide>
      slide 6666
    </slide>
    ...
    <hooper-pagination slot="hooper-addons"></hooper-pagination>
    <hooper-pagination slot="hooper-addons"></hooper-pagination>
    <hooper-pagination slot="hooper-addons"></hooper-pagination>
  </hooper>
</template>

<script>
import 'hooper/dist/hooper.css';
import {
  Hooper,
  Slide,
  Pagination as HooperPagination
  } from 'hooper';

export default {
  layout: 'none',  
  name: 'App',
  components: {
    Hooper,
    Slide,
    HooperPagination
  }
};
</script>