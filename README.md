# AngularJS1
AngularJS1与AngularJS2区别很大，这里主要是介绍AngularJS1用法；
AngularJS主要应用于需要双向绑定数据，以下是hello word程序——AngularJS1简单应用：
当文本框输入值变化，显示立即变化(脏检查)
<!--
<!DOCTYPE html>
<html ng-app> 
<head>
<title>Simple app</title>
<script
src="https://ajax.googleapis.com/ajax/libs/angularjs/1.2.13/angular.js">
</script>
</head>
<body>
<input ng-model="name" type="text" placeholder="Your name">
<h1>Hello {{ name }}</h1>
</body>
</html>
-->
注：DOM元素上ng-app声明所有被它包含的元素都属于AngularJS应用;
DOM元素上使用ng-model="name"指令将内部数据模型对象($scope)中的name属性绑定到了文本输入字段上(数据模型对象是指$scope对象,$scope对象是一个简单的JavaScript对象，其中的属性可以被视图访问);
DOM元素上使用{{ name }}表达式来输出name值；
DOM元素上的ng-controller声明所有被它包含的元素都属于某个控制器；
MVC是手段，终极目的是模块化和复用；
