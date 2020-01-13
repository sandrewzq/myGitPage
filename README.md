# 声明
> 自用Gitpage项目，使用hexo博客框架，仅作为记录备份使用

### 1.hexo指令说明

全局安装hexo

```
npm install -g hexo
```
新建一个空目录，在目录中执行
```
hexo init
```

##### 部署到github:
1.修改根目录下文件 [_congif.yml](_config.yml)
```
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repo: <你的仓库地址> # https://github.com/sandrewzq/sandrewzq.github.io
  branch: master
```
2.下载hexo-deployer-git工具
```
npm install hexo-deployer-git --save
```
3.push项目
```
hexo clean

hexo deploy
```
### 2.使用主题
开源HEXO主题
[hexo-theme-ace](https://github.com/kinggozhang/hexo-theme-ace)



# 感谢及引用
- [5分钟搞定个人博客-hexo](https://www.jianshu.com/p/390f202c5b0e) - But昊@简书
- [hexo-theme-ace](https://github.com/kinggozhang/hexo-theme-ace) - kinggozhang@Github 


