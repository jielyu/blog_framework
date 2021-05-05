# 青衣极客 Blue Geek

青衣极客，一个“有用”的频道。

[个人主页 Github Page](https://blog.bluegeek.me)

扫描二维码关注【青衣极客】公众号

![青衣极客](img/broadcast/wechat_public.png)

## Windows环境安装

第一步： 安装msys2

第二步： 安装ruby (带devkit版)

msys和ruby的安装包

链接: https://pan.baidu.com/s/16Yh7vZBmbJOSpWbBjHpnJg  密码: kaln


第三步：ruby安装后弹出的cmd中选择3，安装工具链

第四步： 安装jekyll、bundler

```
gem install jekyll bundler
```

第五步： 安装框架依赖包

到框架工程的根目录运行以下指令

```
bundle install
```

第六步： 运行框架测试服务器

```
bundle exec jekyll serve
```

第七步：在浏览器中输入访问 "127.0.0.1:4000"

## 托管网站

### Github Pages

可以利用github pages来托管网站

第一步：创建一个 username.github.io的仓库

第二步：把博客源代码推送到该仓库

第三步：等待部署完成后，在网页访问 "username.github.io"

第四步：将username.github.io绑定到自己购买的域名上

github.io域名在国内已被封禁，慎重使用

## Coding Pages

国内可以选择腾讯的coding.net项目进行托管，用法跟github类似

第一步： 创建一个仓库存储源代码

第二步： 将源代码推送到仓库中

第三步：选择持续部署

第四步：选择自定义域名，将自己购买的域名绑定到自定义域名那里，然后将coding上生成的域名绑定到购买的域名的DNS上

第五步： 国内的网站需要申请证书，在coding上可以直接申请，大概一天能够批准下来

coding提供了半年的免费部署，半年之后要收费。通过计算发现，收费并不高，所以基本可以使用。
选择香港节点，响应速度也还不错。