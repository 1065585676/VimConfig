# VimConfig

### 配置文件路径：~/.vimrc

#### " 自动语法高亮
syntax on

#### " 显示当前位置
set ruler

#### " 设置编码
set encoding=utf-8

#### " 编码设置
set enc=utf-8

set fencs=utf-8,ucs-bom,shift-jis,gb18030,gbk,gb2312,cp936

#### " 检测文件类型
filetype on

#### " 检测文件类型插件
filetype plugin on

#### " 上下可视行数
set scrolloff=6

#### " 设定 tab 长度为 4
set tabstop=4

#### " 覆盖文件时不备份
set nobackup

#### " 搜索到文件两端时不重新搜索
set nowrapscan

#### " 搜索时忽略大小写，但在有一个或以上大写字母时仍大小写敏感
set ignorecase

set smartcase

#### " 搜索时高亮显示被找到的文本
set hlsearch

#### " 智能自动缩进
set smartindent

#### " 设置 laststatus = 0 ，不显式状态行
#### " 设置 laststatus = 1 ，仅当窗口多于一个时，显示状态行
#### " 设置 laststatus = 2 ，总是显式状态行
set laststatus=2

#### " 设置在状态行显示的信息
set statusline=%F%m%r%h%w%=\ %l-%c\ (%p%%)\ %Y,\ %{\"\".(&fenc==\"\"?&enc:&fenc).((exists(\"+bomb\")\ &&\ &bomb)?\"+\":\"\").\",\"}\ %{&ff}\

#### "显示括号配对情况
set showmatch
#### " 高亮显示匹配的括号
set showmatch

#### " 解决自动换行格式下, 如高度在折行之后超过窗口高度结果这一行看不到的问题
set display=lastline
