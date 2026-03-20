1 创建工作目录（在虚拟机终端）：
  mkdir credit-switched && cd credit-switched
  
2.初始化Repo:
  repo init -u repo init -u https://github.com/Unnamed-project-o/full-stack-manifest.git
  （注意这里有时候初始化repo工具不通，可以改用repo init -u https://github.com/Unnamed-project-o/full-stack-manifest.git --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo）
  
3.同步代码：
  repo sync

前面操作显示缺失什么工具时，pip install 对应工具

在vscode远程链接虚拟机后，打开刚才创建的文件夹 credit-switched

目录如下：
<img width="446" height="300" alt="image" src="https://github.com/user-attachments/assets/11b138a3-9d23-4b0b-9d81-1c65472f382a" />



终端运行命令：
chmod +x run.sh

./run.sh


