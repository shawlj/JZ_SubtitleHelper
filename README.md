
## JZ_SubtitleHelper全称叫做"AE字幕助手"，专为AE视频特效软件开发的脚本，目的是代替创建字幕这种重复无聊操作，将更多时间精力用在有意义的地方~<br>
通过查阅官方文档和网友帮助下，不断改进优化已实现当下需求，未来不排除会进行更新升级，拭目以待~<br>
非标准工程项目，只是用于脚本介绍及相关记录，源码就不公开啦(~~```不忍直视```~~)~ <br>
如果对您有帮助的话，别忘记点击右上角的Star哟~<br><br>

### 🔗 下载地址：www.aliyundriver.com/shawlj/JZ_SubtitleHelper_v1.1
加入阿里云盘分享地址：欢迎关注该账号，及时了解更新动态


### 💠 功能介绍
    
| **序号** | **功能列表** | **功能说明** | **对应版本** | **状态** |
| --- | --- | --- | --- | --- |
| 1   | 兼容多种字幕格式 | 支持SRT/ASS/LRC文本格式等 | v1.2 | ✅ |    
| 2   | 批量导入字幕文本 | 允许同时选择多个文件导入 | v1.2 | ✅ |
| 3   | 选择导入单语/双语字幕 | 可选择保留和不导入的语言字幕 | v1.2 | ✅ |
| 4   | 调整字幕提前或延后时间 | 脚本忽略字幕文件内置延迟Delay参数<br>由该选项设置字幕提前或延后时间<br>默认即按照字幕时间生成图层<br>负数/正数分别表示字幕提前或延后出现时间<br>若同时选择[从当前时间指示器导入]会叠加该参数 | v1.2 | ✅ |
| 5   | 自定义双语字幕分割规则 | 此项只对LRC和TXT两种格式的双语字幕有效<br>LRC歌词双语字幕文本没有标准化<br>脚本提供手动设置双语字幕解析规则 | v1.2 | ✅ |
| 6   | 选择导入字幕区间 | 设置导入部分字幕区间行号<br>单个文件导入最大不能超过1万行 | v1.2 | ✅ |
| 7   | 设置字幕位置及对齐方式 | 九宫格布局位置<br>可根据字幕边距对位置进行调整 | v1.1 | ✅ |
| 8   | 字幕边距参数相对位置调整 | 字幕图层到边界的距离<br>居正中时此项参数将被忽略 | v1.2 | ✅ |
| 9   | 设置生成图层标签及标记颜色 | 自定义字幕图层的标签和标记颜色 | v1.1 | ✅ |
| 10  | 生成文本图层创建标记 | 脚本创建字幕图层时自动生成标记 | v1.0 | ✅ |
| 11  | 按行生成或关键帧生成文本图层 | 默认所有字幕按照关键帧合并成一个字幕图层<br>勾选后每组字幕都会创建新字幕图层 | v1.0 | ✅ |
| 12  | 覆盖已存在图层 | 此功能暂停使用，脚本创建图层名称参照字幕行<br>若文本内含相同字幕(如歌词)，很可能被误替换<br>若按关键帧方式生成字幕图层则不受影响 | v1.0 | ⚠ |
| 13  | 按指定时间指示器导入 | 默认从0秒生成文本图层<br>选择后所有字幕均以时间指示器为基准生成字幕 | v1.0 | ✅ |
| 14  | 导入进度条展示 | 脚本顶部显示当前导入字幕执行进度 | v1.2 | ✅ |
| 15  | 更多扩展 | - | - | - |


### ⚒ 安装方式
> 将脚本拷贝到AE安装目录下```.../Support Files/Scripts/ScriptUI Panels```即可<br>
> 启动AE点击顶部菜单窗口找到JZ_SubtitleHelper.jsx脚本


### 📅 更新记录
| **序号** | **发布日期** | **发布版本** |
| --- | --- | --- |
| 1 | 2022/09/23 | [JZ_SubtitleHelper_v1.0](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.0 "JZ_SubtitleHelper_v1.0") |
| 2 | 2022/09/25 | [JZ_SubtitleHelper_v1.1](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.1 "JZ_SubtitleHelper_v1.1") |
| 3 | 2022/09/30 | [JZ_SubtitleHelper_v1.2](https://github.com/shawlj/JZ_SubtitleHelper/releases/tag/JZ_SubtitleHelper_v1.2 "JZ_SubtitleHelper_v1.2") |


### 🎯 常见问题
Q：导入字幕为什么乱码？<br>
A：请检查文件编码格式是否为UTF-8或内容存在乱码<br>
...


### 🔎 参考文档
+ [ExtendScript官方开发手册](https://extendscript.docsforadobe.dev)
+ [AE脚本设计参考手册V1.0.0]()


### 🏷 其他说明（待解决）
> 脚本未加入国际化，面板界面为中文语言环境，若脚本在其他语言环境使用过程中出现问题请反馈。


<details open>
  <summary>
    <h3>关于脚本</h3>
  </summary>
  <ul>
    <li>脚本由作者开发完成，所有功能完全免费，不收取任何费用，初次使用时界面也会弹出公告！</li>
    <li>脚本虽微不足道，但未经作者授权请勿将其上传至任何商业网站进行售卖牟利！</li>
    <li>若您要转发到其他非盈利网站时也要记得注明出处哦！</li>
    <li>若您是通过其他渠道购买所得，请立即退款差评并举报！</li>
  </ul>
</details>


### 💬 交流反馈
[![](https://img.shields.io/static/v1?labelColor=000000&label=&message=Shawlj&color=FFFF00&style=flat&logo=github&logoColor=FFFFFF)](https://github.com/shawlj)
[![](https://img.shields.io/static/v1?label=&message=微博&color=e6162d&style=flat&logo=sinaweibo&logoWidth=100%&logoColor=FFFFFF)](https://weibo.com/shawlj)
[![](https://img.shields.io/static/v1?label=&message=微信&color=07C160&style=flat&logo=wechat&logoColor=FFFFFF)](https://space.bilibili.com/320001004)
[![](https://img.shields.io/static/v1?label=&message=知乎&color=0066ff&style=flat&logo=zhihu&logoColor=FFFFFF)](https://www.zhihu.com/people/shawlj)
[![](https://img.shields.io/static/v1?label=&message=邮箱&color=blueviolet&style=flat&logo=gmail&logoColor=FFFFFF)](shawlj@yeah.net)
[![](https://img.shields.io/static/v1?label=&message=B站&color=f45a8d&style=flat&logo=bilibili&logoColor=FFFFFF)](https://space.bilibili.com/320001004)
[![](https://img.shields.io/static/v1?labelColor=orange&label=反馈&message=5&color=orange&style=social&logo=github)](https://github.com/shawlj/JZ_SubtitleHelper/issues)


### ❤ 打赏通道
~~暂未开通~~
