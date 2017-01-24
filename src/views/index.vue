<style scoped lang="less">
    .win-wrapper{
        width:100%;
        height:100%;
        background: url("../images/banner.png") center top no-repeat ;
        overflow: hidden;
    }

    .w-top{
        width:100%;
        position: relative;
    }
    .w-top .top-sc{
        width:100%;
        height:auto;
        position: absolute;
        left:0;
        top:0;
        z-index:2;
        -webkit-animation-delay:.5s;
        -webkit-animation-duration: 3s;
    }

    .w-top .top-logo{
        width:328px;
        height:309px;
        position: absolute;
        left:293px;
        top:0;
        z-index:1;
        -webkit-animation-delay:.5s;
        -webkit-animation-duration: 3s;
    }


    .bottom-scr{
        width:100%;
        height:auto;
        position: absolute;
        bottom:0;
        left:0;
        z-index:1;
        -webkit-animation-delay:1s;
        -webkit-animation-duration: 1.5s;
    }

    .bottom-presentG{
        width:100%;
        height:auto;
        position: absolute;
        bottom:0;
        left:0;
        z-index:3;
        -webkit-animation-delay:1.3s;
        -webkit-animation-duration: 2s;
    }

    .bottom-2017{
        width:248px;
        height:auto;
        position: absolute;
        left:0;
        right:0;
        bottom:0;
        margin:auto;
        z-index:2;
        -webkit-animation-delay:1.3s;
        -webkit-animation-duration: 2s;
    }


    .win-goods{
        width:292px;
        height:292px;
        position: absolute;
        left:293px;
        top:502px;

    }

    .win-goods .imgBox{
        width:100%;
        height:100%;
        position: relative;

    }

    .win-goods .imgBox .goodsImg{
        width:50%;
        height:50%;
        margin-top:25%;
        margin-left:25%;

        object-fit: cover;
        position: relative;

    }

    .win-goods .imgBox::before{
        content: '';
        position: absolute;
        left:0;
        top:0;
        width:100%;
        height:100%;
        background: url("../images/products-bg.png") no-repeat 100% /cover;
        z-index:0;
    }

    .win-goods .imgBox::after{
        content: '';
        position: absolute;
        left:0;
        top:0;
        width:100%;
        height:100%;
        background: url("../images/products-glass.png") no-repeat 100% /cover;
        z-index:2;
    }

    .machine{
        width:569px;
        height:341px;
        background: url("../images/cjj-bgbox.png") no-repeat 100% /cover;
        position: absolute;
        top:0;
        left:0;
        bottom:0;
        right:0;
        margin:auto;

    }

    .machineBox{
        width:100%;
        height:100%;
        position: relative;
    }

    .machineBox .hand{
        position: absolute;
        right:-55px;
        top:40px;
        width:68px;
        height:242px;
        background: url("../images/cjj-down.png") left center no-repeat;
        background-size:auto 100%;


    }

    .light{
        width:528px;
        height:232px;
        position: absolute;
        left:0;
        top:40px;




        bottom:0;
        right:0;
        margin:0 auto;

    }

    .shinning_1{
        background: url("../images/light-01.png")  no-repeat 100% /cover;
    }

    .shinning_2{
        background: url("../images/light-02.png")  no-repeat 100% /cover;
    }

    .runHand{
        -webkit-animation:run 1.5s steps(8) alternate;
    }

    .numberBox{
        width: 477px;
        height:170px;
        background: url("../images/cjj-bgboxyellow.png") no-repeat 100% /cover;
        position: absolute;
        left:0;
        right:0;
        top:65px;
        bottom:0;
        margin:0 auto;
    }

    .numberBox ul{
        width:100%;
        height:100%;
        display: -webkit-flex;
        flex-direction:row;
        justify-content: center;
        align-items: center;

    }


    .numberBox ul li{
        width:102px;
        height:134px;
        margin:0 7px;
        overflow: hidden;
        position: relative;
    }

    .numberBox ul li .bck{
        position: absolute;
        left:0;
        top:-134px;
        width:100%;
        height:100000px;
        background: url("../images/cjj-z.png") repeat-y;
        background-size:100% auto;
    }
    
    .roll{
        -webkit-transition: all 1s;
        -moz-transition: all 1s;
        -ms-transition: all 1s;
        -o-transition: all 1s;
        transition: all 1s;
    }

    .cjj-star{
        position: absolute;
        left:50%;
        bottom:0;
        transform: translateX(-50%);
        cursor: pointer;
        width:266px;
        height:117px;

    }

    .circle{
        width: 410px;
        height:389px;
        position: absolute;
        left:50%;
        bottom:-60px;
        -webkit-transform: translateX(-50%);
        -moz-transform: translateX(-50%);
        -ms-transform: translateX(-50%);
        -o-transform: translateX(-50%);
        transform: translateX(-50%);

        z-index:2;
    }
    
    .circle .content{
        position: relative;
        width:100%;
        height:100%;
    }

    .circle .content .outer{
        position: absolute;
        left:0;
        top:0;
        width:100%;
        height: 100%;
        background: url("../images/cjj-gobg.png") no-repeat 100%/cover;
        z-index:8;
    }

    .circle .content .inner{
        position: absolute;
        left:0;
        top:0;
        width:100%;
        height: 100%;
        bottom:0;
        right: 0;
        margin:auto;
        background: url("../images/cjj-gomain.png") no-repeat 100%/cover;
        z-index:8;
        -webkit-transition: all .7s linear;
        -moz-transition: all .7s linear;
        -ms-transition: all .7s linear;
        -o-transition: all .7s linear;
        transition: all .7s linear;
        transform-origin: center center;
    }

    .circle .content .turnRotate{
        position: absolute;
        left:0;
        top:0;
        width:100%;
        height: 100%;
        background: url("../images/cjj-go.png") no-repeat 100%/cover;
        z-index:999;
        cursor: pointer;
    }

    .star_1{
        background: url("../images/cjj-star01.png") no-repeat 100%/cover;
    }

    .star_2{
        background: url("../images/cjj-star02.png") no-repeat 100%/cover;
    }

    .winnerList{
        width:304px;
        height:520px;
        background: url("../images/list-bg.png") no-repeat 100%/cover;
        position: absolute;
        right:249px;
        top:401px;
    }

    .winnerList .list{
        width:200px;
        height:324px;
        padding:10px 15px;
        background: -webkit-linear-gradient(top,#faf8c4,#e8c792);
        margin-top:94%;
        margin-left:50%;
        -webkit-transform: translateX(-50%) translateY(-50%);
        -moz-transform: translateX(-50%) translateY(-50%);
        -ms-transform: translateX(-50%) translateY(-50%);
        -o-transform: translateX(-50%) translateY(-50%);
        transform: translateX(-50%) translateY(-50%);
        border-radius:10px;
        -webkit-box-shadow: inset 0 1px  5px 2px #000;
        -moz-box-shadow: inset 0 1px  5px 2px #000;
        box-shadow: inset 0 1px  5px 2px #000;
        overflow-x: hidden;
        overflow-y: scroll;
    }

    .winnerList .list span{
        display: inline-block;
        width:50%;
        line-height:25px;
        color: #000;
        font-size:17px;
        font-family:'Microsoft YaHei UI Light';
        font-weight: bold;

    }

    .winnerList .list span:nth-child(odd){
        text-align: left;
    }
    .winnerList .list span:nth-child(even){
            text-align: right;
        }

    ::-webkit-scrollbar
    {
        width: 5px;
        height: 5px;
    }
    ::-webkit-scrollbar-track-piece
    {
        background-color: #ffffff;
        -webkit-border-radius: 6px;
    }
    ::-webkit-scrollbar-thumb:vertical
    {
        height: 5px;
        background-color: rgba(222,222,222,.7);
        -webkit-border-radius: 15px;
    }
    ::-webkit-scrollbar-thumb:horizontal
    {
        width: 5px;
        background-color: #e3e3e3;
        -webkit-border-radius: 6px;
    }

    @keyframes run {
        0%{background-position:0 0}
        100%{background-position:-544px 0}
    }

</style>
<template>
    <div class="win-wrapper">
        <div class="w-top" >
            <img src="../images/top-sc.png"  class="top-sc animated" v-show="expand"   transition="expand">
            <img src="../images/top-logo.png" class="top-logo animated" v-show="expand" transition="top"/>
        </div>

        <img src="../images/bottom-scr.png" class="bottom-scr animated" v-show="expand" transition="trans"/>
        <img src="../images/bottom-PresentG.png" class="bottom-presentG animated" v-show="expand" transition="trans"/>
        <img src="../images/bottom-2017.png" class="bottom-2017 animated" v-show="expand" transition="rotate"/>
        <div class="win-goods">
            <div class="imgBox"><img :src="currentImg"  v-show="showNumber" transition="transInDown" class="goodsImg animated"></div>
        </div>
        <div class="machine animated" v-show="expand" transition="swing">
            <div class="machineBox">
                <div :class="['hand',play?'':'runHand']"></div>
                <div :class=['light',shinning?'shinning_1':'shinning_2'] ></div>
                <div class="numberBox">
                    <ul>
                        <li  :class="[roll?'roll':'']" >
                            <div class="bck" :style="{top:number_1+'px'}"></div>
                        </li>
                        <li :class="[roll?'roll':'']">
                            <div class="bck" :style="{top:number_2+'px'}"></div>
                        </li>
                        <li :class="[roll?'roll':'']">
                            <div class="bck" :style="{top:number_3+'px'}"></div>
                        </li>
                        <li :class="[roll?'roll':'']">
                            <div class="bck" :style="{top:number_4+'px'}"></div>
                        </li>
                    </ul>
                </div>
                <div :class="['cjj-star',play?'star_1':'star_2']" @click="begin()"></div>
            </div>
        </div>
        <div class="circle animated"  v-show="expand" transition="fade">
            <div class="content">
                <p class="outer " ></p>
                <p class="turnRotate" @click="level==0?level=5:level--"></p>
                <p class="inner"   :style="rotateStyle"></p>
            </div>
        </div>
        <div class="winnerList animated" v-show="expand" transition="bounce">
            <div class="list"  >
                <span v-for="item in numArr" track-by="$index" class="animated" v-show="showNumber" transition="fade">{{item.number}}{{item.name}}</span>
            </div>
        </div>
    </div>
</template>
<script>
    import TWEEN from 'tween.js'
    export default {
        data () {
            return {
                expand:false, //初始动画


                shinning:false, //彩灯
                play:true, //是否允许点击
                number_1:0,
                number_2:0,
                number_3:0,
                number_4:0,
                currentImg:'https://img.alicdn.com/imgextra/i2/2692579223/TB28ey8aM0kpuFjSspdXXX4YXXa_!!2692579223.png',
                imgArr:['https://img.alicdn.com/imgextra/i2/2692579223/TB2tYe_aNXlpuFjSsphXXbJOXXa_!!2692579223.png','https://img.alicdn.com/imgextra/i2/2692579223/TB2tYe_aNXlpuFjSsphXXbJOXXa_!!2692579223.png','https://img.alicdn.com/imgextra/i3/2692579223/TB2HNjPa4hmpuFjSZFyXXcLdFXa_!!2692579223.png','https://img.alicdn.com/imgextra/i1/2692579223/TB2Z5zMa.lnpuFjSZFjXXXTaVXa_!!2692579223.png','https://img.alicdn.com/imgextra/i1/2692579223/TB2tBTKa9VmpuFjSZFFXXcZApXa_!!2692579223.png','https://img.alicdn.com/imgextra/i2/2692579223/TB28ey8aM0kpuFjSspdXXX4YXXa_!!2692579223.png'],
                numArr:[], //中奖名单
                nameArr:[],//中奖人名
                level:5, //当前奖品等级
                winCount:38, //中奖次数
                showNumber:false, //更新中奖名单
                rotateStyle:{
                    webkitTransform:'rotate(0deg)'
                },
                testArr:[], //当次抽奖号码集合
            }
        },
        watch:{
            level(val){
                this.showNumber=false;

                this.numArr.splice(0, this.numArr.length);

                this.currentImg=this.imgArr[val];

                this.rotateStyle.webkitTransform='rotate('+(val-5)*60+'deg)';

                switch(val){
                    case 5:
                        this.winCount=30;
                        break;
                    case 4:
                        this.winCount=20;
                        break;
                    case 3:
                        this.winCount=10;
                        break;
                    case 2:
                        this.winCount=5;
                        break;
                    case 1:
                        this.winCount=2;
                        break;
                    case 0:
                        this.winCount=100000;
                        break;
                }

                this.$nextTick(()=>{
                    this.showNumber=true;
                })
            }
        },
        ready () {

            let self=this;

            this.expand=true;

            this.showNumber=true;

            setInterval(()=>{self.shinning=!self.shinning},500)

        },
        methods: {
            //递归显示抽奖号码
            tween(num,count){

                let vm = this;
                console.log(num.number);
                let numArr=[...(!isNaN(num.number)?num.number+'':num.number)];


                numArr.forEach((item,index)=>{


                   let tween= new TWEEN.Tween({ tweeningNumber: 0})
                            .easing(TWEEN.Easing.Quadratic.Out)
                            .to({ tweeningNumber:(parseInt(item))*-134-6700 }, 500*(index+1))
                            .onUpdate(function(){vm['number_'+(index+1)]= this.tweeningNumber.toFixed(0);})
                            .start();

                    if(numArr.length==index+1) {

                        tween.onComplete(()=>{

                            this.numArr.push(num);

                            this.winCount--;

                            if(--count<1){

                                this.play=true;
                                this.level=this.winCount<0?this.level-1:this.level;
                                return false;

                            }else{

                                this.$nextTick(()=>{return this.tween(this.testArr[count-1],count)})

                            }
                        });
                    }
                });

                this.animate();


            },
            //滚动
            animate (time=Date().now) {

                requestAnimationFrame(this.animate)
                TWEEN.update(time)

            },
            //柯里
            curring(m){

               return this.tween(this.testArr[m-1],m);

            },
            //抽奖开始
            begin(){

              if(this.play)  {

                  this.play=false;

                  this.$http.post(
                          'http://year.haowaichangsha.com/Index/draw',{type:this.level},
                          { "Access-Control-Allow-Origin":'*',"Access-Control-Allow-Headers":'Origin, X-Requested-With, Content-Type, Accept'})
                          .then((res)=>{
                              if(res.ok){
                                  return res.body
                              }

                          })
                          .then((resovle)=>{

                              if(resovle.content.length<1){this.play=true;return false;}

                              let length=this.testArr.length;

                              this.testArr.splice(0,length);

                              let multiArr=[];

                              resovle.content.forEach((item,i)=>{
                                  let obj={};
                                  obj.number=item;
                                  obj.name=resovle.name[i];
                                  multiArr.push(obj);
                              })

                              this.testArr.push(...multiArr);

                              this.$nextTick(()=>{ this.curring(this.testArr.length);})

                          })
                          .catch((reject)=>{

                            this.level--;
                            this.play=true;

                          })
                  }
            }
        },

        transitions:{
            'expand':{
                enterClass:'slideInDown',
                leaveClass:'hinge'
            },
            'top':{
                enterClass:'bounceInDown',
                leaveClass:'bounceInUp'
            },
            'bounce':{
                enterClass:'bounceInDown',
                leaveClass:'bounceInUp'
            },
            'trans':{
                enterClass:'fadeInUp',
                leaveClass:'bounceInDown'
            },
            'transInDown':{
                enterClass:'zoomIn',
                leaveClass:'bounceInDown'
            },
            'rotate':{
                enterClass:'rotateIn',
                leaveClass:'rotateOut'
            },
            'fade':{
                enterClass:'fadeInRight',
                leaveClass:'fadeOutLeft'
            },
            'swing':{
                enterClass:'swing',
                leaveClass:'fadeOut'
            }
        }
    }
</script>
