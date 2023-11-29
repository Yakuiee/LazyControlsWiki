# Don't Starve Together Mod Lazy Controls

- 功能讲解系列视频链接：https://space.bilibili.com/326122271/channel/seriesdetail?sid=534917
- 本 Mod 全部设置在模组配置上方都能看到中文介绍，麻麻再也不用担心我看不懂英文了
- 每个功能可以独立开关

## 功能一览

#### 对 [排队论 Action Queue Reborn](https://steamcommunity.com/sharedfiles/filedetails/?id=1608191708) 的亿些改动

- auto collect 模式不会捡起 提灯、背包、包裹、可装备的物品、书、世界唯一物品（例如切斯特眼骨）、扇子、老麦的书、红鞭炮、信号弹、贝壳钟、灰烬、所有类型的月眼、开孔月石、暖石了
- auto collect 模式不允许采摘动作
- auto collect 模式收获仅允许收获晒肉架
- 添加左键动作: 使用钥匙批量开克劳斯包、读书、谋杀、喂宠物、劈(海难砍刀的动作)、种地、往堆肥桶里塞东西、跟植物聊天、变异(万圣节药水)、给树应用肥料、水壶灭火
- 添加右键动作: 点燃、拿取物品(用来摘食人花)、捡起(雕像)
- 刮刀可以刮海草怪了
- 开帆自动 Ho!
- 不允许用修船工具和羽毛笔填燃料
- 批量吃东西仅在只选中了玩家的情况下才会
- 设置 捡起、摘、喂食玩家、开启/关闭( 通常是开/关灭火器 )、使用钥匙开克劳斯包、读书、点燃、拆包裹、喂玩家、重置陷阱、画小木牌、谋杀、喂宠物 到无工作延迟类
- 将食人花加入 easy_stack 列表
- 将破损远古塔加入 entity_morph 列表
- 种种子间距改为 4/3(一块地 9 个)
- 添加排队耕地&浇水
- 开启 auto collect 之后用绿杖分解睡袋会自动捡金丝雀
- 绿杖分解可堆叠物品可以一直分
- 种东西自动捡种子 (建议使用 [Planter](https://steamcommunity.com/sharedfiles/filedetails/?id=2156052731))
- 可以排队灌水了
- 排队论会在用完当前物品后会尝试从所有打开的容器里寻找同类物品
- 自动翻脚印
- 自动给风暴科学家零件
- 无尽重复模式，游戏内按键开启，开启后会在下一次选择目标之后持续选择人物周围同类可执行同样动作的实体 ( 默认关闭 )
- 添加找猫猫支持
- 可以排队用不老表
- 选择附近实体的键现在优先选择右键动作了
- 选择附近实体排除开关灭火器
- 支持喂睡着的鸟 (拿出来再放回去)

#### 重复丢弃（默认为 Normal Drop 即丢到人物当前站的位置）

- shift + 右键双击物品丢弃所有同类物品
- shift + ctrl + 右键双击物品重复单个丢弃所有同类物品
- shift + 双击地面丢弃鼠标上物品
- 丢弃队列可以使用任何移动、攻击、鼠标、动作键来取消
- 选项 Drop On Grid A 代码来自于 [Advanced Controls](https://steamcommunity.com/sharedfiles/filedetails/?id=1601725838)，功能同该 mod 的丢弃至格点
- 选项 Drop On Grid B 为仅鼠标左键丢弃物品时丢弃至格点 ( 默认选项 )

#### 批量移动物品 -- 舒服 (懒人) 移动物品

- shift + 左键双击批量移动物品至对应容器，如果批量移动到打包袋中会自动打包
- 可以设定一个快捷键来代替按 "打包" 按钮

#### 先进[打包纸](url=https://steamcommunity.com/sharedfiles/filedetails/?id=2055431789)和厨具

- 在开着箱子的时候打包现在不会先进箱子 沃利的调味站同理

#### 更好的影织者战斗

- 在影手存在的时候按攻击键不会锁定到影织者

#### 快速调整镜头

- shift + 滚轮快速 放大 / 缩小 镜头

#### 不捡恶魔花

- 不捡恶魔花，包括鼠标左键及空格键
- 可设置选项：空格键不捡花

#### 坐井观天 ( 默认关闭 )

- 鼠标点击时钟来开启/关闭洞穴时钟

#### 重复比鱼 使用抓娃娃机 ( 默认关闭 )

- 按下按键自动往鱼类比较器里面塞鱼，玩抓娃娃机

#### 一键使用最近的锚和舵 一键攻击食人花 ( 默认关闭 )

#### 快速救救我 ( 默认关闭 )

- 一键发 rescue

#### 不可视物品

- 鼠标可以像穿过小木牌一样 无视萤火虫、蘑菇灯、眼塔、老麦小弟、玩家、月相盘、作物、避雷针、龙蝇火炉 点击后面的物体

#### 无限制施法 划水

- 现在在点星星和月亮能点到以前点不到的位置了(划船同理)
- 星杖月杖可以在全黑情况使用

#### 更好的划船

- 划船不会失败，禁用对实体划船，长按右键重复划船

#### 不用绞盘

- 禁用空格键使用绞盘

#### [减少 mod 界面卡顿](url=https://steamcommunity.com/sharedfiles/filedetails/?id=2290107641)

- 只有在进入模组界面时才会刷新一次，按 F5 手动刷新 ( 仅在模组界面有效 ) 一直按 F5 有惊喜
- 注意：不要同时启用 此选项 和 减少 mod 界面卡顿 mod

#### 丢弃动作改动

- 禁用官方快丢，用来兼容 排队论 和 重复丢弃

#### [武器接力](url=https://steamcommunity.com/sharedfiles/filedetails/?id=2095062694)

- 当武器没有耐久时自动切换新武器

#### [杀鱼队列](url=https://steamcommunity.com/sharedfiles/filedetails/?id=2032316309)

- 按下快捷键可以自动开始杀鱼(现在不会太阳鱼和冰雕鱼了)

#### [显示 mod 文件夹](https://steamcommunity.com/sharedfiles/filedetails/?id=2007016033) ( 默认关闭 )

- 在 mod 名称下面显示 mod 的文件夹，也许能对 mod 开发有帮助吧

#### 蜂蜜采集

1. 当身上有点火用具 ( 不包括火魔杖 )
2. 附近有可收获蜂箱在打开的灭火器范围内
3. 身上装备有鳞甲/玩家为薇洛时，按下动作键，mod 就会自动帮你点燃蜂箱，并收获蜂蜜
   > 不要将点火用具装备到手上，mod 会在物品栏直接利用模拟手柄按键使用物品的的（好处是不消耗耐久）

#### 自动玩鸦年华鸟鸟吃虫虫 ( 默认关闭 )

- 按下按键可以[全自动喂鸟](https://www.bilibili.com/video/BV1pK4y1V7rQ)
- 需要开启 [Action Queue Reborn](https://steamcommunity.com/sharedfiles/filedetails/?id=1608191708) 和 AQ Changes

#### 一视同仁

- 所有的鹿角，贝壳，小玩具(不包括电线)，挂饰，彩灯，零食，糖果，石笋，种子，种下的蔬菜，巨型蔬菜，蓝图 / 稿纸 / 广告，杂草，树，科学家零件 视为同一个 prefab

#### 控制台小改动

- 禁用控制台切换键关闭控制台（只能用 esc 关闭）

#### 批量雇佣 ( 默认关闭 )

- 给 猪人/兔人/鱼人/蜘蛛 东西的时候每人只给一个(不包括鱼人王)

#### 快速找祭坛

- 在不同的位置使用 2 次天体探测仪后会在小地图上显示出具体位置
- 在地面上会显示像小鱼妹显示触手的白圈，这个地方就是埋天体雕像的位置

#### 半自动天体老头小游戏

- 不戴天文镜也能看到老头的指示
- 绑定一个按键，在事件开始前按启动键会走到科学家的位置
- 事件开启后，按下后可以自动给老头天体零件(即使零件在地面上)

## 常见问题

#### 海钓长按不能收线

关闭 No Repeat Held Action 功能，这个默认开启的功能会禁用原版的长按模拟重复点击

## 测试功能

- 同时按下 Alt + F4 可以切换旧版制作栏 ( 目前可能会导致游戏崩溃，请谨慎使用!!! )

## Credits

- Action interrupt part codes is from [eXiGe](https://steamcommunity.com/id/efutue)
- UpvalueHelper from [rezecib](https://steamcommunity.com/id/rezecib)
