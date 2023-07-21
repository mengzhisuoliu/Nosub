#### Nosbu V2新版正在开发中，V2的版本基于QT.5和C++20，完全cmake构建。


#### Nosub是一个全新的字幕软件 [下载地址](https://github.com/patui/Nosub/releases)

>开发者愿景：让新手上字幕真正变得简单；
---

###### （一）Nosub的支持平台：
- [x] Windows
- [ ] MacOS (暂时不支持，请耐心等待)
- [ ] Linux (暂时不支持，请耐心等待)

###### （二） Nosub的核心组件：
- [x] 视频播放器
- [x] 无限滚动时间轴（波形图）
- [x] 无限滚动字幕编辑器；（字幕切割，合并，删除，修改，调整时间）

###### （三） Nosub的核心功能：
- [x] 音频降噪处理；(来自WebRTC)
- [x] 离线语音自动切割；(来自WebRTC)
- [x] 语音识别生成字幕；
- [x] 字幕快照；（解决传统字幕软件闪退丢失字幕的问题）
- [x] 视频压制；（异步任务队列，支持批量压制）

###### （四）Nosub已经支持的语音识别引擎列表：
```
语音文件转写引擎支持列表：（即音/视频直接转字幕）
1. 阿里云语音文件转写；
2. 讯飞语音文件转写；
3. 腾讯语音文件转写；
4. 百度语音文件转写；
```
语音文件转写价格以及账号配置可以参考这篇下面的两个：
- configcore.json的配置文件说明：[configcore.json的配置文件说明](https://github.com/patui/Nosub/blob/master/configcore.md)
- nosub beta7更新说明：[nosub beta7更新说明](https://github.com/patui/Nosub/releases/tag/1.0beta7)

###### （五）Nosub已经支持的字幕翻译引擎列表：


###### （六）Nosub用到的开源库：(截止到2020年10月1日)
- QT 跨平台的GUI库；（QT是一个综合C++库，不仅仅是GUI）
- CppRestSDK 微软C++ 11风格的HTTP请求库；
- FFmpeg 音视频解码库；
- H.264  H264编解码库；
- H.265  H265编解码库；
- Mp3lame Mp3编解码库;
- Fdk-aac AAC编解码库;
- Libass 字幕渲染库;
- Uchardet 文本编码检测库；
- Iconv   文字编码转换库;
- Fontconfig 字体配置库;
- Freetype   字体渲染库;
- OpenSSL SSL通信加密库;
- WebRTC Chrome实时音视频库；
- SDL2 多媒体渲染库；
- SDL2-ttf 字幕渲染库;
- Spdlog 日志记录库;
- MediaInfo 查看音视频信息库；





[Nosub开发者推荐的其它字幕制作平台](https://github.com/patui/Nosub/blob/master/推荐的字幕制作平台.md)
