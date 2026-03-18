1 创建工作目录（在虚拟机终端）：
  mkdir credit-switched && cd credit-switched
2.初始化Repo:
  repo init -u https://github.com/Huzhiwen1208/manifest.git
3.同步代码：
  repo sync

显示没有该命令时，再pip install 对应工具

在vscode远程链接虚拟机后，打开刚才创建的文件夹 credit-switched

目录如下：
<img width="812" height="198" alt="image" src="https://github.com/user-attachments/assets/8ea4e7a1-1207-4924-a34c-af978a9868ef" />

接下来推荐打开两个终端命令行：
启动后端：
cd backend
# 首次运行请安装依赖
mvn install
# 启动应用
mvn spring-boot:run

启动前端：
cd frontend
# 安装依赖
npm install
# 启动开发服务器
npm run dev


