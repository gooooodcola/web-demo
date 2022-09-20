<!DOCTYPE html>
<html lang="en">

<head>
	<!-- 这里是对开头的相关定义 -->
    <meta charset="UTF-8">
	<!-- 告诉浏览器用什么格式进行编码 -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
	<!-- 无需考虑网页是否兼容IE8浏览器，只要确保网页在edge下的表现就可以了 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!-- width - viewport的宽度 height - viewport的高度，initial-scale - 初始的缩放比例-->
    <title>Document</title>
	<!-- Document 对象使我们可以从脚本（JavaScript）中对 HTML 页面中的所有元素进行访问。 -->
</head>

<body>
    <table align="center" border="1" height="600px" width="325px" cellspacing="0">
		<!-- align属性规定单元格中内容的水平对齐方式。 -->
		<!-- border设置边框 -->
		<!-- cellspacing单元格之间的间隙 px为像素 -->
        <tr align="center">
            <td width="80" colspan="8">信息统计表</td>
		<!-- colspan="8" 指示浏览器横跨到列组的第8列。 -->
        </tr>
        <tr align="center">
            <td width="80">姓名</td>
            <td width="80" colspan="6">
                <input type="text">
				<!-- 可以在其中输入文档 -->
            </td>
        </tr>
        <tr align="center">
            <td width="80">年龄</td>
            <td width="80" colspan="6">
                <input type="text">
            </td>
        </tr>
        <tr align="center">
            <td width="80">性别</td>
            <td width="80" colspan="6">
                <label><input type="radio" name="sex" value="男">男</label>
                <label><input type="radio" name="sex" value="女">女</label>
            </td>
        </tr>
        <tr align="center">
            <td width="60">爱好</td>
			   <td align="left" width="60" colspan="6">
                <label><input type="checkbox" name="like" value="0">旅游<br /></label>
                <label><input type="checkbox" name="like" value="0">登山<br /></label>
                <label><input type="checkbox" name="like" value="0">健身<br /></label>
                <label><input type="checkbox" name="like" value="0">上网<br /></label>
                <label><input type="checkbox" name="like" value="0">游泳<br /></label>
            </td>
        </tr>
        <tr align="center">
            <td width="80">学历</td>
            <td width="80" colspan="6">
                <select>
                    <option value="">本科</option>
                    <option value="">专科</option>
                    <option value="">研究生</option>
                </select>
            </td>
        </tr>
        <tr align="center">
            <td width="80">自我 介绍</td>
            <td width="80" colspan="6">
                <textarea name="textarea" cols="25" rows="2" style="resize:none;"></textarea>
            </td>
        </tr>
        <tr align="center">
            <td width="80"></td>
            <td width="80" colspan="6">
                <input type="submit" value="提交">
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
				<!-- 不换行空格 -->
                <input type="reset" value="重置">
            </td>
        </tr>
    </table>
</body>

</html>