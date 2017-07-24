# pikaday
pikaday时间插件
#### 直接在网页中打开index.html就可以查看效果
##### 在自己的项目中引入时间插件
  * 引入css、js    <link rel="stylesheet" type="text/css" href="css/pikaday.css"/>
                  <script type="text/javascript" src="js/pikaday.min.js"></script>
  * 需要调用时间插件的dom标签 <input type="text" id="datepicker" />
  * 在javascript中调用这个时间插件
      <script type="text/javascript">

      var picker = new Pikaday(
      {
          field: document.getElementById('datepicker'),
          firstDay: 1,
          minDate: new Date('2010-01-01'),
          maxDate: new Date('2020-12-31'),
          yearRange: [2000,2020] //设置你的时间年份的范围
      });

  </script>
