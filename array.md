### 字符串中每个字符重复的次数
	var info = arr
	    .split('')
	    .reduce((p, k) => (p[k]++ || (p[k] = 1), p), {});
