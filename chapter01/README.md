# 开始Vim之旅

## 安装
```zsh
brew install vim # 安装vim
brew upgrade vim # 更新vim
```

## 配置文件
家目录：
```zsh
echo $HOME
```
配置文件位置: `/home/<username>/.vimrc`

## 常用操作
- 打开文件: `vim`, `:e` 
- 修改文字: `i`, 
- 保存关闭文件: `:w`, `:q`
- **交换文件**: Vim 默认在原始文件目录下自动生成`.<filename>.swp`文件，用于恢复文件内容，防止用户的 Vim 会话或系统崩溃。
- 随意移动光标: `h`, `j`, `k`, `l`, `w`, `e`, `b`, `{`, `}`。
- 简单编辑: `c`, `d`。 
- 撤销和重做: `u`, `Ctrl`+`r`。
