# 第一次作业，宝可梦游戏
- [综述](##综述)
- [新增](##新增)
- [修改](##修改)
- [问题](##问题)
- [评论](##评论)

## 综述
  这是第一次作业，本作业在示例代码上进行修改。玩法与示例代码相近。
## 新增
  1. 新增一个宝可梦属性，宝可梦护盾：宝可梦护盾效果是减少宝可梦受到的伤害（%百分比减免），会在宝可梦最终伤害计算之后生效。
  2. 新增水属性类，受到伤害时，有50%的几率减免30%的伤害\n
  2. 新增宝可梦杰尼龟，水属性。
     技能：
     1. 水枪 (Aqua Jet)：杰尼龟喷射出一股强力的水流，对敌方造成 140% 水属性伤害
     2. 护盾 (Shield)：杰尼龟使用水流形成保护盾，减少下一回合受到的伤害50%


     
## 修改
无修改
## 问题
- 当对手死亡后，还能放出技能。解决思路是在使用技能之前判断生命值。如果生命值小于0，则跳过使用技能。直接回合结束。或强制使用一个空技能来跳过回合。
## 评论
第一次做作业，对github不太熟练，如有错误还望多多包含。游戏问题会在后面有空时逐步更新。多多谅解，感激不尽。
