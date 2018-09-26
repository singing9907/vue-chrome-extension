## 商店截图
![image](https://github.com/zangse/vue-chrome-extension/blob/master/screenshots/chrome-extension.png)
### 截止2018年9月26日 书签管理用户数 1200+，扩展管理用户数1300+
## chrome 扩展文档

## Chrome-extension（基于vue.js开发Chrome扩展）

### 扩展1: hiBookMark( 欢迎吐槽)

#### 安装

chrome商店安装（需翻墙）
 [点击这里获取](https://chrome.google.com/webstore/detail/hibookmark/kimcgbcdngdnggfmkjdmmjceijnkcjmd?hl=zh-CN&gl=HK)

#### 介绍

-   本项目由vue-cli编译生成,webpack.config.js中配置了双入口，分别配置了popup页面和管理页
-   实现了书签的快速查找，只需在浏览器内按下 ctrl+B(mac为command+B)，即可唤出搜索页，输入书签名称或部分网址，回车即可获取搜索结果
-   书签管理页可以管理书签，移动、删除书签（支持批量操作），查看最近浏览历史等

#### 更新记录

##### 2017-11-9更新

##### 待修复bug

-   [x] 删除书签没有更新列表（建议更新书签后，根据操作刷新页面）
-   [x] 新建文件夹后，当前选中的文件夹消失
-   [x] 书签排序问题，考虑文件夹在前
-   [x] 书签栏左侧当前位置应该标明
-   [x] 选中后，打开某一个书签，返回后，选中的丢失

##### 2017-11-13更新

-   [x] 文件夹和书签重命名（编辑问题）
-   [x] 优化搜索过程，实现实时搜索
-   [x] 修复其他已知问题

##### 2017-11-16更新

-   [x] 增加操作提示
-   [x] 搜索后，popup层（弹出界面）支持tab切换选中，然后按enter键可以打开新页面

##### 2017-11-29更新

-   [x] 国际化，支持英文

##### 2017-12-8更新

-   [x] 修复已知bug

##### 2018-1-2 更新

-   [x] 弹出层搜索结果，取消tab键行为，可使用上/下键选择，enter键从新标签页打开
-   [x] 弹出层搜索结果，可使用ctrl+数字键（1~9）直接从新标签页打开书签
    ##### 2018-05-24更新
-   [x] 解决弹出层input框未聚焦问题，美化侧边滑动栏

##### 待优化

-   [ ] 增加书签导入导出功能
-   [ ] 增加书签过渡动画
-   [ ] 考虑增加拖拽效果
-   [ ] 检查死链
-   [x] 滑动时限定区域滑动
-   [x] 优化滚动条样式
-   [x] 优化小屏幕浏览器展示列数
-   [ ] 新建文件夹后，如果在下方，没有定位到下方
-   [x] 搜索结果自动聚焦第一条，上下键可切换，Ctrl+数字键可选择（直接打开？)
-   [ ] 增加配置页（配置书签栏是否自动展开，管理页书签的默认展开方式）
-   [ ] 增加新标签页（可配置是否开启）
-   [ ] 记住上次打开位置（可配置是否开启）
-   [ ] 打开当前文件夹自动关闭其他文件夹（可配置是否开启）
-   [ ] 解决快捷键冲突，实现自定义快捷键
-   [ ] 优化安装包体积，压缩包体积过大
-   [ ] 考虑书签移动支持拖拽模式（单个或多个）（基于一个网友的建议）

### 扩展2: 扩展管理

#### 安装

chrome商店安装（需翻墙）
( [点击这里获取](https://chrome.google.com/webstore/detail/%E6%89%A9%E5%B1%95%E7%AE%A1%E7%90%86/jijileelaefjahodboljljdgfpbjjlac?hl=zh-CN&gl=HK) 欢迎吐槽)

#### 功能

-   可对单个扩展启用/禁用
-   可一键关闭或启动所有扩展
-   可查看扩展信息(跳转至商店)
-   可配置有配置项的扩展
-   可以移除扩展
-   添加了一些快捷方式

#### 更新记录

##### 2018-1-10更新

##### 新增常用扩展模式

可设置常用扩展，并在工具栏中切换模式

##### 2018-2-25更新

修改插件名称

##### 2018-3-12更新

增加搜索模式，可在列表页搜索扩展
增加badge，显示当前已启用扩展数量

##### 2018-6-26更新
 将扩展以常用扩展排序(2018-3-31)


#### 需求

-   搜索模式，顶部加搜索框（可配置是否开启，首次安装扩展超过15个默认开启）
-   增加更多的按键操作（可配置是否启用）
-   将扩展以常用扩展和英文字母排序(2018-3-31)

#### more

更多优化和建议，欢迎大家提出
最近也在考虑开发更多实用的扩展，如果有小伙伴有相关的想法，可以在issues中提出
