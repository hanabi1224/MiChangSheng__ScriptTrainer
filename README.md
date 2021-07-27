# 觅长生内置修改器

**注意：
1.本修改器禁止用于任何收费项目中！！
2.该修改器需要BepInEx 5.4.5版本（不能太高）**

------------

挖个新坑，目前是初始版本功能还不是很多，以后慢慢加；
如遇到Bug，这是正常现象，请反馈给我。

源码地址：https://github.com/3DMXM/MiChangSheng__ScriptTrainer

### 安装方法：
 - 先安装 [BepInEx 5.4.5 x86](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.5 "BepInEx 5.4.5 x86")
 - 将“ScriptTrainer.dll”放入“BepInEx\plugins”中
 - 进游戏按“F9”打开菜单
 
> 启动快捷键可以在“BepInEx\config\aoe.top.MiChangSheng.ScriptTrainer.cfg”中修改

### 功能

**基础功能**
- 增加/减少/修改 现金
- 增加/减少/修改 宁州声望
- 增加/减少/修改 海域声望
- 一键修为全满
- 一键血量全满

**抽卡**
- 随机抽一张卡
- 随机抽三张卡
- 随机抽三张相同的卡
- 抽三张指定属性的卡

**玩家属性**
- 修改玩家年龄
- 修改玩家寿元
- 修改玩家资质
- 修改玩家神识
- 修改玩家悟性
- 修改玩家遁速
- 修改玩家心境
- 修改玩家丹毒
- 修改玩家灵感
- 修改玩家修为
- 修改玩家生命值/最大生命值
- 修改玩家五行灵根属性

**门派**
- 修改玩家当前门派
- 修改玩家在门派中的职位 （我只有竹山宗可以改职位，可能是我境界不够）
- 修改玩家门派声望 （每个门派都有单独的声望）

> 门派功能我还没有完全测试，可能会有一些未知的Gug，如果你遇到了奇怪的Bug，请反馈给我

**悟道**
- 修改12个属性的悟道值
- 修改悟道点
- 单独改满悟道值

**物品**
现已完善物品获取功能。
- 可按类型搜索物品
- 可按名称搜索物品
- 可设置获取数量
- 可手动输入ID获取物品

**NPC选项**
- 修改NPC年龄
- 修改NPC寿命
- 修改NPC血气
- 修改NPC资质
- 修改NPC悟性
- 修改NPC好感度
- 修改NPC情分
- 修改NPC遁速
- 修改NPC神识
- 修改NPC修为




### 更新日志
v1.2.0:
- 更新NPC相关选项

v1.1.0:
- 更新完善获取物品功能

v1.0.1：
- 修复遁速和神识会一直增长的问题
- 修复在进入游戏之启动修改器会出错且之后无法再启动修改器的问题

v1.0.0：
- 初始发布