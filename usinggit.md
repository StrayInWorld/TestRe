# Git的使用
## Git命令
- 所有的git命令都需要使用git开头。
- 在进行任何 Git 操作之前，都要先切换到 Git 仓库目录，也就是先要先切换到==项目的文件夹目录下==。
- git status 这个命令顾名思义就是==查看状态==，这个命令可以算是使用最频繁的一个命令了，建议大家没事就输入下这个命令，来查看你当前 git 仓库的一些状态。
***
### 第一步
   - 创建一个文件，再创建一个文件夹
   （需要==使用Git的命令行==来实现，而不是window带的命令行，否则touch命令为未知命令）。
     - mkdir E:/GitTest    --创建目录 
     - cd E:/GitTest       --切换到test目录
     - touch a.md          --新建.md（Markdown）文件
***
### 第二步
   - 输入git init，表示初始化git库。
   - 输入git status, 输出的信息表示文件并没有被追踪。
   - 输入git add a.md。再输入git status。输出changes to be commited表示等待被提交。
   - 输入git commit -m 'first comment' 。commit表示提交,-m 后的内容表示提交的信息。执行以上命令表示进行了第一次提交。
   - 输入git log。就会看到commit记录。
   - 总结就是需要==先git add filename== , 再==git commit -m 'info'==。当然也可以==一步完成==。
***
### 第三步
   - git branch 查看当前分支。
   - git branch a 新建一个分支。分支前面带有 * 表示当前所在开发的分支。
   - git checkout a 表示切换分支。
   - git checkout -b a 表示创建分a支并且切换到分支a。
   - git merge a 表示合并分支a。不过==需要先切换到主分支==，如果已经在主分支则不用切换了
   - git branch -d 表示删除分支。
   - git branch -D 表示强制删除分支。
   - git tag v1.0 表示在当前代码状态下新建v1.0的标签。使用git tag可以查看tag记录。
   - git checkout v1.0 表示切换到v1.0tag的代码状态。





































  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
 