# 贡献代码

## fork 我的项目
登录您的 [Github](http://github.com/) 账户。
点击下面的连接，进入我的仓库
> [https://github.com/tidyjiang8/ieee-802.15.4-2006-chinese](https://github.com/tidyjiang8/ieee-802.15.4-2006-chinese)

点击右边的 fork，将我的仓库 fork 到您的用户下。
## clone 到本地

fork 成功后，进入该项目，点击右边的```Clone or Download```，在弹出的小窗口中将您的仓库地址复制到粘贴板。

进入您的 Linux 或者 Windows，将您的项目**克隆到本地**，比如：
```
git clone git@github.com:jchunhua163/ieee-802.15.4-2006-chinese.git
```
> 将后面的仓库地址换成您对应的地址。

## 将您 fork 后的仓库与我的仓库同步
为了避免您提交的改动与我的仓库的改动产生冲突，您需要在我的最新版的基础上做修改。

**添加我的仓库作为您的远程源**：
```
git remote add tidyjiang8 https://github.com/tidyjiang8/ieee-802.15.4-2006-chinese
```
**更新远程源**：
```
git remote update
```
基于我最新的仓库创建一个新分支，比如：
```
git checkout tidyjiang8/master -b chapter_5.1
```
将新分支推送到您的远程仓库：
*```
git push origin chapter_5.1
```
## 在 Gitbook 中导入书籍
进入 Gitbook 主页，用您的 Github 账户登录 Gitbook。
> 如果您是第一次登录 Gitbook，需要进行授权。在弹出的新窗口中，选择```Authroize Application```即可。

新建一本书，将书的类型选为 GITHUB。

> 如果您是第一次使用 Gitbook 创建书籍，需要再次授权。点击 Link to your Github，然后在新弹出的窗口宏，选择```Authroize Application```。
> <center> <img src="" /> </center>

在上图中，先选择好您的 Github 仓库，再填好您在 Gitbook 上要创建的书籍的标题和链接，然后点击```Create book```按钮。

此时，Gitbook 会从您的 Github 仓库同步您的书籍。稍微等待一会儿，如果长时间一直在同步，请刷新页面。然后就可以看到，我们已经成功地在 Gitbook 上创建了一本书。
## 使用 Gitbook 编辑书籍
点击右上角的 Gitbook 在线编辑按钮，您就可以在线编辑这本书了。
下图是 Gitbook 编辑器的页面：

①：
②：
③：
④：
⑤：
⑥：
⑦：
⑧：