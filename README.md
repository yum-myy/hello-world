# My Notes

<img src="" alt="The picture is missing" width="" height="">
<a href="" target="_blank" tittle="鼠标悬停出现的内容">跳转到...</a>


<a href="#tiaozhuan1">页面内跳转...</a>
<h3 id="tiaozhuan1">页面内跳转...</h3>
<!-- 13页(13.htm)跳转到12页(12.htm)指定的位置:格式为:（要跳转页面的文件名#id属性名） -->
<p>
  <a href="12.htm">人物介绍</a>
  <a href="12.htm#tiaozhuan1">早年经历</a>
  <a href="12.htm"tiaozhuan1>演艺经历</a>
</p>



<head>
  <style type="txet/css">
    P{
       font-size:20px;
       color:#000;
    }
    span{
          /* 设置文字特殊样式 */
          color:red;
    }
  </style>
</head>

<!-- div+css头部/内容/底部 -->
<div calss="header">1</div>
<div calss="content">2</div>
<div calss="footer">3</div>

<style type="text/css">
  /* 清除默认样式 */
  .*{
      padding:0px;
      margin:0px;
  }
  /* 无序列表前面没有小圆点(有序换成ol即可) */
  ul{
     list-style:none;
  }
  table,tr,td,th{
     /* 制作单线表格 */
     border-collapse:collapse;
  }
  .header{
          width:100%;
          height:200px;
          background-color:#eee;
  }  
  .content{
          width:100%;
          height:500px;
          background-color:#eee;
          margin-top:30px;
  }  
   .footer{
          width:100%;
          height:200px;
          background-color:#eee;
          margin-top:30px;
  }  
  
  
  
  
  
  
  
  
