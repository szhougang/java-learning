### ArrayList 扩容原理


#### List扩容实现步骤
总的来说就是分两步：
* 1、扩容：把原来的数组复制到另一个内存空间更大的数组中
* 2、添加元素：把新元素添加到扩容以后的数组中




在无参构造中，我们看到了在用无参构造来创建对象的时候其实就是创建了一个空数组，长度为0

在有参构造中，传入的参数是正整数就按照传入的参数来确定创建数组的大小，否则异常

在添加的时候远数组是空的，就直接给一个10的长度，否则的话就加一

每次扩容是原来长度的1.5倍









