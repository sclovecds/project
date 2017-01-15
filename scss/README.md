# scss文件夹
## plug文件夹-----存放插件scss源码
## public文件夹---存放网站公用的scss源码
### style.scss 整合所有零碎的scss文件

#### plug文件夹下各个文件详解
1. _flexSlider.scss
	* jquery支付宝官网首页左右全屏banner焦点图 样式文件文件
2. _pagination.scss 
	* bootstrap分页样式文件
3. _toolbar.scss
	* 右侧工具条样式
4. _iconfont.scss
	* 图标字体样式
5. _job.scss
	* _纯css响应时表格样式_
6. _backtotop.scss
	* 返回上一层样式
7. _np.scss
	* 通用上一篇下一篇样式
8. _position.scss
	* 通用面表屑导航基本样式
9. _message.scss
	* 通用表单样式

#### public文件夹下各个文件详解
1. _mixin.scss 
	* 自己写的函数可以通过 @include 调用
	* 在style.scss中必须导入这个文件，不然会导致其他的scss文件发生错误
2. _normalize.scss 
	* 重置浏览器样式
3. _public.scss
	* 自定定义的重置浏览器的样式
4. _var.scss
	* 存放变量的文件 
	* 必须导入到style.scss中
