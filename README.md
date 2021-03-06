TransIt
===========

让划词翻译更简单

#### 功能列表

- 页面英文划词翻译 
- 连续对多个单词进行划词翻译
- 按住 Shift 键可以对超链接中的文本进行划词翻译
- 调整页面划词翻译结果显示的时间长短
- 适应更多的页面，包括 Iframe 嵌套
- 支持在窗口边缘和选词附近两种方式显示翻译结果

#### 更新历史

V1.3

- 添加独立的偏好设定页面，并精简弹出窗口
- 鼠标移上页面翻译结果时，结果面板不消失，移出后重新计时
- 解决页面翻译结果被 Chrome 搜索框遮盖的问题

V1.2 - 2014-05-30

- 支持对 IFRAME 中的内容进行划词翻译
- 支持对使用了 Turbolinks 技术的网站进行划词翻译
- 支持在划词内容附近显示翻译结果
- 限于有道翻译 API 的使用协议，移除缓存功能

V1.1 - 2014-02-16

- 页面划词时，如果一个单词的翻译还未消失，再次对该词划词，不会重复翻译
- 修正部分单词没有查找到翻译仍然显示翻译结果的问题
- 页面划词翻译结果增加透明和淡入淡出效果
- 为翻译结果添加音标（如果有）
- 更新链接文本划词翻译的描述
- 解决频繁划词导致翻译结果跑出屏幕的问题（支持使用滚轮滚动）

---

TransIt 离不开大家的贡献，如果对 Chrome 扩展开发有兴趣，请了解[如何参与项目]及[贡献者列表]。

[如何参与项目]: https://github.com/GDG-Xian/crx-transit/wiki/HowToContribute
[贡献者列表]: https://github.com/GDG-Xian/crx-transit/wiki/Contributors

---

本项目遵循 MIT 协议，请参阅 LICENSE 文件

---

Powered by [有道翻译](http://fanyi.youdao.com/openapi?path=data-mode)
