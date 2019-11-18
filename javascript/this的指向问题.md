
# this的指向问题
>this是一个对象，但是我们不同的操作 this指向的对象是不相同的。

## 三种 this指向情况：
1. 对象调用，this 指向该对象（前边谁调用 this 就指向谁）

2. 直接调用的函数，this 指向的是全局 window 对象

3. 通过 new 的方式，this 永远被绑定在新创建的对象上，任何方式都改变不了 this 的指向

> new的过程，其实在内部创建了一个空对象，然后将构造函数传入的参数和属性挂在了这个空对象上，然后返回了这个对象。

## 扩展：箭头函数的 this 指向谁？

```
const obj ={
    a:()=>{
        console.log(this)
    }
}
```

>运行程序，控制台输出：

![](https://user-gold-cdn.xitu.io/2019/11/14/16e6758e10fbf72e?imageView2/0/w/1280/h/960/format/webp/ignore-error/1)

>我们可以得出结论，this在箭头函数中失效了，因为这是由于箭头函数没有单独的 this值。
>
>箭头函数的 this与声明所在的上下文相同。
>
>也就是说调用箭头函数的时候，不会隐式的调用 this参数，而是从定义时的函数继承上下文。


# 如何改变 this 的值？

1. call 方法

2. apply 方法

3. bind 方法