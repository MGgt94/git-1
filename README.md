安装
 git --version      看版本
cd /g/git        cd+路径(直接拖文件夹)
touch index.html    
touch app.js 在文件夹下建
git init  初始化
git config --global user.name '木槿gt'  
git config --global user.email '1840264662@qq.com'
git add index.html 添加
git add *.html       添加某一类文件
git add .   上传所有文件
git status 看状态 查看修改
git rm --cached index.html 移除
git commit 提交时备注信息
esc :wq 退出
修改文件，查看状态，提示
再次添加git add .
提交并备注 git commit -m 'changed app.js' 
touch .gitignore 增加忽略文件 在忽略文件中写需要忽略的内容
比如：git.txt
          /demo2
git branch login 创建分支 
git checkout login切换到分支 
git checkout master 回到主线
git merge login 合并到主线

https://github.com 登录 复制命令操作

touch README.md