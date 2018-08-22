# bigfiles

## 下载链接

```text
https://raw.githubusercontent.com/wxlzmt/bigfiles/master/jdk1.8-api.zip
https://raw.githubusercontent.com/wxlzmt/bigfiles/master/[MV]AOA_BingBing-(youtube).mp4
https://raw.githubusercontent.com/wxlzmt/bigfiles/master/jdk-8u172-linux-x64.tar.gz
```

---

## 示例代码段

```shell
wget -P /usr/java https://raw.githubusercontent.com/wxlzmt/bigfiles/master/jdk-8u172-linux-x64.tar.gz
tar -zxvf jdk-8u172-linux-x64.tar.gz
```

`vim /etc/profile`

```text
export JAVA_HOME=/usr/java/jdk1.8.0_172
export CLASSPATH=$JAVA_HOME/lib/
export PATH=$PATH:$JAVA_HOME/bin
```

---

下载`jdk1.8-api.zip`并解压至`/var/www/html`目录下,如果目标文件已存在,则不覆盖.
```shell
wget https://raw.githubusercontent.com/wxlzmt/bigfiles/master/jdk1.8-api.zip
unzip -n jdk1.8-api.zip -d /var/www/html
```

---


