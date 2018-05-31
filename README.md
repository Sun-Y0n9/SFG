+ git status
+ git add
+ git commit -m "提交信息"
+ git diff
+ 版本退回
    * git reset
    * git reset --hard HEAD^ 上一个版本
    * git reset --hard HEAD^^ 上上一个版本
    * git reset --hard HEAD~100 上100个版本
    * git reset --hard 29d7q 回到版本号为的29d7q版本
+ git log 查看提交信息 用于回退到以前版本的版本号查看
+ git reflog 查看所有提交信息 用于返回到最新版本的版本号查看
+ Git tracks changes of files.
+ git checkout -- README.md 撤销工作区的中的修改 当前修改的文件
+ git checkout b1 切换到b1分支
+ git reset HEAD file.ext 撤销暂存区的修改; 撤销git add 的操作
+ 测试 2
+ git re file.ext 确认删除一个文件
+ git checkout -- test.txt 将暂存区的文件覆盖掉工作区的文件,也就是撤销工作区中的修改,极端情况,删除了工作区的文件,可使用版本库里的文件找回;