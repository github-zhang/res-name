# res-name
Great repository names are short and memorable. Need inspiration? How about hairy-wookie


git init here            -- 创建本地仓库(repository)，将会在文件夹下创建一个 .git 文件夹，.git 文件夹里存储了所有的版本信息、标记等内容

git remote add origin git@github.com:winter1991/helloworld.git        
                         -- 把本地仓库和远程仓库关联起来。如果不执行这个命令的话，每次 push 的时候都需要指定远程服务器的地址

git add                  -- 从本地仓库增删，结果将会保存到本机的缓存里面
git rm

git commit -m "注释"     -- 提交，把本机缓存中的内容提交到本机的 HEAD 里面

git push origin master   -- 把本地的 commit(提交) push 到远程服务器上， origin 也就是之前 git remote add origin 那个命令里面的 origin，origin 替代了服务器仓库地址：git push git@github.com:winter1991/helloworld.git master
git pull origin master   -- 从远程服务器 pull 新的改动
