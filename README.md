# huan.github.io
1. 创建一个名为 "test.txt" 的空文件。
```bash
touch test.txt
2. 显示当前路径的完整名称。
       pwd
3. 列出当前目录下的所有文件和文件夹。
       ls
4. 将文件 "file1.txt" 复制到目录 "/home/user/docs"。
       cp file1.txt /home/user/docs
5. 将文件 "file2.txt" 移动到目录 "/home/user/archive"。
       mv file2.txt /home/user/archive
6. 在文件 "data.txt" 中查找包含关键词 "error" 的行。
       grep error ./data.txt 
7. 显示系统当前时间和日期。
       date
8. 创建普通用户“admin”，并指定密码“abcdefg”
       useradd admin
       passwd admin
       abcdefg
       abcdefg
       
       or
       
       useradd admin
       echo abcdefg | passwd --sdin admin
9. 切换到用户 "admin"。
       su admin
10. 将文件 "oldfile.txt" 重命名为 "newfile.txt"。
        mv oldfile.txt newfile.txt
11. 将文件 "data.txt" 压缩为 "data.zip"。
        zip data.zip data.txt
12. 将文件 "backup.zip" 解压缩到当前目录。
        unzip backup.zip
13. 创建一个新的目录 "photos"。
        mkdir photos
14. 创建一个普通文件"temp.txt"
        touch temp.txt
15. 删除文件 "temp.txt"。
        rm -rf temp.txt
16. 切换到超级用户（root）身份。
        su - root
17. 显示当前登录的用户。
        whoami
        
        or
        
        echo $USER
18. 列出当前路径下的所有隐藏文件。
        ls -a
19. 将目录 "/home/user/docs" 中的所有文件和文件夹复制到目录 "/backup".
        cp -r /home/user/docs /backup 
20. 将文件 "data.txt" 的内容追加到文件 "archive.txt"。
        echo data.txt >> archive.txt
21. 创建一个新用户 "guest"。
        useradd guest
22. 列出系统中的所有用户。
        awk -F : '{print $1}' /etc/password
23. 修改文件 "config.txt" 的所有者为用户 "admin"。
        chown admin:admin config.txt
24. 将文件 "file1.txt" 和 "file2.txt" 合并为一个文件 "merged.txt"。
        cat file{1,2}.txt > merged.txt
25. 删除目录 "/tmp" 及其所有内容。
        rm -rf /tmp
26. 显示系统的运行时间。
        uptime
27. 显示系统中的当前登录用户数。
        who | wc -l
28. 将文件 "backup.tar.gz" 解压缩到目录 "/home/user/backup"。

    tar -zxvf backup.tar.gz -C /home/user/backup

