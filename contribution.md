# 贡献代码

---
主要内容：
####　　fork 我的项目
####　　clone 到本地
####　　将您 fork 后的仓库与我的仓库同步
####　　在 Gitbook 中导入书籍
####　　使用 Gitbook 编辑书籍
####　　提交 Pull Request
####　　翻译约定
####　　Gitbook 编辑常见问题
---
## fork 我的项目
**登录您的 [Github](http://github.com/) 账户**。
点击下面的连接，进入我的仓库
> [https://github.com/tidyjiang8/ieee-802.15.4-2006-chinese](https://github.com/tidyjiang8/ieee-802.15.4-2006-chinese)

点击右边的 fork，**将我的仓库 fork 到您的用户下**。
<center> <img src="images/contribution/Image 1.png" /> </center>

## clone 到本地

fork 成功后，进入该项目，点击右边的```Clone or Download```，在弹出的小窗口中将**您的仓库地址复制到剪切板**。

<center> <img src="images/contribution/Image 2.png" /> </center>


进入您的 Linux 或者 Windows，**将您的项目克隆到本地**，比如：

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

**基于我最新的仓库创建一个新分支**，比如：

```
git checkout tidyjiang8/master -b chapter_5.1
```

**将新分支推送到您的远程仓库**：

```
git push origin chapter_5.1
```

## 在 Gitbook 中导入书籍

进入 Gitbook 主页，**用您的 Github 账户登录 Gitbook**。

> 如果您是第一次登录 Gitbook，需要进行授权。在弹出的新窗口中，选择```Authroize Application```即可。


<center> <img src="images/contribution/Image 3.png" /> </center>

<center> <img src="images/contribution/Image 7.png" /> </center>

**新建一本书**:

<center> <img src="images/contribution/Image 4.png" /> </center>

**将书的类型选为 GITHUB**。

> 如果您是第一次使用 Gitbook 创建书籍，需要再次授权。点击 Link to your Github，然后在新弹出的窗口宏，选择```Authroize Application```。
> 
> <center> <img src="images/contribution/Image 6.png" /> </center>

<center> <img src="images/contribution/Image 5.png" /> </center>

在上图中，先**选择好您的 Github 仓库，再填好您在 Gitbook 上要创建的书籍的标题和链接，然后点击```Create book```按钮**。

此时，Gitbook 会从您的 Github 仓库同步您的书籍。稍微等待一会儿，如果长时间一直在同步，请刷新页面。然后就可以看到，我们已经成功地在 Gitbook 上创建了一本书。
<center> <img src="images/contribution/Image 10.png" /> </center>

## 使用 Gitbook 编辑书籍
点击右上角的 Gitbook 在线编辑按钮，您就可以在线编辑这本书了。

下图是 Gitbook 编辑器的页面：

<center> <img src="images/contribution/Image 11.png" /> </center>

①：工具栏区域。我们在编辑文章时就用这些工具按钮进行排版。

②：窗口控制区域。

③：分支管理区域。

④：书籍设置区域。

⑤：书籍目录。

⑥：书籍源码。书籍目录区域的每个目录都会在该区域下对应一个源码。

⑦：编辑区。我们在这个区域编辑书籍。

⑧：预览区。编辑区的显示效果不是最终的效果，预览区的显示效果才是最终的效果。

您也可是使用 **Gitbook 离线编辑器**：
> [https://www.gitbook.com/editor](https://www.gitbook.com/editor)

## 提交 Pull Request

**先在 Gitbook 的编辑器中编辑代码，然后保存**。
> 注意，编辑前一定要将您的分支切换到所创建的对应分支。比如我将分支切换到```chapter_5.1```：
> <center> <img src="images/contribution/Image 12.png" /> </center>

<center> <img src="images/contribution/Image 13.png" /> </center>

进入 Github。找到对应的文件，然后将分支切换到 ```chapter_5.1```，我们可以看到，在 Gitbook 中编辑的内容已经自动同步到 Github 里了：



<center> <img src="images/contribution/Image 14.png" /> </center>

**进入仓库的根目录，点击下面的```New Pull Request```**：


<center> <img src="images/contribution/Image 15.png" /> </center>

在新出来的页面中，选择**右边的分支为新创建的分支，然后点击```Create pull request```**：

<center> <img src="images/contribution/Image 16.png" /> </center>

再次确认右边的分支是您的新分支，然后**填写```Pull Request```的标题和正文**，简要说明您的 Pull Request 都做了哪些修改。最后点击右下角的```Create pull request```。
<center> <img src="images/contribution/Image 17.png" /> </center>

这样，您就完成了一次```pull request```。

我会收到系统发的邮件，告诉我有人已经申请 pul request，我会检查您的改动。如果没有问题，我就会将您的```pull request```合并到我的主分支上。如果有问题，我会在该pull request页面留言(此时系统也会向您发送邮件)。

## 翻译约定
- 中文和英文之间，中文和数字之间保留一个半角空格。
- 如果需要适用男圆括弧一律使用英文的换括弧
- 如果要使用破折号，一律用 ```—— ``` ，且在破折号后加一个半角空格。
- 段首用两个中文全交空格缩进。
- 其它。。。

## Gitbook 编辑常见问题
- **如何换行**：连敲两次回车键，即可换行。
- **如何在表格中换行**：输入```<br>```即换行。
- **如何缩进**：将您的输入法切换到中文全交，然后在段首输入空格，即可缩进。
<center> <img src="images/contribution/Image 18.png" /> </center>
- **如何居中**：使用 html 标签 center。例如：

```
<center> 这是居中！ </center>
```
显示效果：

<center> 这是居中！ </center>

- **如何插入图片**：我会将本项目所有需要用到的图片都上传到仓库里，您可以直接使用。通用使用标签：

```
<center> <img src="images/contribution/Image 17.png" /> </center>
```
您只需将对应图片的路径替换掉即可。
