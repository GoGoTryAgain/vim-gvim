# gvim

#### 介绍
gvim 配置，用leaderf，实现文件查找，列出，定义跳转，使用查找

#### 软件架构
总共目前有leaderf、LeaderF、vim-monoka（主题）、nerdtree（目录树）、Mark（高亮关键字）
替代ctrlp 和gtags和rg一起使用，同时可以替换cscope，gtags，


#### 安装教程

1.  安装gvim 8.2，这个是基于x64的
2.  安装python3.8  x64位，和gvim的Python版本一致，不清楚的可以打开gvim输入:version查看python3版本
3.  用当前repository里面的_vimrc替换安装目录下的_vimrc
4.  安装gtags（leaderf查找代码必须要的）  解压glo663wb.zip，把bin目录添加到环境变量
5.  安装rg（leaderf模糊查找需要的）  解压ripgrep-12.1.1-x86_64-pc-windows-msvc.zip，把rg.exe复制到gvim安装目录，和gvim.exe同一级目录
6.  安装vundle，在vim安装目录的vimfile内，执行gitbash 终端，输入 git clone https://github.com/VundleVim/Vundle.vim.git bundle/Vundle.vim
6.  安装插件 gvim执行 PluginInstall（因为vimrc已经替换了）


#### 使用说明


#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
