# Javascript
# Javascript学习资料以及电子书还有经验和学习笔记实例代码

# <a href="https://segmentfault.com/a/1190000022866321">JavaScript 中 15 种常见的数组操作</a>
# <a href="https://juejin.cn/post/6844903616512278536">JS创建对象的几种方法</a>
# <a href="https://blog.csdn.net/u011280778/article/details/99711988">javascript中对一个对象数组按照对象某个属性进行排序</a>
# <a href="https://www.w3school.com.cn/js/js_special_characters.asp">JavaScript 特殊字符</a>
# <a href="https://juejin.cn/post/6844903881172877320">JS函数中参数的传递方式</a>
# <a href="https://www.cnblogs.com/yugege/p/5539020.html">浅谈JavaScript函数重载</a>
# <a href="https://juejin.cn/post/6844903636154187790">JavaScript中的函数重载（Function overloading）</a>
# <a href="https://blog.csdn.net/guoxiaozhuang4/article/details/80253772">JS重写Object的toString()方法</a>
# <a href="https://www.jianshu.com/p/45cd21aae931">优化Visual Studio Code的自动补全</a>

# js中有趣的Infinity
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<body>
		<script type="text/javascript">
			//1.infinity是值正的无穷大，属于Number类型，-infinity是值负的无穷大
			var res=1/0;//其他语言中0不能转为除数，但是js可以。
			document.write("1/0="+res+"<br/>");//1/0=Infinity
			//2.一个数字除以一个Infinity，结果是0
			var res2=10000/res;
			document.write("10000/Infinity="+res2+"<br/>");//10000/Infinity=0
			//3.Infinity乘于-1等于-Infinity
			var res3=res*(-1);
			document.write("Infinity*(-1)="+res3+"<br/>");//Infinity*(-1)=-Infinity
			//4.Infinity/Infinity=NaN无穷大除以无穷大得到的是NaN
			document.write("Infinity/Infinity="+Infinity/Infinity+"<br/>");//Infinity/Infinity=NaN
		    //5.Infinity/-1=-Infinity
			document.write("Infinity/-1="+Infinity/-1+"<br/>");//Infinity/-1=-Infinity
			//6.Infinity/-Infinity=NaN
			document.write("Infinity/-Infinity="+Infinity/-Infinity+"<br/>");//NaN
			//7.Infinity-Infinity=NaN
			var r=Infinity-Infinity;
			document.write("Infinity-Infinity="+r+"<br/>");
			//8.Infinity+Infinity=Infinity
			var r2=Infinity+Infinity;
			document.write("Infinity+Infinity="+r2+"<br/>");//=Infinity
			//9.Infinity*Infinity=Infinity
			var r3=Infinity*Infinity;
			document.write("Infinity*Infinity="+r3+"<br/>");//=Infinity
		</script>
	</body>
</html>
