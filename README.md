## 联系方式

- 手机 : 8618316966947
- Email : 00g0@qq.com
- Wechat : dajia18316966947
- Cocos Store : 521011

## 个人信息

- 姓名 : 张嘉俊
- 学历 : 大专
- Gitee : https://gitee.com/dajia9404
- 荣誉奖励 : 15年广轻院16届数字媒体大赛第一名
- 期望职位 : 游戏前端开发工程师
- 工作年限 : 6年

## 技能清单

- 引擎：cocoscreator/egret/nodejs
- 语言: typescript/javascript/html/css
- 框架: cocos-oops-framework/pure-mvc
- 数据库: mysql
- 版本管理: git/svn
- 图集整理: texture merge/texture packer/bitmap font

## 项目经历

### 3D冰雪大挑战

3D冰雪大挑战是一款利用Cocoscreator开发的3D自走棋策略游戏。本人参与项目的维护，上线等流程

#### 我负责过

- 修改主界面，游戏，结算，排行，角色成长，离线时长，挂机时长，关卡选择，boss提示等界面
- 修改怪物行为树，怪物寻路，怪物攻击，怪物受击，怪物死亡，死亡掉落，Astar，红点等模块逻辑
- 利用cocoscreator导出android studio项目，结合的gradlew assemble和jenkins提供自动打包方案
- 提供根据Screen width和Screen height的动态高低资源适配等方案
- 提供策划需求新建引导枚举，并实现对应的新手引导功能
- 根据TapADN提供的方案，修改cocoscreator导出的android工程原生java代码，实现项目广告功能
- 正则查找中文字符和遍历找中文图片资源，替换并实现location

#### 项目成果

- 国外的安卓vivo，oppo低端机占比21%，所以必须做游戏低端机优化，可以有效避免用户流失
- 游戏国内内测时有百分之三十留存，给管理人很大的信心做好游戏


### 宇游

宇游一款利用egret + erlang开发的休闲游戏。本人参与项目的，开发，维护，发布等流程

#### 我负责过

- 修改排行榜，结算，分享，加入房间，创建房间,背包,聊天等界面
- 修改背包，道具，角色，技能，特效管理等模块逻辑
- 利用nodejs的fs中间件，裁剪exml中x,y,scalex,scaley小数点的工具
- 修改图集texture merge图集打包的思路，将源文件json修改源文件merg
- 将配置表json结构，改为列表结构，优化加载时间
- 将屏蔽字库转为字符串，分割并遍历该字符返回标准的发言

#### 项目成果

- 目前游戏仍在微信小游戏平台运营，微信搜索宇游即可
- 游戏月流水约二十万，每日在线约三百人，同时在线约三十人


### 3D乖离子

乖离子是一款利用Laya + fairygui开发的3D自走棋策略游戏。本人参与项目的研发，维护，上线等流程

#### 我负责过

- 搭建登录，创建亚瑟，加载，亚瑟布阵，战斗，结算，聊天，世界，闯关，抽奖等界面
- 实现背包，聊天，亚瑟成长，骑士成长，骑士分解等，播放战斗，文字对话等模块
- 利用Laya提供的资源加载器，读取角色模型，特效模型制作编辑器，并添加策划配置导出成前端可用的配置格式
- 利用Glsl在property提供两个Vec4颜色，并在着色阶段采样混合外部提供的颜色变量，达到字体渐变Shader
- 利用nodejs将屏蔽字库修改成树状结构并打包成json格式，运行时外部字符串逐字匹配该树，完成高效屏蔽字逻辑
- 利用红点树绑定红点状态，分离ui界面和组件，实现高效红点模块

#### 项目成果

- 了解并研发角色编辑器，技能编辑器，特效编辑器
- 屏蔽字库可以进行预先处理成树状结构，运行时根据传入字符串进行读取，避免暴力遍历

### 剑荡乾坤

#### 项目描述

剑荡乾坤是一款用egret + fairygui开发的中量级仙侠类Arpg游戏。本人参与了该项目的模块开发，维护流程。

#### 我负责过

- 参与个人Boss，全民Boss，魔王降临，天神装备，图腾界面等界面搭建
- 实现Arpg游戏背包，红点等模块的开发
- 维护上线游戏，跟进修复线上问题
- 接微信SDk，利用nodejs读取脚本中的私有变量，并缩短私有变量的命名,又利用分包策略将核心逻辑打包成库放入微信子包
- 参与优化游戏终端的发热问题，优化各模块中的遍历次数，将红点更新逻辑改为事件触发并缓存，删除多余的配置字段和公式化成长数值

#### 项目成就

- 每日八百登录,同时在线三十人，百分之二十留存(君海反馈)
- 于2021年君海因为版号问题关闭运营

### 暖暖蛋糕房

#### 项目描述

