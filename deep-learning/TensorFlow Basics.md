## Tensor

## Operations
https://www.tensorflow.org/api_docs/python/tf/Operation

After the graph has been launched in a session, an Operation can be executed by passing it to tf.Session.run. op.run() is a shortcut for calling tf.get_default_session().run(op).
## Graph

## 其他
#### `tf.app`
- tf.app.run: http://blog.csdn.net/helei001/article/details/51859423

#### Variable 与get_variable
tf.Variable()每次都会创建新的对象，如果指定了相同的名称，tf会自动处理。而tf.get_variable在遇到相同名称的对象时会报错。如果指定了reuse为True, 则会返回已有的对象。
