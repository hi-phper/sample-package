## ����

����һ���򵥵�Composer��ʾ����

ֻ��һ��HiPhper\SamplePackage\Sample��, һ������sayHello()��

## ��װ

	composer require hi-phper/sample-package
	
	
## ʹ��ʾ��

	require './vendor/autoload.php';

	use HiPhper\SamplePackage\Sample;

	$sample = new Sample();
	echo $sample->sayHello();