# music-Website
该网站是仿网易云的，网易云音乐网页端样式比客户端简陋，并且没有歌词滚动等功能，针对这两个开发了这个网站
### 技术栈

`Vue3`、`Vue-Router`、`Vite`、`TypeScript`、`Axios`、`Element-Plus`、`Pinia` 、`Less`

### 实现的功能

1. 播放歌曲时,歌词滚动
2. 上一首和下一首播放
3. 歌曲音量调整
4. 歌曲排行榜
5. 播放器
6. 用户扫码登录
7. 自动构建和部署

### 未实现的功能

这是收集了网上用户的反馈后想要改进的

- 歌曲排序功能
- 不同歌曲的音量高低差异过大，需要进行适当的调整

## 入门

需要先克隆[NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)到本地，然后进入该项目文件夹运行一下命令启动后台服务（可以更换想要的端口）

```
node app.js
```

克隆本仓库到本地

安装依赖

```
npm i
```



启动开发环境

```
npm run dev
```

接口：[网易云音乐Api](https://github.com/Binaryify/NeteaseCloudMusicApi)提供Api接口服务
