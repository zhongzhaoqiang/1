#### **配置个人信息**

##### 1.用户名

```shell
git config --global user.name "zhongzhaoqiang"
```

##### 2.邮箱

```shell
git config --global user.email "2979376005@qq.com"
```

#### 本地仓库

##### 1.创建仓库

```shell
$ git init
```

![1603097621694](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1603097621694.png)



![1603097644723](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1603097644723.png)

#### 文件版本

##### 1.新建文件

```shell
touch note.txt
```

##### 2.把文件添加到仓库

```shell
git add note.txt
```

3. 文件提交到仓库 

```shell
git commit -m "新建"
[master (root-commit) 4c4e031] 新建
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 note.txt

```



```
git remote add origin git@github.com/zhongzhaoqiang/1.git
```