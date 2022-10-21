| [📚 项目简介](#-项目背景) | [🌐 下载方式](#-下载方式) | [💠 功能介绍](#-功能介绍) | [📅 更新记录](#-更新记录) |
| --- | --- | --- | --- |
| [⚙ 安装运行](#-安装运行) | [💻 开发环境](#-开发环境) | [🔎 参考资料](#-参考文档) | [📓 笔记记录](#-笔记记录) |
| [🎯 常见问题](#-常见问题) | [💬 交流讨论](#-交流讨论) | [📝 关于脚本](#关于脚本) | [❤ 打赏赞助](#-打赏赞助) |

### 📚 项目简介

JZ_SubtitleHelper全称叫做"AE字幕助手"，专为AE视频特效软件开发的脚本。目的解决AE不能导入字幕格式文件问题，脚本支持常见的参数配置，具体用法请观看[AE字幕助手使用视频教程]()详细指南或[知乎文章]()。

> 通过查阅官方文档和热心网友帮助下顺利完成开发(`最新版已发布`)，在此感谢大家的帮助~<br>
> 这是非标准项目结构，仅用于脚本介绍及相关记录，源码就不公开啦(~~`不忍直视`~~)~ <br>
> 如果对您有帮助的话，别忘记点击右上角的Star哟~<br>

### 🌐 下载方式
| **云盘** | **下载链接** | **提取码** | **备注** |
| --- | --- | --- | --- |
| 阿里云盘 | [aliyundriver](https://www.aliyundrive.com/s/5GXcabZJd2e) | ***** | 点击[订阅](https://www.aliyundrive.com/er/u/1efa11ffc8a141f78bc6b13b2e549e28)立即获取最新版 |
| 蓝奏云盘 | [lanzou](https://shawlj.lanzoul.com/s/JZ-SubtitleHelper) | ***** | - |

### 💠 功能介绍
    
| **序号** | **功能列表** | **功能说明** | **版本** | **状态** |
| --- | --- | --- | --- | --- |
| 1   | 导入格式 | 支持SRT/ASS/SSA/LRC/TXT文本格式 | v1.2 | ✅ |    
| 2   | 批量导入 | 允许同时选择多个文件导入 | v1.0 | ✅ |
| 3   | 选择字幕 | 可选择保留和不导入的语言字幕 | v1.2 | ✅ |
| 4   | 字幕延时 | 脚本忽略字幕文件内置延迟Delay参数<br>由该选项设置字幕提前或延后时间<br>默认即按照字幕时间生成图层<br>负数/正数分别表示字幕提前或延后出现时间<br>若选择[从当前时间指示器导入]会叠加该参数 | v1.2 | ✅ |
| 5   | 字幕解析 | 此项只对LRC和TXT两种格式的双语字幕有效<br>LRC歌词双语字幕文本没有标准化<br>脚本提供手动设置双语字幕解析规则 | v1.2 | ✅ |
| 6   | 字幕区间 | 设置导入部分字幕区间行号<br>导入单文件最大行差不能超过1万行 | v1.2 | ✅ |
| 7   | 字幕位置 | 上下左右中九种组合方式<br>可根据字幕边距对位置进行调整 | v1.1 | ✅ |
| 8   | 字幕边距| 字幕图层到边界的距离<br>居正中时此项参数将被忽略 | v1.2 | ✅ |
| 9   | 图层标签 | 自定义字幕图层的标签和标记颜色 | v1.1 | ✅ |
| 10  | 图层标记 | 脚本创建字幕图层时自动生成标记 | v1.0 | ✅ |
| 11  | 生成方式 | 默认所有字幕按照关键帧合并成一个字幕图层<br>勾选后每组字幕都会创建新字幕图层 | v1.0 | ✅ |
| 12  | 覆盖图层 | 此功能谨慎使用，脚本创建图层名称是参照字幕行<br>若文本内含相同字幕(如歌词)，很可能被误替换<br>若按关键帧方式生成字幕图层则不受影响 | v1.0 | ✅ |
| 13  | 指定时间 | 默认从0秒生成文本图层(与字幕延时参数叠加)<br>选择后所有字幕均以时间指示器为基准生成字幕 | v1.0 | ✅ |
| 14  | 进度条 | 脚本顶部显示当前导入字幕执行进度 | v1.2 | ✅ |
| 15  | 预合成 | 将导入字幕进行预合成(可选) | v1.3 | ✅ |
| 16  | 更多扩展 | - | - | - |

### 📅 更新记录
| **序号** | **更新日期** | **发布版本** |
| --- | --- | --- |
| 1 | 2022/09/23 | [JZ_SubtitleHelper_v1.0](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.0 "JZ_SubtitleHelper_v1.0") |
| 2 | 2022/09/25 | [JZ_SubtitleHelper_v1.1](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.1 "JZ_SubtitleHelper_v1.1") |
| 3 | 2022/09/30 | [JZ_SubtitleHelper_v1.2](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.2 "JZ_SubtitleHelper_v1.2") |
| 4 | 2022/10/06 | [JZ_SubtitleHelper_v1.3](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.3 "JZ_SubtitleHelper_v1.3") |

### ⚙ 安装运行
> **温馨提示：Mac系统路径略有不同，并且可能存在兼容问题！**
+ 拷贝AE字幕助手脚本文件到 **`.../Adobe/Adobe After Effects xx/Support Files/Scripts/ScriptUI Panels/`** 目录
+ 打开AE编辑->首选项->常规->脚本和表达式->勾选允许脚本读写和访问网络
+ 打开AE窗口->点击脚本( **`JZ_SubtitleHelper_v1.3.jsxbin`** )

### 💻 开发环境
+ [Vscode](https://code.visualstudio.com/)
+ [Javascript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

### 🔎 参考资料
+ [ExtendScript docs](https://extendscript.docsforadobe.dev)
+ [Github docs](https://docs.github.com/)
+ [Adobe forum](https://community.adobe.com/)
+ [Adobe Jsx Samples](https://github.com/Adobe-CEP/CEP-Resources/tree/master/ExtendScript-Toolkit/Samples/javascript)
+ [AE脚本设计参考手册V1.0](https://github.com/shawlj/JZ_SubtitleHelper/blob/7cce2cec8a14c8e4f20f1f2f011fff552308d32b/assets/%E3%80%8AAE%E8%84%9A%E6%9C%AC%E8%AE%BE%E8%AE%A1%E5%8F%82%E8%80%83%E6%89%8B%E5%86%8CV1.0.0%E3%80%8B.pdf)

### 🎯 常见问题
Q：导入字幕为什么乱码？<br>
A：请检查文件编码格式是否为UTF-8或内容存在乱码<br>
...

### 🏷 其他说明（待处理）
> 脚本未加入国际化，面板界面为中文语言环境，若脚本在其他语言环境使用过程中出现问题请反馈。
> 小技巧1：双击关于的名字打开日志文件（作者自用，现开放共享）
> 小技巧2：选中图层双击图层创建标签快速删除选定区域内的所有标记（已占用）
> 小技巧3：选中某图层点击导入时默认将在选中图层上方开始生成字幕图层
> 小技巧5：点击面板左侧静态文本重置右侧参数
> 点击面板关于按钮下方链接打开本脚本项目主页
> 隐藏小技巧4：双击颜色标签随机更换选中图层的标签颜色
> 更多小技巧暂不公开~

<details open>
  <summary>
    <h3 >关于脚本</h3>
  </summary>
  <ul>
    <li>脚本由作者开发完成，所有功能完全免费！</li>
    <li>脚本虽微不足道，禁止任何倒卖行为！</li>
    <li>欢迎转发分享给更多小伙伴们使用哟！</li>
    <li>若您通过购买获得，请您立即退款差评并举报！</li>
  </ul>
</details>

### 💬 交流讨论
[![](https://img.shields.io/static/v1?labelColor=000000&label=&message=Shawlj&color=FFFF00&style=flat&logo=github&logoColor=FFFFFF)](https://github.com/shawlj)
[![](https://img.shields.io/static/v1?label=&message=%E5%BE%AE%E5%8D%9A&color=e6162d&style=flat&logo=sinaweibo&logoWidth=100%&logoColor=FFFFFF)](https://weibo.com/shawlj)
[![](https://img.shields.io/static/v1?label=&message=%E5%BE%AE%E4%BF%A1&color=07C160&style=flat&logo=wechat&logoColor=FFFFFF)](https://space.bilibili.com/320001004)
[![](https://img.shields.io/static/v1?label=&message=%E7%9F%A5%E4%B9%8E&color=0066ff&style=flat&logo=zhihu&logoColor=FFFFFF)](https://www.zhihu.com/people/shawlj)
<a href="mailto: shawlj@yeah.net"><img src="https://img.shields.io/static/v1?label=&message=%E9%82%AE%E7%AE%B1&color=blueviolet&style=flat&logo=gmail&logoColor=FFFFFF"></a>
[![](https://img.shields.io/static/v1?label=&message=B%E7%AB%99&color=f45a8d&style=flat&logo=bilibili&logoColor=FFFFFF)](https://space.bilibili.com/320001004)
[![](https://img.shields.io/static/v1?labelColor=orange&label=%E5%8F%8D%E9%A6%88&message=5&color=orange&style=social&logo=github)](https://github.com/shawlj/JZ_SubtitleHelper/issues)


### ❤ 打赏赞助
<img src="https://github.com/shawlj/shawlj/blob/fe2a70b487830ba9005f0eab16f8555260ca6e46/sponsor/sponsor.jpg" width="50%">
