## plug文件夹
### 存放的是常用jQuery 插件目录
1. jquery.flexslider-min.js
	* jquery支付宝官网首页左右全屏banner焦点图
	* 配套scss目录-- scss->plug->flexSlider.scss
	* 配套图片目录--images->flexSliderImg
	* html 调用方法
		* 在phpstorm中（我已配置好代码块）输入flexslider之后按tab键就行
		* 其他编辑器
			```
				<div class="flexslider">
					<ul class="slides">
						<li style="background:url(images/flexSliderImg/img1.jpg) 50% 0 no-repeat;"></li>
						<li style="background:url(images/flexSliderImg/img2.jpg) 50% 0 no-repeat;"></li>
						<li style="background:url(images/flexSliderImg/img3.jpg) 50% 0 no-repeat;"></li>
						<li style="background:url(images/flexSliderImg/img4.jpg) 50% 0 no-repeat;"></li>
						<li style="background:url(images/flexSliderImg/img5.jpg) 50% 0 no-repeat;"></li>
					</ul>
				</div>
				<script src="js/jquery.flexslider-min.js" ></script>
				<script>
					$(function(){
						$('.flexslider').flexslider({
							directionNav: true,
							pauseOnAction: false
						});
					});
				</script>
			```
