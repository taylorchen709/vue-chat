<template>
    <section class="chatlist">
        <ul>
            <li class="chat-mine">
                <div class="chat-user"><img src="../assets/user.png"></div>
                <div class="time"><cite><i>2016-11-15 22:01:17</i>游客</cite></div>
                <div class="chat-text">212121212</div>
            </li>
            <li>
                <div class="chat-user"><img src="../assets/default.png"></div>
                <div class="time"><cite>客服MM<i>2016-11-15 22:01:17</i></cite></div>
                <div class="chat-text">城区朝秦暮楚朝秦暮楚fda城区朝秦暮楚朝秦暮楚fda</div>
            </li>
            <li class="chat-mine">
                <div class="chat-user"><img src="../assets/user.png"></div>
                <div class="time"><cite><i>2016-11-15 22:01:17</i>游客</cite></div>
                <div class="chat-text">212121212</div>
            </li>
            <li>
                <div class="chat-user"><img src="../assets/default.png"></div>
                <div class="time"><cite>客服MM<i>2016-11-15 22:01:17</i></cite></div>
                <div class="chat-text">城区朝秦暮楚朝秦暮楚fda城区朝秦暮楚朝秦暮楚fda</div>
            </li>
            <li class="chat-mine">
                <div class="chat-user"><img src="../assets/user.png"></div>
                <div class="time"><cite><i>2016-11-15 22:01:17</i>游客</cite></div>
                <div class="chat-text">212121212</div>
            </li>
            <li>
                <div class="chat-user"><img src="../assets/default.png"></div>
                <div class="time"><cite>客服MM<i>2016-11-15 22:01:17</i></cite></div>
                <div class="chat-text">城区朝秦暮楚朝秦暮楚fda城区朝秦暮楚朝秦暮楚fda</div>
            </li>
            <li class="chat-mine">
                <div class="chat-user"><img src="../assets/user.png"></div>
                <div class="time"><cite><i>2016-11-15 22:01:17</i>游客</cite></div>
                <div class="chat-text">212121212</div>
            </li>
            <li>
                <div class="chat-user"><img src="../assets/default.png"></div>
                <div class="time"><cite>客服MM<i>2016-11-15 22:01:17</i></cite></div>
                <div class="chat-text">城区朝秦暮楚朝秦暮楚fda城区朝秦暮楚朝秦暮楚fda</div>
            </li>
            <li class="chat-mine">
                <div class="chat-user"><img src="../assets/user.png"></div>
                <div class="time"><cite><i>2016-11-15 22:01:17</i>游客</cite></div>
                <div class="chat-text">212121212</div>
            </li>
            <li>
                <div class="chat-user"><img src="../assets/default.png"></div>
                <div class="time"><cite>客服MM<i>2016-11-15 22:01:17</i></cite></div>
                <div class="chat-text">城区朝秦暮楚朝秦暮楚fda城区朝秦暮楚朝秦暮楚fda</div>
            </li>
        </ul>
    </section>
</template>

<script>
export default {
  name: 'chatlist',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .chatlist {
        position: absolute;
        top: 60px;
        bottom: 48px;
        left: 0px;
        right: 0px;
        overflow-y: scroll;
        overflow-x: hidden;
        padding: 10px;
    }
    
    .chatlist ul .chat-mine {
        text-align: right;
        padding-left: 0;
        padding-right: 60px;
    }
    
    .chatlist ul li {
        position: relative;
        /*font-size: 0;*/
        margin-bottom: 10px;
        padding-left: 60px;
        min-height: 68px;
    }
    
    .chat-mine .chat-user {
        left: auto;
        right: 3px;
    }
    
    .chat-user {
        position: absolute;
        left: 3px;
    }
    
    .chat-text,
    .chat-user {
        display: inline-block;
        vertical-align: top;
        /*font-size: 14px;*/
    }
    
    .chat-user img {
        width: 40px;
        height: 40px;
        border-radius: 100%;
    }
    
    .time {
        width: 100%;
    }
    
    cite {
        left: auto;
        right: 60px;
        text-align: right;
    }
    
    cite {
        font-style: normal;
        line-height: 24px;
        font-size: 12px;
        white-space: nowrap;
        color: #999;
        text-align: left;
    }
    
    cite i {
        font-style: normal;
        padding-left: 5px;
        padding-right: 5px;
        font-size: 12px;
    }
    
    .chat-mine .chat-text {
        margin-left: 0;
        text-align: left;
        background-color: #33DF83;
        color: #fff;
    }
    
    .chat-text {
        position: relative;
        line-height: 22px;
        /*margin-top: 25px;*/
        padding: 10px 15px;
        background-color: #eee;
        border-radius: 3px;
        color: #333;
        word-break: break-all;
        max-width: 462px\9;
    }
    
    .chat-text,
    .chat-user {
        display: inline-block;
        vertical-align: top;
        font-size: 14px;
    }
    
    .chat-text img {
        max-width: 100%;
        vertical-align: middle;
    }
    
    .chat-user {
        position: absolute;
        left: 3px;
    }
    
    .chat-text:after {
        content: '';
        position: absolute;
        left: -10px;
        top: 15px;
        width: 0;
        height: 0;
        border-style: solid dashed dashed;
        border-color: #eee transparent transparent;
        overflow: hidden;
        border-width: 10px;
    }
    
    .chat-mine .chat-text:after {
        left: auto;
        right: -10px;
        border-top-color: #33DF83;
    }
</style>