# Examples for jQuery TextPosition

## 获取输入框选择范围

	$('#element').textposition();

返回内容：

	{
	    start: 0,
	    end: 2
	}

## 替换选中的文本为指定的内容

	$('#element').textposition('example text');

## 移动光标到指定位置

	$('#element').moveposition(0, 2);

## 选中指定范围的文本

	$('#element').moveposition(0, 2, true);

Visit [抚云生活](http://www.ifuyun.com/ "抚云生活") for more information.