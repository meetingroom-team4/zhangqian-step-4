  step2-zhangqian


  遇到的问题：

1：提示zipcode2barcode不是一个函数
2：输入zipcode之后输出无数个barcode结果，而且没有输出菜单
3：发现输出两次结果


  解决办法：



1：引进的应该是core里的主函数
2：当respond.reset是true时，应该将item更新为最初始的item（originItem）
3：开始以为是代码中有问题，最后发现是因为有一个console.log