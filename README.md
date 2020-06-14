## 介绍

这是一个简单的Composer包示例。

只有一个HiPhper\SamplePackage\Sample类, 一个方法sayHello()。

## 安装

	composer require hi-phper/sample-package
	
	
## 使用示例

	require './vendor/autoload.php';

	use HiPhper\SamplePackage\Sample;

	$sample = new Sample();
	echo $sample->sayHello();