暖暖蛋糕屋是一款自研经营竞技游戏,前端使用CocosCreator,后端使用nodejs。参与了该项目的研发，上线发布等流程。

#### 我负责过

- 搭建加载,主界面，游戏，结算等界面
- 根据cocoscreator提供的spine接口，封装spine动画，外部只需调用动画id即可完成播放
- 实现游戏中顾客生成时动画，所需蛋糕动画，以及动画逻辑
- 利用双向链表将蛋糕material串联，串联合成目标蛋糕并拖拽到指定顾客完成需求，从而提交到nodejs得分
- 利用websocket协议和json数据结构，进行前后端数据同步，并于服务端生成客户端所需蛋糕并下发给前端
- 利用cocoscreator打包html5命令行，调用命令行并使用windows下zip命令进行压缩封包，再利用filezilla部署到云服务器提供外部访问

#### 项目成就

- 每日六百登录,同时在线三十人，百分之四十一留存
- 为团队提供了广告收入，铺垫了下一个项目

### 欢乐祖玛

#### 项目描述

欢乐祖玛是一款使用CocosCreator研发的自研祖玛消除游戏。参与了立项，需求列表，任务分配，跟进开发以及流程发布上线等流程。

#### 我负责过

- 搭建主界面，游戏，关卡，宝箱，七日奖励等界面
- 实现玩家子弹的随机产生，旋转以及发射等逻辑
- 利用多段贝塞尔曲线分割，在update中叠加插值，实现祖玛球沿着配置好的贝塞尔点进行运动
- 实现祖玛球冰冻，闪电，缓速等技能
- 接微信小游戏SDK中登录，分享，排行，广告,将原先webp格式的背景图更换为jpg格式兼容wechat runatime
- 利用贝塞尔算法和cocoscreator的可视化，固定画布大小的前提下让策划可拖拽贝塞尔点，并生成运动曲线导出配置给前端用
- 利用cocoscreator打包html5命令行，调用命令行并使用windows下zip命令进行压缩封包，再利用filezilla部署到云服务器提供外部访问

#### 项目成就

- 每日一千登录,同时在线八十人，百分之四十一留存
- 为团队提供了丰厚的广告收入，为公司接下来的项目研发打下坚实的基础

## 工作经历
|年份|公司|职位|公司简介|
|---|---|---|--|
2021.3 - 2022.6 | 佛山宇游信息科技有限公司|egret游戏前端开发|广东宇游科技是一间专注休闲游戏自研公司，公司秉持高端、前沿、精准、求实的品牌精神提供完美的服务。
2020.7 - 2021.1 | 广州蜃龙信息科技有限公司|Laya游戏前端开发|广州蜃龙游戏设计有限公司成立于2017年，成员均由行业内资深“老兵们”创立，是一支专注于原创3D次世代游戏开发的游戏团队
2019.1 - 2020.6 | 广州光娱信息科技有限公司|egret游戏前端开发|光娱游戏成立于2015年，是一家专注于手机游戏研发和运营的新锐游戏企业。研发出《剑仙缘》、《奇迹屠仙》、《破雪刃》等多款千万级产品和破2亿产品《九州行》
2018.3 - 2019.12 | 广州峻峰信息科技有限公司|游戏前端开发|广州峻峰科技有限公司是一家专注于移动游戏、H5游戏的专业游戏研发商。主攻各类精品化的轻游戏和小游戏产品，也涵盖卡牌类等中度游戏产品研发

## 开源项目

- exml文件替换多余小数点后缀
    - 解决exml中小数点长后缀导致的无用字符过多问题 ： https://gitee.com/dajia9404/exml
- Texture-Compator,美术资源基于cocoscreator的有损压缩png方案
    - 项目源码地址：https://gitee.com/dajia9404/texture-compator
- cocos creator 文本横轴渐变Shader着色方案
    - 该方案上架Cocos store , 商品地址 ：https://store.cocos.com/app/detail/5756 
- cocos creator 文本纵轴渐变Shader着色方案
    - 该方案上架Cocos store , 商品地址 ：https://store.cocos.com/app/detail/5832
- cocos creator 在Shader中利用uv偏移实现背景无限滚动方案
    - 该方案上架Cocos store , 商品地址 ：https://store.cocos.com/app/detail/5779
- cocos creator 在Shader中利用uv进行镜像翻转节省美术资源
    - 该方案上架Cocos store , 商品地址 ：https://store.cocos.com/app/detail/5767
- cocos creator 三色渐变shader文本方案
    - 商品地址 ：https://store.cocos.com/app/detail/5860

## 自我评价

- 有较强的责任心，良好的沟通能力和团队协作能力
- 喜欢专研新技术，喜欢封装各种各样的工具库为已所用
- 有良好的抗压能力


## 感谢你花时间阅读小弟的简历，期待有机会与你共事♥