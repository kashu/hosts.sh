## Auto update the hosts file

### 自动更新hosts文件（用了大半年了，挺好用的）

### How to use:
* ./hosts.sh


- 脚本会把系统中现有的/etc/hosts备份在原路径中，然后下载新的hosts文件
- 如果有固定的（自定义的，一定要存在的）hosts条目需要添加，可写入到/etc/hosts.base中，这样，每次更新hosts文件时，新hosts文件都会把hosts.base文件中的条目原封不动地加入到新hosts文件中。


#### The source file at here: https://github.com/racaljk/hosts/raw/master/hosts
