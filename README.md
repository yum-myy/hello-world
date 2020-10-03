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
  
  




<head>
    <meta charset="UTF-8">
    <title>Table</title>
    <style type="text/css">
        table,tr,td{
            border:1px solid #000;
            border-collapse: collapse;
        }
        caption{
            font-weight:bold;
      }
    </style>
</head>
<body>
<table>
    <caption>各地区资产投资情况</caption>
    <thead>
       <tr>
           <td rowspan="2">地区</td>
           <td colspan="2">按总量分</td>
           <td colspan="2">按比重分</td>
       </tr>
       <!-- 第二行还是表头，放在表格主题部分会出错，要注意！！！   -->
       <tr>
           <td>自年初累计（亿元）</td>
           <td>比去年同期增长（%）</td>
           <td>自年初累计（%）</td>
           <td>去年同期（%）</td>
       </tr>
    </thead>
    <tbody>
        <tr>
            <td>全国</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
        </tr>
        <tr><td>东部地区</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
            <td>8</td></tr>
        <tr><td>北京市</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td></tr>
        <tr><td>天津市</td>
            <td>13</td>
            <td>14</td>
            <td>15</td>
            <td>16</td></tr>
        <tr><td>河北省</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td></tr>
    </tbody>
</table>
</body>
  
  
  
  
  
