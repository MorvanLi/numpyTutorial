# numpyTutorial

- [创建和生成](https://github.com/MorvanLi/numpyTutorial/blob/main/np1_%E5%88%9B%E5%BB%BA%E5%92%8C%E7%94%9F%E6%88%90.ipynb)
  - np.linspace(start, end, nums)
  - rng.integers/uniform(low, high, size)
  - rng.normal(loc, scale, size)
- [统计和属性](https://github.com/MorvanLi/numpyTutorial/blob/main/np2_%E7%BB%9F%E8%AE%A1%E5%92%8C%E5%B1%9E%E6%80%A7.ipynb)
  - arr.shape
  -  arr.sum/max/min(axis, keepdims)
  - np.average(arr, axis)
- [形状和转换](https://github.com/MorvanLi/numpyTutorial/blob/main/np3_%E5%BD%A2%E7%8A%B6%E5%92%8C%E8%BD%AC%E6%8D%A2.ipynb)
  - arr.reshpae/np.reshape
  - np.expand_dims(arr, axis)
  - np.squeeze(arr axis)
  - np.transpose(arr, axis)
  - arr.T
- [分解和组合](https://github.com/MorvanLi/numpyTutorial/blob/main/np4_%E5%88%86%E8%A7%A3%E5%92%8C%E7%BB%84%E5%90%88.ipynb)
  - arr[start:stop:step, ...]
  - np.concatenate((arr1, arr2), axis)
  - np.stack((arr1, arr2), axis)
  - np.repeat(arr, repeat_num, axis)
  - np.split(arr, part_num, axis)
- [筛选和过滤](https://github.com/MorvanLi/numpyTutorial/blob/main/np5_%E7%AD%9B%E9%80%89%E5%92%8C%E8%BF%87%E6%BB%A4.ipynb)
  - np.where(condition, arr, replaced_val)
  - rng.choice(a, size, replace=False, p=probs_size_equals_a)
  - rng.argmax/argmin/argsort(arr, axis)
- [矩阵和计算](https://github.com/MorvanLi/numpyTutorial/blob/main/np6_%E7%9F%A9%E9%98%B5%E5%92%8C%E8%AE%A1%E7%AE%97.ipynb)
  - +-*/
  - np.dot(a, b) == a.dot(b)
  - np.matmul(a, b) == a @ b

​	[numpy实现反向传播](https://github.com/MorvanLi/numpyTutorial/blob/main/demo.ipynb)