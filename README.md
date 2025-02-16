# Typora_pic
用于存储Typora中的图片

### Typora和Picgo联动使用

1.将Typora设置如下：

![image-20250217004227363](https://raw.githubusercontent.com/Realyangy/Typora_pic/main/20250217004227403.png)

Picgo的路径就是电脑中的存储位置。

2.在Picgo中使用Github图床：

​	第一步：新建一个仓库

​	第二步：新建一个该仓库的读写fine-grained tokens。新建步骤如下：Github头像 -> Settings -> Developer settings -> Personal access tokens -> Fine-grained tokens。可设置永久有效期；设置其对于刚才新建的仓库访问权限；设置对该仓库的读写权限（Repository Permissions -> Contents -> Read and write）;生成并保存Tokens。


​	第三步：配置Picgo图床如下：

![image-20250217004416745](https://raw.githubusercontent.com/Realyangy/Typora_pic/main/20250217004416767.png)

​	图床配置名是给该图床起的名字；仓库名是Github用户名/仓库名；分支(main或master)如下所示；Tokens就是刚才的一段字符；自定义域名是"https://raw.githubusercontent.com/用户名/仓库名/分支名"

![image-20250217005838586](https://raw.githubusercontent.com/Realyangy/Typora_pic/main/20250217005838605.png)
