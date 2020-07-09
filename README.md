# git 命令

## 分支

1、创建分支并跳转到该分支

        git checkout -b 分支名 
        相当于
        git branch 分支名        创建分支
        git checkout 分支名      跳转分支
2、查看分支

		本地
		git branch 
		远程
		git branch -r 


3、分支合并

        git merge 分支名 （指定分支名合并到现在所在的分支）

4、分支删除

        本地删除
        git branch -d 分支名
        
        远程删除
        git push origin -d 分支名 
        git push origin :分支名

5、 分支修改
        先修改本地分支名称，后提交至远程
        git branch -m oldName newName    
          -(odlName改为newName)
	
5、分支提交
		
	git push origin 分支名

-------------

