# hello-world
a simple github start project
3.2 生成SSH KEY
 
代码
$ ssh-keygen -t rsa -C "your_mail_addr@gmail.com"
Enter file in which to save the key (/c/Users/Tekkub/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Tekkub/.ssh/id_rsa.
Your public key has been saved in /c/Users/Tekkub/.ssh/id_rsa.pub.
The key fingerprint is:
e8:ae:60:8f:38:c2:98:1d:6d:84:60:8c:9e:dd:47:81 your_mail_addr@gmail.com
 
在这里会要求输入key 目录和 密码，可根据自己的情况输入

注：这里生成的key可以在多个网站上使用（例如github和bitbucket），只要本地的和对应网站的key保持一致就可以了 
 
3.3 将Public Key 添加到GitHub
打开你的GitHub->SSH Public Key->点击“Add another public key”,  将你的public key（id_rsa.pub）的内容拷贝到GitHub中
 

bitbucket添加方式：帐号下来-->Account-->SSH keys 里面的 Add a new key ,  将你的public key（id_rsa.pub）的内容拷贝到SSH key文本框
