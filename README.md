# Typecho_Replit
在Replit部署Typecho博客 + [Butterfly主题移植](https://blog.wehaox.com/archives/typecho-butterfly.html#cl-3 )</br>

大前端主题</br>
- [Typecho-theme-DUX](https://wwfx.lanzouw.com/iSRQF0yqeglc) 密码:bt0m  </br>

附带插件</br>
- [LoginDesigner](https://github.com/jrotty/LoginDesigner)</br>
- [Snow-Typecho-Plugin](https://github.com/journey-ad/Snow-Typecho-Plugin)</br>
- [DynamicLines-typecho-plugin](https://github.com/1379/DynamicLines-typecho-plugin)</br>

<b>不装插件的话可以用注释代码将 <b>main.sh</b> 以下内容注释掉即可：</b></br>
```bash
<!--
# 回到根目录
cd ../

# Snow 插件
cd plugins
mkdir Snow
cd Snow
git clone https://github.com/journey-ad/Snow-Typecho-Plugin.git && mv -b Snow-Typecho-Plugin/* ./ && mv -b Snow-Typecho-Plugin/.[^.]* ./ && rm -rf *~ && rm -rf Snow-Typecho-Plugin

# 登录美化
cd ../
mkdir LoginDesigner
cd LoginDesigner
git clone https://github.com/Sayafx/LoginDesigner/ && mv -b LoginDesigner/* ./ && mv -b LoginDesigner/.[^.]* ./ && rm -rf *~ && rm -rf LoginDesigner

# 蛛网

cd ../
mkdir DynamicLines
cd DynamicLines
git clone https://github.com/Sayafx/DynamicLines-typecho-plugin.git && mv -b DynamicLines-typecho-plugin/* ./ && mv -b DynamicLines-typecho-plugin/.[^.]* ./ && rm -rf *~ && rm -rf DynamicLines-typecho-plugin
-->
```

### 个人版（不推荐）：
### 教育版(Team) 安装：
<a href="https://repl.it/github/super-yan86/Typecho_Replit">
  <img alt="Run on Repl.it" src="https://repl.it/badge/github/super-yan86/Typecho_Replit" style="height: 40px; width: 190px;" />
</a></br>
将以下代码粘贴至Replit Shell后回车

```git
  git clone https://github.com/super-yan86/Typecho_Replit.git && mv -b Typecho_Replit/* ./ && mv -b Typecho_Replit/.[^.]* ./ && rm -rf *~ && rm -rf Typecho_Replit
```

当加载完 Detected change in environment, reloading shell...
在Shell输入`sh main.sh`初始化，初始化完成后点击绿色 ▶ Run 运行

-----------------------------------------------------------------------------------------------------------------

默认请使用原生sqlite数据库</br>
postgresql数据库版：[https://github.com/super-yan86/Typecho_Replit_pgsql](https://github.com/super-yan86/Typecho_Replit_pgsql)</br>
修改自：[https://github.com/valetzx/typechonreplit](https://github.com/valetzx/typechonreplit)

# 修改内容

添加了下列插件

- [LoginDesigner](https://github.com/jrotty/LoginDesigner)
- [Snow-Typecho-Plugin](https://github.com/journey-ad/Snow-Typecho-Plugin)
- [DynamicLines-typecho-plugin](https://github.com/1379/DynamicLines-typecho-plugin)


<!--
# 关于图床

## 推荐使用 PicGo + bilibili 图床

### [点此下载PicGo](https://alist.sayagal.repl.co/d/%E5%B7%A5%E5%85%B7/PicGo-Setup-2.3.0-x64.exe)

### 在 PicGo 中安装bilibili图床插件

- 在线安装

  打开 [PicGo](https://github.com/Molunerfinn/PicGo) 详细窗口，选择**插件设置**，搜索**bili**安装，然后重启应用即可。

- 离线安装

  克隆该项目，复制项目到 以下目录：

  - Windows: `%APPDATA%\picgo\`
  - Linux: `$XDG_CONFIG_HOME/picgo/` or `~/.config/picgo/`
  - macOS: `~/Library/Application\ Support/picgo/`

  切换到新目录执行 `npm install ./picgo-plugin-smms-user`，然后重启应用即可。

### 获取B站SESSDATA

1. 登录[B站](https://www.bilibili.com/)
2. 按`F12`打开控制台
3. 找到`SESSDATA`复制即可![img](https://i0.hdslb.com/bfs/album/4b212e3692523c9baa9bfb4415b89c68fff44557.png)

### 解决B站防盗链（403）

> B站开启了防盗链，利用的是HTTP的Referer属性做判断。如果Referer是他白名单之外的网站，就会返回403

#### 全站图片使用

在外观-设置外观里找到`自定义head标签内位置内容`，设置如下标志，那么全站资源引用都不会携带referrer

```
<meta name="referrer" content="no-referrer">
```

[具体配置点此查看](https://github.com/xlzy520/picgo-plugin-bilibili.git)

PS. 自行启用插件和主题

Snow插件推荐设置，观感较好。
![Snow设置](https://images.weserv.nl/?url=https://article.biliimg.com/bfs/article/dafa22094fc8129879ee352d2763bd41299108a8.png)

[博客原址](https://syblog.repl.co/index.php/archives/3/)
-->
