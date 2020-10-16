# Python 语法、案例

## [可变参数]（./programs/variable_parameter.py）

如果函数具体有多少个参数是由调用者来决定，在不确定参数个数的时候，我们可以使用可变参数

## 默认变量名

    # __name__是Python中一个隐含的变量它代表了模块的名字
    # 只有被Python解释器直接执行的模块的名字才是__main__
    if __name__ == '__main__':
        print('call foo()')
        foo()
        print('call bar()')
        bar()

代码的规范书写：

    def main():
        # Todo: Add your code here
        pass


    if __name__ == '__main__':
        main()