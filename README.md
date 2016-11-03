下面是github一些简单的操作：
1，首先注册一个github的账户
2，在电脑上安装git环境
3，配置git和github，让两者关联起来：
1） Linux 与 Mac 都是默认安装了 SSH ，而 Windows 系统安装了 Git Bash 应该也是带SSH的，大家可以在终端（win下在 Git Bash 里）输入 ssh 查看是否已经安装了ssh，安装成功提示如下：
![image](https://github.com/zhlmgithub/github-test/blob/master/res/image/ssh2.png)
     紧接着输入 ssh-keygen -t rsa ，什么意思呢？就是指定 rsa 算法生成密钥，接着连续三个回车键（不需要输入密码），然后就会生成两个文件 id_rsa 和 id_rsa.pub ，而 id_rsa 是密钥，id_rsa.pub 就是公钥。这两文件默认分别在如下目录里生成： Linux/Mac 系统 在 ~/.ssh 下，win系统在 /c/Documents and Settings/username/.ssh 下，都是隐藏文件，相信你们有办法查看；接下来要做的是把 id_rsa.pub 的内容添加到 GitHub 上，这样你本地的 id_rsa 密钥跟 GitHub 上的 id_rsa.pub 公钥进行配对，授权成功才可以提交代码。
2） 第一步先在 GitHub 上的设置页面，点击最左侧 SSH and GPG keys；
![image](https://github.com/zhlmgithub/github-test/blob/master/res/image/ssh1.png)


     第二步然后点击右上角的 New SSH key 按钮：
  ![image](https://github.com/zhlmgithub/github-test/blob/master/res/image/ssh3.png)
     需要做的只是在 Key 那栏把 id_rsa.pub 公钥文件里的内容复制粘贴进去就可以了（上述示例为了安全粘贴的公钥是无效的），Title 那栏不需要填写，点击 Add SSH key 按钮就ok了。SSH key 添加成功之后，输入 ssh -T git@github.com 进行测试，看看是否添加成功了
     ![image](https://github.com/zhlmgithub/github-test/blob/master/res/image/ssh4.png)
 3）clone github上的代码， git clone git@github.com:stormzhang/test.git 
    （git clone git@github.com:zhlmgithub/okhttp.git）用这样的命令clone好代码之后，就可以用git处理其他的操作了。

