<template>
  <div class="tabbable" style="width:230px;height:265px" >
    <ul class="nav nav-tabs padding-12 tab-color-blue background-blue">
      <li>
        <a data-toggle="tab" href="#basicInformation">基本信息</a>
      </li>
      <li class="active">
        <a data-toggle="tab" href="#watchInformation">监测信息</a>
      </li>
    </ul>
    <div class="tab-content" style="padding:5px 0px 0px 0px " >
      <div id="basicInformation" class="tab-pane" style="overflow:scroll;max-height:215px;">
        <table class="table table-striped table-bordered table-hover">
          <thead >
          <tr>
            <th>
            测站名称
            </th>
            <th>
            大浦口
            </th>
          </tr>
          </thead>
        <tbody >
          <tr>
            <td class="">测站编码</td>
            <td>
              20000011
            </td>
          </tr>
          <tr>
            <td class="">测站类别</td>
            <td>
              水质站
            </td>
          </tr>
        <tr>
          <td class="">监测方式</td>
          <td>
            人工
          </td>
        </tr>
        <tr>
          <td class="">采集频率</td>
          <td>
            一月一次
          </td>
        </tr>
        <tr>
          <td class="">所属湖区</td>
          <td>
            #
          </td>
        </tr>
        </tbody>
        </table>
      </div>

    <div id="watchInformation" class="tab-pane in active" style="overflow: auto;max-height:215px">
    <table class="table table-striped table-bordered table-hover" >
    <thead class="thin-border-bottom">
    <tr>
    <th>
    检测项目
    </th>
    <th>
    测量值
    </th>
    </tr>
    </thead>
    <tbody style="overflow: scroll">
      <tr>
    <td class="">水色</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">透明度</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">水温</td>
    <td>
    <a href="#">12</a>
    </td>
    </tr>
    <tr>
    <td class="">溶解氧</td>
    <td>
    <a href="#">6.5</a>
    </td>
    </tr>
    <tr>
    <td class="">电导率</td>
    <td>
    <a href="#">IV</a>
    </td>
    </tr>
    <tr>
    <td class="">pH</td>
    <td>
    <a href="#">7.89</a>
    </td>
    </tr>
    <tr>
    <td class="">高锰酸盐指数</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">化学需氧量</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">氨氮</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">蓝藻</td>
    <td>
    <a href="#">12</a>
    </td>
    </tr>
    <tr>
    <td class="">总氮</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">总磷</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    <tr>
    <td class="">溶解性总磷</td>
    <td>
    <a href="#"></a>
    </td>
    </tr>
    </tbody>
    </table>
    </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'lzcontent',
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
