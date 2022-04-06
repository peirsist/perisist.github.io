# 配置docsify
[toc]
#### 0. 相关链接

- [ GitHub+docsify搭建个人博客_Pwalker的博客-CSDN博客_docsify部署到github上](https://blog.csdn.net/Pwalker/article/details/105434900)
- [docsify+github/gitee搭建个人在线文档_Mark_md的博客-CSDN博客_docsify 代码高亮](https://blog.csdn.net/Mark_md/article/details/121457115)
- [手把手教你用git上传项目到GitHub（图文并茂，这一篇就够了）](https://zhuanlan.zhihu.com/p/193140870)
- [ 上传/更新文件到github_记录踩过的坑只为了更好地填坑-CSDN博客_github 更新](https://blog.csdn.net/u011108439/article/details/80609235)

## 1. 安装docsify





## 2. 上传到github

### 2.1 ==**问题**==

```shell
git push -u origin master
```

- 执行上面语句出现 **error: src refspec master does not match any.** [**解决方法**](https://www.cnblogs.com/Renyi-Fan/p/13833340.html)

- git push错误failed to push some refs to的解决。[**解决方法**](https://blog.csdn.net/rocling/article/details/82956402)

  **执行**

  ```shell
  git pull --rebase origin main
  ```



## 3. 更新

push到云端就可以，要是网站没有更新，那就是代码的问题，找了好久，发现代码有问题，现在总结代码。

##### 创建本地仓库

```shell
git init
git add .
git commit -m "这是注释内容"
git remote add origin https://github.com/xxxx/xxx.git（https://github.com/xxxx/xxx.git就是仓库地址 ）
git push -u origin main
```

##### 更新本地仓库

```shell
git init
git add .
git pull origin main
git push -u origin main
```



- [Docsify 的 LaTex支持 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/363113255)
- [使用Markmap将docsify中的markdown通过思维导图的形式展示出来 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/352795634)
- [笑脸表情类目所有emoji - 笑脸表情有关的表情符号 - EmojiXD](https://emojixd.com/subgroup/face-smiling)
- [docsify导航栏缩进](https://github.com/iPeng6/docsify-sidebar-collapse)
- [docsify的配置+全插件列表 - 邓邓的流水账 (xhhdd.cc)](https://xhhdd.cc/index.php/archives/80/)
- [Docsify高亮](https://github.com/fzankl/docsify-plugin-flexible-alerts)
- [(ฅ>ω<*ฅ) 噫又好了~Docsify进阶配置 | 小四先生的博客 (zxiaosi.cn)](https://zxiaosi.cn/archives/cd1d42d1.html)
- [主题](https://jhildenbiddle.github.io/docsify-themeable/#/options)
- [font-weight - CSS（层叠样式表） | MDN (mozilla.org)](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-weight)
- 

