***
#### 执行后台运行命令并记录输出到文件
    nohup python ***.py > ***.out 2>&1 &
>说明：  
    1. nohup 命令将输出重定向至指定文件，默认为 nohup.out,通过 > file 指定文件名file, 2>&1 将
    错误输出也重定向到同一个文件。  
    2. 末尾的 & 命令 让程序后台运行,关掉窗口会话程序不会停止;
***
#### linux alias 命令
    #~/bash_aliases
    alias notes="cd */*/notebook"
    #activate
    source ~/.bashrc
>alias命令 指定简洁的短命令代替长命令 
***
