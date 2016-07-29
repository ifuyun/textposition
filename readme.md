# Examples for jQuery TextPosition

## 获取输入框选择范围

```js
	$('#element').textposition();
```

返回内容：

```js
	{
	    start: 0,
	    end: 2
	}
```

## 替换选中的文本为指定的内容

```js
	$('#element').textposition('example text');
```

## 移动光标到指定位置

```js
	$('#element').moveposition(0, 2);
```

## 选中指定范围的文本

```js
	$('#element').moveposition(0, 2, true);
```

Visit [抚云生活](http://www.ifuyun.com/ "抚云生活") for more information.
