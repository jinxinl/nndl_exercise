# CNN_tensorflow 遇到的问题及解决方法

- 版本问题，我使用的是 `teansorflow 2.5.1` ，而作业中的 `tensorflow` 版本是 `1.x` ，两个版本的库和函数略有不同
  - `No module named ‘tensorflow.examples `报错
  - `module ‘tensorflow‘ has no attribute ‘placeholder` 报错
  - `AttributeError: module ‘tensorflow‘ has no attribute ‘truncated_normal‘` 报错
  - `ValueError: Shape must be rank 1 but is rank 0 for ‘batch_normalization_1/cond/Reshape_4‘ (op: ‘Resh` 报错
  - `TypeError: conv2d_v2() got an unexpected keyword argument 'filter'` 报错，类似的有 `TypeError: max_pool_v2() got an unexpected keyword argument 'value'` 报错，`TypeError: reduce_sum() got an unexpected keyword argument 'reduction_indices'` 报错，
  - `AttributeError: module 'tensorflow' has no attribute 'log'` 报错
  - `AttributeError: module 'tensorflow._api.v2.train' has no attribute 'AdamOptimizer'` 报错
  - `TypeError: minimize() missing 1 required positional argument: 'var_list'` bao'c

