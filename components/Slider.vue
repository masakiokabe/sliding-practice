<template>
    <div>
        <div class="msg-container">
            <div class="slider" :class="[{button1:available1},{button2:available2},{button3:available3},{button4:available4},]">
                <div class="msg-col">
                    <h1>The Reasoning</h1>
                    <p>
                    If you're visiting this page, you're likely here because you're searching for a random sentence. Sometimes a random word just isn't enough, 
                    and that is where the random sentence generator comes into play. By inputting the desired number, you can make a list of as many random sentences 
                    as you want or need. 
                    </p>
                    <a>Learn More</a>
                </div>

                <div class="msg-col">
                    <h1>The Knowledge</h1>
                    <p>
                    But why smiling man her imagine married. Chiefly can man her out believe manners cottage colonel unknown.
                    Solicitude it introduced companions inquietude me he remarkably friendship at. My almost or horses period. 
                    Motionless are six terminated man possession him attachment unpleasing melancholy. 
                    Sir smile arose one share. No abroad in easily relied an whence lovers temper by. 
                    </p>
                    <a>Learn More</a>
                </div>

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
            </div>
        </div>

        <div class="controller">
            <div class="line1" @click="available1 =!available1"></div>
            <div class="line2" @click="available2 =!available2"></div>
            <div class="line3" @click="available3 =!available3"></div>
            <div class="line4" @click="available4 =!available4"></div>
            <div class="active"></div>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return{
            available1: true,
            available2: false,
            available3: false,
            available4: false,
            available5: false,

        }
    },
    methods:{
       
    }
}
</script>
<style scoped>
    .msg-container{
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

    .line1,.line2,.line3,.line4{
        height: 80px;
        width: 10px;
        cursor: pointer;
        transform: translateX(-50%);
        background: red;

    }

    #active{
        width: 5px;
        height: 80px;
        border-radius: 10px;
        background: #fff;
        position: absolute;
        top: 0;
        transform: translateX(-50%);
        
    }

    button1{
        transform: translateX(0);
    }
    button2{
        transform: translateX(-25%);
    }
    button3{
        transform: translateX(-50%);
    }
    button4{
        transform: translateX(-75%);
    }
    
</style>