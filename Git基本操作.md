## 平台准备

安装vscode，接着安装git(官网下载)，安装时选择用vscode作为编辑器，在vscode中安装插件GitHub Pull Requests and Issues。


## 下载到本地

- 打开vscode，登录github(左侧边栏猫咪)
- ctrl+shift+p 选择clone 输入项目的网址(形如 https://···xxx.git) 回车

## 创建文件并提交

- 资源管理器，新建文件
- 源代码管理，更改栏，点+号，进入暂存
- 最上方，输入提交消息，ctrl+enter(或者点对号)

## 创建分支
- 最下方main，点击，输入分支名字，回车
- 法二: 最上方终端，选择gitBash，输入 git checkout -b \<branchName\>

## 提交分支
- 回到main分支，git checkout main
- 合并分支，git merge \<branchName\>

## 删除分支
- 查看分支 git branch
- 删除分支 git branch -D \<branchName\>

## 提交到云
- 回到main，git checkout main
- 提交， git push (不行多来几次)
- 网络老断，试试 git config --global http.sslVerify "false"