<template>
  <div class="tabbable" style="width:260px;height:265px" >
    <ul class="nav nav-tabs padding-12 tab-color-blue background-blue">
      <li>
        <a data-toggle="tab" href="#basicInformation">基本信息</a>
      </li>
      <li class="active">
        <a data-toggle="tab" href="#watchInformation">视频信息</a>
      </li>
    </ul>
    <div class="tab-content" style="padding:5px 0px 0px 0px " >
      <div id="basicInformation" class="tab-pane" style="overflow:scroll;max-height:215px;">
        <table class="table table-striped table-bordered table-hover">
          <thead >
            <tr><td>站名</td><td>大浦口</td></tr>
            <tr><td>站码</td><td>20000011</td></tr>
            <tr><td>经度</td><td>119°95′21″</td></tr>
            <tr><td>纬度</td><td>31°30′96″</td></tr>
          <tr>
            <th>
            建站时间
            </th>
            <th>
            2011年6月
            </th>
          </tr>
          </thead>
        <tbody >
          <tr>
            <td class="">建站单位</td>
            <td>
              水利部太湖流域管理局
            </td>
          </tr>
          <tr>
            <td class="">描述</td>
            <td>
              供电方式采用太阳能浮充供电，通信方式通过3G（CDMA2000）双卡无线传输
            </td>
          </tr>
        </tbody>
        </table>
      </div>

    <div id="watchInformation" class="tab-pane in active" style="overflow: auto;max-height:215px">
      <img src="/src/assets/thlz.jpg">
    </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'lzcontent',
  props: ['echarts'],
  data:function(){
      return {
      }
  },
  created:function(){
    //alert('1');
  },
  methods:{
    }
}

</script>

<style>

</style>
