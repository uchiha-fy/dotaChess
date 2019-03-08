# dotaAutoChess
[传送门](https://uchiha-fy.github.io/dota_AutoChess/)
### 逐步完善的刀塔自走棋相关查询
***
+ 英雄查询(点击即可查看所选英雄属性及相关羁绊)
+ 种族查询(点击即可查看该种族的所有英雄)
+ 职业查询(同上)
+ 羁绊查询(点击开启则开启羁绊查询模式，最多点选10人口即10个英雄，再次点击取消选中该英雄，关闭则推出羁绊查询模式)
***
#### 页面相关
* 单页面全屏(无滚动条)
* 简单添加媒体查询，1000px以上视为PC端，以下为移动端
* 移动端未适配所有型号手机，自己的荣耀10没问题，嘻嘻
* Chess中英雄查询可模糊查询，但未添加输入框(防止错误输入)。控制台暴露chess实例，可通过chess.getHero(heroName) eq:chess.getHero('龙') return ['精灵龙','冥界亚龙','龙骑士']
* Chess中装备及装备合成(目前仅添加函数，可通过控制台chess.equipment查看，eq:chess.equipment.detect(['虚无宝石','治疗指环','虚无宝石','治疗指环']) return ['刷新球'] )
***
#### 后续
+ 装备相关已写好但未展示(与英雄相关的切换待添加，装备合成函数最终物品显示顺序待改进)
+ 添加各类玩法的阵容推荐
+ 玩法克制(没思路、搁置)
***
#### 当前版本
* 已完成官方2019-03-05更新
***
#### 个人尝试
* 6地精是强，但总感觉不好胡...强行6地精，凉的别太快(2019-03-06)
