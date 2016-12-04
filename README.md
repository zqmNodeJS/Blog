# Blog
《Node.js实战》

#### 全局安装 Express

```ruby
sudo npm install -g express-generator@4
```

注: `node --version`为v6.9.1

#### 新建一个工程
* 在github创建仓库Blog,并且git clone到本地(本人使用`SourceTree`工具)

* 切换至本地仓库根目录

* 创建一个名为blog的Express项目
```ruby
express -e blog
```
* 切换到blog根目录,并且安装所需模块
```ruby
cd blog && npm install
```

* 运行
```ruby
DEBUG=blog:* npm start
```

* 浏览器打开: `http://localhost:3000/`
