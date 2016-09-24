
plugin-form-select
=======
>   表单下拉框格式化

* 文件调用
   > css文件：需要common-pc.css支持

   > js文件：http://ruhnnstatic.oss-cn-hangzhou.aliyuncs.com/plugin/plugin-form/form.js
 
* 例子代码：
```javascript
// TODO:傅将华补充
$('select').selectPicker();
$('select').selectPicker({
    fieldValue:[option的value字段名],
    fieldName: [option的text字段名],
    fieldQuery:[模糊查询的请求字段名],
    url:[模糊查询url],
    data:[模糊查询额外请求数据]
});
```
