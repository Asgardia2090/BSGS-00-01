# BSGS-00-01
everyone hold together for  common dream,better and better.
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<style type="text/css">
			*{
				margin:0
			}
			form{
				width: 300px;
				height: 400px;
				border: 1px solid green;
				margin: 0 auto;
				line-height: 40px;
				background: pink;
				margin: 300px 800px;
				text-align: center;
				
			}
		</style>
	</head>
	<body>
		<form action="index.html" method="post" enctype="multipart/form-data">
			<p>用户名<input type="text" name="uname" placeholder="数字下划线字母组成" required="required"</p>
			<p>密码<input type="password" name="upassword" maxlength="8" placeholder="请输入8位密码"</p>
			<p>性别<input type="radio" name="sex" value="女"/>女
			     <input type="radio" name="sex" value="男"/>男
			</p>
			<p>爱好<input type="checkbox" name="hoppy" value="唱"/>唱
			<input type="checkbox" name="hoppy" value="跳"/>跳
			<input type="checkbox" name="hoppy" value="说"/>说
			<input type="checkbox" name="hoppy" value="篮球"/>篮球
			</p>
			<p>国籍
			      <select name="coutry" required="required">
			      	<option>请选择</option>
					<option>美国</option>
					<option>日本</option>
					<option>中国</option>
					<option>中国台湾</option>
			      </select>
			</p>	  
			 <p>
				 邮箱<input type="email" name="email" id="" value="" />@qq.com
			 </p>
			 <p>自我介绍<textarea  name="introduce" ></textarea></p>
			 <p><input type="file" name="pictrue" id="" value="" /></p>
			 <p><input type="submit" name="" id="" value="注册" /></p>
			  
		</form>
	</body>
</html>
