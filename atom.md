<time>2016.4</time>

- 介绍
![atom](./atom.png)

  - 官网 [atom.io](https://atom.io/)
  - 中文社区 [atom-china.org](https://atom-china.org/)
  - [为什么选择 Atom](https://atom-china.org/t/atom/59)
  - [Atom 基础使用](https://atom-china.org/t/guan-fang-shou-ce-atom-ji-chu-shi-yong/62)


- 下载安装

  - 下载地址 [*国内可下载地址*](http://cnpmjs.org/mirrors/atom/)
  - 安装插件
  >由于墙的原因apm不好用，需要安装使用npm。直接安装[node.js](http://nodejs.cn/)，自带npm。

  - 离线安装插件
```
git clone  $url(* git资源地址*)
cd (*本地仓库地址*)
npm install
```

- 插件
  - **[atom-simplified-chinese-menu](https://github.com/chinakids/atom-simplified-chinese-menu)** — 含菜单汉化、右键菜单汉化以及设置汉化
  - **[atom-html-preview](https://github.com/webBoxio/atom-html-preview)** — 实时html
  - **[css-clean](https://github.com/SeanJM/css-clean)** — css格式化

  - **[Emmet](https://github.com/emmetio/emmet-atom)** — 用过都说好,神器;有个别快捷键会和Markdown preview快捷键冲突,改下就好了
  - **[autoprefixer]()** — 用来补充css前缀的,会自动生成多个浏览器的前缀
  - **[color-picker]()** — 取色器,太赞了有木有,不卡,启动超快
  - **[git-plus](https://github.com/akonwi/git-plus)**
可以直接在 Atom 的命令面板中运行 git commit, git push 等常用命令，可以使用 Atom 来编辑 Commit Message, 查看 Diff, 查看文件历史等。有了这个插件就不需要离开 Atom 去 Shell 或者 GUI 来操作 Git 了
  - **[git-projects](https://github.com/prrrnd/atom-git-projects)**
可以用 ctrl-alt-o 这个快捷键搜索磁盘（默认是 ~/repos）上的 Git 仓库，形成一个列表供你快速打开一个 Atom 窗口来编辑这个项目。有了这个插件可以非常快速地打开某个项目，项目比较多也不必找来找去（可以设置按照上次修改时间排序）
  - **[merge-conflicts](https://github.com/smashwilson/merge-conflicts)**
在使用 Git 进行合并和 rebase 的时候可以用 alt-m d 来激活这个插件，它会列出所有冲突的文件，将每一处冲突高亮，同时有按钮和快捷键供你快速选用某个版本，在你解决所有冲突后会提示你进行 Commit. 有了这个插件再也不同担心出冲突的时候看瞎眼了
  - **[atom-beautify](https://github.com/Glavin001/atom-beautify)**
可以格式化几乎所有语言的代码，比较适合从别处粘贴代码后进行格式化，或者平时不太注意代码样式的人使用
  - **[linter](https://github.com/steelbrain/linter)**
Linter 是一个代码纠错的基础设施，安装了 Linter 后你就可以去安装具体语言的纠错插件，为你的代码提供实时的语法检查和风格检查
  - **[highlight-selected](https://github.com/richrace/highlight-selected)** 当你选择了一个单词，这个插件会在编辑器中高亮显示所有这个单词出现的地方（就像你进行搜索时一样），在修改代码时非常有用


- 快捷键

  - 命令面板 `cmd-shift-P`
  - 文件切换
    - `cmd-O` 打开文件
    - `ctrl-shift-s` 保存所有打开的文件
    - `cmd-shift-o` 打开目录
    - `cmd-\` 显示或隐藏目录树
    - `ctrl-0` 焦点移到目录树,目录树下，使用`a，m，delete`来增加，修改和删除
    - `cmd-t` 或 `cmd-p` 查找文件
    - `cmd-b` 在打开的文件之间切换
    - `cmd-shift-b` 只搜索从上次git commit后修改或者新增的文件
  - 括号跳转
    - `ctrl-m` 相应括号之间，html tag之间等跳转
    - `ctrl-cmd-m` 括号(tag)之间文本选取
  - 编码方式
    - `ctrl-shift-U` 调出切换编码选项
  - 查找和替换
    - `cmd-F` 在buffer中查找
    - `cmd-shift-f` 在整个工程中查找
  - 自动补全
    - `ctrl-space` 提示补全信息
  - 文件语法高亮
    - `ctrl-shift-L` 选择文本类型
  - 使用Atom进行写作
    - `ctrl-shift-M` Markdown预览,可用代码片段 `b, legal, img, l, i, code, t, table`
