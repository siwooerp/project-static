# project-static
此文档是内部插件文档，详细说明所有内部插件的功能使用方法



> plugin目录 PC端用插件
>   1.  [日期时间选择插件](#plugin-date-picker)
>   1.  [下拉框选择插件](#plugin-form-select)
>
> popup 手机端用插件


### plugin-date-picker
>   日期时间选择插件

* 文件调用
   > css文件：http://ruhnnstatic.oss-cn-hangzhou.aliyuncs.com/plugin/plugin-date-picker/jquery.datetimepick.css

   > js文件：http://ruhnnstatic.oss-cn-hangzhou.aliyuncs.com/plugin/plugin-date-picker/jquery.datetimepick.full.js
 
* 例子代码：
```html
<input type="text" data-module="date"></input>
// 自动加载 日期        
<input type="text" data-module="datetime"></input>
// 自动加载 日期+时间
<input type="text" data-module="time"></input>
// 自动加载 时间
```
### plugin-form-select
>   表单下拉框格式化

* 文件调用
   > css文件：需要common-pc.css支持

   > js文件：http://ruhnnstatic.oss-cn-hangzhou.aliyuncs.com/plugin/plugin-form/form.js
 
* 例子代码：
```javascript
$('select').selectPicker();
$('select').selectPicker({
    fieldValue:[option的value字段名],
    fieldName: [option的text字段名],
    fieldQuery:[模糊查询的请求字段名],
    url:[模糊查询url],
    data:[模糊查询额外请求数据]
});
```



