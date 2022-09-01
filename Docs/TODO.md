# SAO Battle Simulator 计划说明
### 计划说明  
**SAO Battle Simulator会是一个注重物理交互体验，沉浸式刀剑战斗的动作游戏（魂like敌人强大类型）**
* 游戏平台：PCVR  
* 游戏类型：冷兵器战斗/魂like  
* 游戏模式：单人闯关/多人BOOS战(待定)  
* SAO特有的技能释放  
* 场景组成方式：类VrChat
* 通关竞速  
* 追求画面
* 使用原著中的交互界面
* 提供原著中相同的登陆过程
* 重要的风景场景  
* 需要：**主美(极缺，已有20人美术团队)以及建模/渲染/技术美术/特效（缺）**
* [![](https://img.shields.io/badge/%E5%8A%A0%E5%85%A5%E6%88%91%E4%BB%AC-%E7%BB%84%E7%BB%87%E7%BE%A4-informational)](https://github.com/whx-prog/The-Seed-Link-Future/blob/main/Image/%E5%BC%80%E5%8F%91%E4%BA%A4%E6%B5%81%E7%BE%A4.png)
* 现有类似VR游戏参考：[Battle Talent](https://www.bilibili.com/video/BV1WF411u7B1?spm_id_from=333.337.search-card.all.click  "Battle Talent")         [剑与魔法](https://www.bilibili.com/video/BV1eJ41137eb?spm_id_from=333.337.search-card.all.click  "剑与魔法") 
___


# TODO
### 角色系统
* - [X] 角色模型IK骨骼系统
* - [X] 角色数值系统  
* - [X] 背包系统
* - [ ] 角色自定义（衣服头发颜色）
### 登录系统
* - [X] 登录过场场景
### 战斗系统  
* - [X] 姿势技能释放 
* - [X] 武器物理系统  
* - [ ] 战斗数值系统与模式设计
* - [ ] 武器不同区域计算区别
* - [X] 武器速度检测+手势检测是否是有效的武器挥舞
* - [X] 运动系统
* - [X] 连击Combat
* - [X] 弱点要害区域判定
* - [ ] 跳越检测（按键/头部离地识别）
* - [ ] 滞空攻击
* - [X] 技能释放时机（类似音游的按下时机不同，会有不同的伤害）
* - [X] 击中区域特效以及被击中敌人动作
* - [X] 攻击到物体的反馈/振动
* - [ ] BOSS难度级别
    #### 武器类型  
    * - [X] 单手剑
    * - [X] 单手弯剑
    * - [X] 单手弯斧
    * - [X] 双手战斧
    * - [X] 双手剑
    * - [X] 匕首  
    * - [X] 武士刀
    具体参考： [SAO WIKI](https://swordartonline.fandom.com/wiki/Sword_Skills  "SAO WIKI") 
### 场景  
* - [X] 教学关卡野猪
* - [X] 第一层Boss
* - [X] 青眼恶魔
* - [X] 四十七层
* - [X] 聚会大厅
* - [X] 训练场
* - [X] 休闲社交（湖边小屋/第一层大厅）  
### 特效  
* - [X] 死亡破碎特效（同登录特效）  
* - [X] 技能蓄力武器辉光Shader/粒子特效拖尾
### 音效  
* - [X] 武器挥舞（各类音效）
* - [X] 普通击中（可以统一）
* - [ ] 暴击集中反馈（包括要害集中）
* - [X] 技能蓄力
* - [X] 技能释放（技能音效/人物喊声）
* - [X] 特殊技能（名字）
* - [ ] 怪物叫声
* - [X] 战斗BGM（应该是直接用动画里的）
* - [X] 教学关卡教学说明声音
* - [X] 移动（走路/跑步），喘气
* - [X] 武器召唤出现
* - [ ] 武器收纳
* - [X] 心跳声/沉重呼吸声
* - [ ] 玩家被击中反馈叫声
* - [X] UI交互（已经有了图了），需要实装功能
* - [X] 死亡破碎
### 交互系统  
* - [X] UI高清重置  
* - [X] 操作系统  
.<div align=center><img src="https://github.com/whx-prog/The-Seed-Link-Future/blob/main/Image/UI.png" width="450" height="300" /></div>  
