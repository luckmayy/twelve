<template>
	<div class="list">
		<el-container>
				<!--这是头部--> 
				<el-header style="height: 150px;">
					<img src="../assets/img/图片1.png" style="float: left;width: 200px;height: 150px;margin: 0px 0px 0px 150px;">
				</el-header>
				<!-- <el-main >
					<div style="height: 300px;width: 1200px;">
						<img alt="龙腾升学欢迎您！" src="../assets/img/学校图片.jpg" style="height: 300px;width: 1200px;">
					</div>
				</el-main> -->
				<div style="height: 400px;width: 1760px;">
						<img title="龙腾升学欢迎您！" src="../assets/img/学校图片.jpg" style="height: 400px;width: 1760px;">
					</div>
			<div class="module" style="margin: 0px 70px;">

				<el-container style="height: 400px;">
					<el-aside style="width:500px;height: 350px;margin: 30px ;" >
						<div class="module-aside">	
							<el-card class="box-card" shadow="always">
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">升学实验班：在龙腾，有名师，做塑造人的教育</span>			
								</div>	
								<div class="text item"  style="position: relative;right: 20px;">
									<div class="block" style="margin-top: 0px;">
										<el-timeline :reverse="reverse">
											<el-timeline-item
											v-for="(activity1, index) in activities1"
											:key="index">
											{{activity1.content1}}
											</el-timeline-item>
										</el-timeline>
										
									</div>
									
								</div>
							</el-card>	
						</div>
					</el-aside>
					<el-aside style="width:500px;" class="aside">
						<div class="module-aside">	
							<el-card class="box-card" shadow="always">
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">黑龙江高考优势</span>			
								</div>	
								<div class="text item"  style="position: relative;right: 20px;">
									<div class="block" style="margin-top: 0px;">
										<el-timeline :reverse="reverse">
											<el-timeline-item
											v-for="(activity2, index) in activities2"
											:key="index">
											{{activity2.content2}}
											</el-timeline-item>
										</el-timeline>
										
									</div>
									
								</div>
							</el-card>	
						</div>
					</el-aside>
					<el-aside style="width:500px;" class="aside">
						<div class="module-aside">	
							<el-card class="box-card" shadow="always">
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">黑龙江高考优势2</span>			
								</div>	
								<div class="text item"  style="position: relative;right: 20px;">
									<div class="block" style="margin-top: 0px;">
										<el-timeline :reverse="reverse">
											<el-timeline-item
											v-for="(activity2, index) in activities2"
											:key="index">
											{{activity2.content2}}
											</el-timeline-item>
										</el-timeline>
										
									</div>
									
								</div>
							</el-card>	
						</div>
					</el-aside>
				</el-container>

				<el-container>
					<el-aside style="width:500px;" class="aside">
						<div class="module-aside">					
							<el-card class="box-card" shadow="always">								
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">各省高考基本情况</span>			
								</div>
								<div class="text item" >
										<el-link href="static/青海高考基本情况概述.docx" type="primary">黑龙江高考基本情况概述</el-link>									
								</div>
								<div class="text item"><el-link type="primary">青海高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">吉林高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">陕西高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">天津高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">新疆高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">辽宁高考基本情况概述</el-link></div>
							</el-card>
						</div>
					</el-aside>
					<el-aside style="width:500px;" class="aside">
						<!-- <div class="module-name"><p style="position: relative; bottom: 90px;"></p></div> -->
						<div class="module-aside">					
							<el-card class="box-card" shadow="always">								
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">郑州民办高中基本情况</span>			
								</div>
								<div class="text item"><el-link type="primary">郑州外国语新枫杨学校</el-link></div>
								<div class="text item"><el-link type="primary">郑州市明新中学</el-link></div>
								<div class="text item"><el-link type="primary">郑州华夏中学</el-link></div>
								<div class="text item"><el-link type="primary">郑州创新学校</el-link></div>
								<div class="text item"><el-link type="primary">郑州市陇海中学</el-link></div>
								<div class="text item"><el-link type="primary">郑州一八联合国际学校</el-link></div>

							</el-card>
						</div>
					</el-aside>

					<el-aside style="width:500px;" class="aside">
						<!-- <div class="module-name"><p style="position: relative; bottom: 90px;"></p></div> -->
						<div class="module-aside">					
							<el-card class="box-card" shadow="always">								
								<div slot="header" class="clearfix">
									<span style="font-size: 20px;">各省高考基本情况</span>			
								</div>
								<div class="text item"><el-link type="primary">陕西高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">天津高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">新疆高考基本情况概述</el-link></div>
								<div class="text item"><el-link type="primary">辽宁高考基本情况概述</el-link></div>
							</el-card>
						</div>
					</el-aside>
				</el-container>


				
			</div>
		</el-container>

		<el-container>
				<el-footer>Footer</el-footer>
		</el-container>
		
	</div>
    
</template>

<script>

export default {
	data () {
		return {
			url1:'../assets/file/青海高考基本情况概述.docx',
			reverse: true,
        activities1: [{
          content1:'360°贴心服务,家长安心无忧',
        }, {
          content1:'国内领先的五维一体高效课堂, 小班制教授课程',
        }, {
          content1:'避开五五分流,正常办理学籍户籍,升学无忧有保障',   
        },{
		  content1:'学生可以同时享受优质教育资源和高考优惠政策',
		},{
		  content1:'激情教育系列:梦想激发课堂、激情早读、激情跑操'
		}
		],
		activities2: [{
          content2:'由于地域参加高考人数少',
        }, {
          content2:'具有普通高校81所,四所211高校',   
        },{
		  content2:'招生计划多，录取比例高,录取分数低',
		},{
		  content2:'高考题目难度低,容易拿高分',
		},{
		  content2:'国家政策支持,手续简单,合法合规'
		}
		],

	      }
      },
	  methods: {
		handDownload(url1)
		{
		
			console.log(url1, '下载文件事件')
      // 创建 a 标签
      const a = document.createElement('a')
      // 创建一个点击事件
      const event = new MouseEvent('click')
      // 将 a 的 download 属性设置为我们想要下载的图片的名称，若 name 不存在则使用'图片'作为默认名称
      a.download = url1.name || '青海高考基本情况概述.docx'
      // 将生成的 url 设置为 a.href 属性 （file.downloadUrl 属性也是一个链接，是一个自定义的链接）
      a.href = url1.downloadUrl
      // 打开新的窗口（如果是一个图片类型的文件，在浏览器打开新的标签页打开）
      a.target = '_blank'
      // 实现触发生成的 a 标签
      a.dispatchEvent(event)

		},  
}

}

</script>

<style>
.el-link.el-link--primary{
	font-size: 20px;
	line-height: 40px;
}
 .el-carousel__item h3 {
    color: #475669;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
  }
  
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
  .block{
	margin-top: 30px;
  }
  .el-menu--horizontal>.el-menu-item{
	font-size: 20px;
  }
  .el-menu--horizontal>.el-submenu .el-submenu__title{
	font-size: 20px;
  }
  .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
	height: 400px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }
  
  .aside{
	height: 400px;
	margin: 30px 20px;
  }
  .list{
	box-sizing: border-box;
  }
  .module-name{
	width:	450px;
	height: 50px;
	border: 1px solid green;
	margin: 0px 0px 0px 25px;
  }
 .module-aside{

	width: 490px;
	height: 330px;
	margin: 0px 0px 0px 5px;
 }
 .el-timeline-item__content{
	float: left;
	font-size: 17px;
	line-height: 20px;
 }
 .el-timeline-item{
	padding-bottom: 35px !important;
 }
 
  
</style>