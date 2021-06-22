
git使用说明
账号
282596268@qq.com


一.出现错误OpenSSL SSL_read: Connection was reset, errno 10054
git config --global http.sslVerify "false"


取消全局代理：
git config --global --unset http.proxy
 
git config --global --unset https.proxy

git config --global http.postBuffer 524288000


Windows用户：cmd命令窗口执行：

ipconfig /flushdns



一.本地更新到远程库


  100  git init
  101  ls
  102  git add ./* -f
  103  git commit -m "ssmProject - 第4周添加功能完成"
  104  git remote add origin https://github.com/zhengleiqing/ssmProject.git
  105  git push -u origin master

二.从远程拉下来

git pull  https://github.com/zhengleiqing/ssmProject.git



git init 作用是什么要理解
git add 
git remote add origin <URL>
git push 
git pull
git merge
git checkout 
git branch
0.启动



1.把本地的所有文件更新传上去

添加文件，

git add ./* -f 

2.把本地的某个文件传上去



3.把远程的所有文件更新拉下来




4.把远程的某个文件更新拉下来


5.删除本地某个文件




6.删除本地所有文件



7.删除远程 某个文件




6.删除远程所有文件


8.创建分支



9.合并分支


10.创建5个分支
待办管理
会员管理
文件管理
权限管理

前端分离
