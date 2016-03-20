## Auto update the /etc/hosts file

### 自动更新/etc/hosts文件（用了近一年了，并结合着Lantern一起用，非常好用）

### How to use(run as superuser privileges):
* sudo ./hosts.sh


- 脚本会把系统中现有的/etc/hosts备份在原路径中，然后下载新的hosts文件
- 如果有固定的（自定义的，一定要存在的）hosts条目需要添加，可写入到/etc/hosts.base中，这样，每次更新hosts文件时，新hosts文件都会把hosts.base文件中的条目原封不动地加入到新hosts文件中。


#### via: https://github.com/racaljk/hosts/raw/master/hosts
