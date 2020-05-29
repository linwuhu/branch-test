"# branch-test" 


V1.0.x 分支创建 


分支修改

## 分支

1、创建分支并跳转到该分支

        git checkout -b 分支名 
        相当于
        git branch 分支名        创建
        git checkout 分支名      跳转 

2、分支打tag

        git tag    查看tag列表
        git tag -a tag名 -m "tag描述"
        git push origin tag名 （tag 是一种特殊的分支？）

3、分支合并

        git merge 分支名 （指定分支名合并到现在所在的分支）

4、分支删除
        本地删除
        git branch -d 分支名
        
        远程删除
        git push origin -d 分支名 
        git push origin :分支名