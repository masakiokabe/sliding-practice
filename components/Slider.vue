<template>
  <hooper class="hooper">
    <slide>
        <div class="msg-col">
            <h1>The Reasoning</h1>
            　<p>
                If you're visiting this page, you're likely here because you're searching for a random sentence. Sometimes a random word just isn't enough,
                and that is where the random sentence generator comes into play. By inputting the desired number, you can make a list of as many random sentences
                as you want or need.
            </p>
            <a>Learn More</a>
        </div>
    </slide>
    <slide>
        <div class="msg-col">
            <h1>The Knowledge</h1>
            <p>
            But why smiling man her imagine married. Chiefly can man her out believe manners cottage colonel unknown.
            Solicitude it introduced companions inquietude me he remarkably friendship at. My almost or horses period.
            No abroad in easily relied an whence lovers temper by. 
            </p>
            <a>Learn More</a>
        </div>
    </slide>
    <slide>
        <div class="msg-col">
            <h1>The Integration</h1>
            <p>
            Did shy say mention enabled through elderly improve. As at so believe account evening behaved hearted is.
            House is tiled we aware.
            It ye greatest removing concerns an overcame appetite. Manner result square father boy behind its his.
            Their above spoke match ye mr right oh as first.
            </p>
            <a>Learn More</a>
            </div>
    </slide>
    <slide>
        <div class="msg-col">
        <h1>The Learning</h1>
        <p>
        New had happen unable uneasy. Drawings can followed improved out sociable not.
        Earnestly so do instantly pretended. See general few civilly amiable pleased account carried.
        Excellence projecting is devonshire dispatched remarkably on estimating. Side in so life past.
        Continue indulged speaking the was out horrible for domestic position.
        </p>
        <a>Learn More</a>
        </div>
    </slide>
    <!--<hooper-navigation slot="hooper-addons"></hooper-navigation>-->
    <hooper-pagination slot="hooper-addons"></hooper-pagination>
   </hooper>
</template>

<script>
import 'hooper/dist/hooper.css';
import {
  Hooper,
  Slide,
  Pagination as HooperPagination,
  Navigation as HooperNavigation
  } from 'hooper';

export default {
  components: {
    Hooper,
    Slide,
    HooperPagination,
    HooperNavigation
  }
};
</script>
<style scoped lang="css">

.hooper{
width: 600px;
height: 280px;
position: absolute;
left: 14%;
top: 57%;
transform: translateY(-50%);
overflow: hidden;
}

.slider{
display: inline-flex;
}

.msg-col{
width: 600px;
}

.msg-col h1{
color: #fff;
font-size: 80px;
font-weight: 100;
margin: 10px 0;

}
.msg-col p{
color: #ddd;
font-size:15px;
line-height: 25px;
}

.msg-col a {
display: inline-block;
text-decoration: none;
color: #555;
background: #fff;
font-size:15px;
padding: 10px 35px;
border-radius: 30px;
margin-top: 25px;
position: relative;
bottom: 20px;
}

.controller{
width: 1px;
height: 320px;
display: block;
background: #c0c0c0;
position: absolute;
top: 55%;
right: 50px;
transform: translateY(-50%);
}


</style>