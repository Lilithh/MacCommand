#Terminal
- `defaults write com.apple.finder AppleShowAllFiles -bool true; killall Finder`
 >显示隐藏文件
 
- `defaults write com.apple.finder AppleShowAllFiles -bool false; killall Finder`
>隐藏隐藏文件 

- `open ~/../../ `
>打开文件或文件夹

- `enca file` 
>查看file文件的编码格式

- `enca -x utf-8 file`
>将file文件转换为utf-8的格式

- `iconv -f UTF-8 -t GBK Desktop/from.txt > to.txt`

>文件格式转换
参数: 
>>`-f`是现在的格式  `-t`是目标格式
>>`Desktop/from.txt` 输入文件 ` to.txt`是目标文件

---
- `ifconfig` 
>查看本机网络信息 
>`en0` 本机ip地址

 - `traceroute host`

  **跟踪访问`host`地址的路径、路由信息**
  
- `netstat`

>跟踪系统当前建立会话的端口，地址等
参数: 
>>`-n` 查看侦听会话的原地址、目标地址、端口*(Active Internet connections)*
>>`-an` *(Active Internet connections (including servers))*

- 
