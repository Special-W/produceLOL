<template>
    <div>
      <div class="msg_hot">
        <div class="msg_left">
          <p>OMG.xiyang迎来自己LPL赛场的第300场比赛</p>
          <span class="msg_left_time">
            2018-9-18
          </span>
          <span class="msg_left_num">
            1.7万阅读量
          </span>
        </div>
        <div class="msg_right">
          <img src="../../assets/img/team_a1.png" alt="">
        </div>
      </div>
      <div class="msg_hot">
        <div class="msg_left">
          <p>Smlz赛后与xiyang聚餐 与老队友感情依旧</p>
          <span class="msg_left_time">
            2018-9-18
          </span>
          <span class="msg_left_num">
            1.7万阅读量
          </span>
        </div>
        <div class="msg_right">
          <img src="../../assets/img/team_a3.png" alt="">
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "MemberNews"
    }
</script>

<style scoped>
  .msg_hot {
    height: 93px;
    width: 100%;
    border-top: 1px solid #dedede;
    padding-top: 15px;
    margin: 0 auto;
  }
  .msg_hot .msg_right img {
    width: 102px;
    height: 76px;
  }
  .msg_hot .msg_right {
    float: right;
    margin-right: 3%;
  }
  .msg_hot .msg_left {
    width: 60%;
    float: left;
    margin-left: 3%;
  }
  .msg_hot .msg_left p {
    width: 90%;
    font-size: 14px;
    height: 48px;
    line-height: 24px;
    overflow: hidden;
    margin: 0;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
    margin-bottom: 5px;
    margin-left: 3%;
  }
  .msg_hot .msg_left span {
    font-size: 12px;
    color: #AAAAAA;
  }
  .msg_hot .msg_left .msg_left_time {
    float: left;
    margin-top: 3px;
    margin-left: 5%;
  }
  .msg_hot .msg_left .msg_left_num {
    margin-left: 5%;
    float: left;
    margin-top: 1px;
  }
</style>
