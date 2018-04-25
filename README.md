# Array_max_min
Array maxValue and minValue

	var arr = [1, 2, 3, 4, 5, 6];
	// 计算数组的最大值 
	var max = Math.max.apply(null, arr);
	var min = Math.min.apply(null, arr);
	console.log('最大值' + max);
	document.writeln('最大值' + max);

	console.log('最小值' + min);
	document.writeln('最小值' + min);

	var arr1 = [ 1, 2, 3];
	var arr2 = [ 4, 5, 6];
	// 数组合并
	Array.prototype.push.apply( arr1, arr2);
	console.log(arr1);
	document.write(arr1);
