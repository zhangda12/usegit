进入盘符 ：cd E：
回车 创建目录 ： mkdir git仓库 
进入目录 ： cd git仓库 
退出目录 ： cd .. 
初始化仓库 git init 
列出当前目录所有的文件 ls -la
添加文件 git add gituse.txt
查看状态 git status
提交 git commit -m '注释'
生成ssh key  ssh-keygen -t rsa -C "1913321356@qq.com"
找到密钥 window: C:User/Admi/.ssh 用记事本打开.pub 公钥 复制里面的内容 打开github账号 点击setting 在左侧 选择SSH and GPG keys 点击New SSH keys 在title写名字 key粘贴