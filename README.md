# CodeConfusion
代码混淆 demo

自己做的 demo ,是使用 swift 制作的,原理和 OC 语言的一样

(一)现在工程中建两个文件confuse.sh和func.list,第一个文件是用来放脚本,第二个文件是放需要加密的方法名字

(二)将confuse.sh的脚本填充好,直接复制就好

注意:脚本的路径一定要对,不对的话会出现两个错误,可以运行,但是最后是没有代码混淆的,如下图,是放置的位置

(四)最后在 func.list 中写入你需要混淆的方法,运行即可,第一次运行会自动生成一个文件codeObfuscation.h, 如果有对应的# define 生成,说明你已经成功了!
