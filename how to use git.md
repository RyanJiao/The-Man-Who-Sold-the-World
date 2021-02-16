- #### 普通更新

  ```c
  git add  XXX.txt
  
  git commit -m "whatever you want to say."
  
  git status //optional check
  
  git push origin master
  ```



- #### 回档

  ​	重置工作区

  ```c
   git checkout -- readme.txt
  ```

  ​	重置暂存区

  ```c
    git reset HEAD readme.txt
  ```

  ​	回到特定版本

  ```c
    git log --pretty=oneline  //显示所有commit id
    git reflog   //显示所有操作  
    git reset --hard HEAD~100  //回到一百次存档之前
    git reset --hard 1094a    //回到指定的commit id
  ```

  

- #### 取消同步

  ```
   git checkout -- readme.txt
  ```

  

​	

- #### 查看区别

  ```
  git diff HEAD -- readme.txt
  ```

  

- #### 分支操作

  ```c
  git branch  //查看分支
  git branch <name>  //创建分支
  git checkout <name>   //切换分支
  git switch <name>  //切换分支
  git checkout -b <name>   //创建并切换分支
  git switch -c <name>     //创建并切换分支
  git merge <name>   //合并某分支到当前分支
  git branch -d <name>   //删除分支
  ```

  

  