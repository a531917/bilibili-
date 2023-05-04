<template>
    <div id="video-mg">
        <router-link to='/play'>
            <div class="cover-mg">
                <img src="../img/video-cover2.png" alt="">
                <div class="video-data">
                    <div class="data">
                        <span class="iconfont icon-bofangliang"> {{
                            v.bofangliang}}</span>
                        <span class="iconfont icon-danmu"> {{v.bofangliang}}</span>
                    </div>
                    <div class="time">
                        <span>7.23</span>
                    </div>
                </div>
            </div>
            <div class="title">
                <p>曾经我也想过一了百了--中岛美嘉</p>
            </div>
            <div class="up">
                <i class="iconfont icon-UPzhu"> stefxmc</i>
                <i class="iconfont icon-gengduo"></i>
            </div>
        </router-link>
    </div>
</template>

<script>
    
</script>

<style scoped>
    #video-mg{
        width: 48%;
        height: auto;
        margin: 5px;
        border-radius: 5px;
        background: white;
        padding: 5px;
    }
    .cover-mg{
        position: relative;
    }
    img{
        width:100%;
        height: auto;
    }
    .video-data{
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
        background-image: linear-gradient(rgba(0,0,0,0),rgba(0,0,0,1));
        height:50px;
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
    }
    .data{
        display: flex;
        align-items: flex-end;
    }
    span{
        margin: 5px;
        color: white;
        font-size: 13px;
    }
    .up{
        display: flex;
        justify-content: space-between;
        color: #999;
    }
</style>

<script>
export default {

}
</script>