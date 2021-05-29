<template>
   <div class="content">
       <div class="box-1">快帮网</div>
       <div class="box-2">干啥都行，干啥都快</div>
       <div class="box-3">
           <img src="./tubiao/手机@3x.png" class="ssr"/>
           <input type="text" class="ss" placeholder="手机号码"/>
       </div>
       <div class="box-4">
           <div class="s">
               <img src="./tubiao/duanxin.png" class="b">
               <input type="text" class="c" placeholder="短信验证码"/>
         </div>
         <div class="a">获取验证码</div>
     </div>
     <div class="box-5">登入</div>
     <div class="box-6">立即注册</div>
   </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.content{
  .box-1{
    margin-top: 87px;
    text-align: center;
    font-size: 24px;
    font-weight: 500;
    color: #ff552e;
    ien-height: 33px;
  }
  box-2{
      margin-top: 5px;
      text-alig: center;
      font-size: 16px;
      color: #ff552e;
      line-height:20px;
  }
  .box-3{
    margin: 29px auto;
    width: 82%;
    height: 44px;
    background: #e6e3e3;
    border-radius: 22px;
    border: 3px solid #eeeeee;
    display: flex;
    border: 3px solid #eeeeee;
    .ssr {
      width: 11px;
      teight: 17px;

      margin: auto 0 auto 27px
    }
    .ss {
      margin-left: 15px;
      font-size: 14px;
      color: #cccccc;
      border: 0; //去除未选中状态边框
      outline: none; //去除选中状态边框
      background-color: rgba(0,0,0,0,); //透明背景
    }
    .box-4{
      display: flex;
      width: 82%;
      margin: 19px auto;
      .s{
        width: 64%
        height: 44px;
        background: #e6e3e3;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        display:flex;

        .b{
          text-align: center;
          margin: auto 0 auto 21px;
          width: 16px;
          height: 14px;
        }
        .c{
          margin: auto 15px;
          width: 70px;
          height: 20px;
          font-size: 14px;
          color: #cccccc;
          line-height: 20px;
          border: 0; //去除未选中状态边框
          outline: none; //去除选中状态边框
          background-color: rgba(0,0,0,0,); //透明背景
        }
      }
      .a{
        width: 36%;
        height: 44px;
        background: #e6e3e3;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        font-size: 14px;
        text-align: center;
        color: #0e8ed8;
        line-height: 44px;
        margin-left: 15px;


      }

    }
  }

}
