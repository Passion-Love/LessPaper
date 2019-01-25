VGGNet

conv_op(input_op,name,kh,kw,n_out,dh,dw,p)
//创建卷积层，并将本层参数传入参数列表
//input_op是输入的tensor
//name这一层的名称
//kh,kw卷积核的高和宽
//n_out卷积核数量，即输出通道数
//dh,dw步长的高和宽
//p参数列表

get_shape()[-1].value
//获取输入input_op的通道数，比如输入图片的尺寸224x224x3中的3

tf.name_scope和tf.get_variable
//https://blog.csdn.net/heiheiya/article/details/81085297

tf.contrib.layers.xavier_initializer_conv2d()
//https://blog.csdn.net/yinruiyang94/article/details/78354257/

tf.nn.bias_add()
//conv加bias

fc_op
//全连接层创建函数

mpool_op
//最大池化层创建函数

inference_op
//VGGNet-16网络结构函数

keep_prob
//控制dropout比率的一个placeholder

x.get_shape()
//返回static shape，只有tensor有这个方法，返回是元组

tf.reshape()
//https://blog.csdn.net/sangreallilith/article/details/80285229

tf.nn.dropout
//https://blog.csdn.net/yangfengling1023/article/details/82911306

tf.nn.softmax
//https://blog.csdn.net/wgj99991111/article/details/83586508

tf.nn.argmax
//https://blog.csdn.net/uestc_c2_403/article/details/72232807

time_tensorflow_run
//评测函数

tf.global_variables_initializer()
//http://blog.sina.com.cn/s/blog_e504f4340102y8rk.html


