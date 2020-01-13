# weibo-rss

微博 RSS 订阅源生成器，可将某人最近发布的微博转换为符合 RSS Feed 标准的格式订阅。  
支持长微博、所有配图、链接的完整输出。  
致力于一目了然的微博阅读体验。  

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## 手动部署

运行环境要求：`Node.js >= v8.0.0`  
安装：
```
git clone https://github.com/zgq354/weibo-rss.git
cd weibo-rss
npm install
```
启动：
```
npm install pm2 -g
pm2 start bin/www
```

更多配置参考 [项目Wiki](https://github.com/zgq354/weibo-rss/wiki)  


## 相关项目
1. [RSSHub](https://github.com/DIYgod/RSSHub)

## 赞助

若本项目为你的生活增添了许多便利，不妨考虑支持一下作者？  
[赞助作者](https://blog.izgq.net/donate.html)

## License

MIT
