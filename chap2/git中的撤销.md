
##  修改最后一次提交

有时候发现几个文件忘记加了，或者提交信息写错了，可以使用`--amend`修改提交

```cpp
$ git commit -m 'initial commit'
    $ git add forgotten_file
    $ git commit --amend
```

上面的三条命令最终只是产生一个提交，第二个提交命令修正了第一个的提交内容。


## 取消暂存
`git restore --staged {文件名}`  可以取消暂存

![[Pasted image 20221017233323.png]]

## 撤销暂存区的修改
`git restore {文件名}` 撤销对暂存区的修改

![[Pasted image 20221017233624.png]]