参考： [Vim按键映射高级技巧](https://zhuanlan.zhihu.com/p/38150203)
-------------------------------------------------------------------

```vim

[nore]map [<args>] {lhs} {rhs}

" {lhs}: 按键队列 -- 用户输入的字符队列, 表示映射前的按键序列
" {rhs}: 字符队列 -- 表示映射后的按键序列, 不一定是Vim最终要处理的字符队列, 比如是递归命令时，可能会再次被解释

举例:

inoremap <silent><expr> <c-space> coc#refresh()    

" <c-space> 按键 会调用 coc#refresh() 函数 
" <expr> 表示{rhs}是一个Vim表达式, 或者1个函数调用

```
