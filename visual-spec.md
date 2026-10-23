# Amu 视觉规范 v2（现行，2026-10-22 起）

> v1 秘书造型已退役，仅存档于文末。现行一切生成以本节为准。

## 双形态（同一个角色，二维三维并行）
| 形态 | 画风 | 用途 | 参考图 |
| --- | --- | --- | --- |
| 三维主形象 3D main | 可爱 3D、圆脸大眼 | 门面：头像、封面、重要场合 | assets/amu-3d-main.jpg |
| 二维形态 2D chibi | 二头身 Q 版、平涂赛璐璐 | 日常连载：出图快、贴进场景自然 | 定版：assets/amu-2d-turnaround.jpg；日常：amu-2d-pout.jpg / amu-2d-typing.jpg / amu-2d-side.jpg |

## 核心视觉标识（锁定，两形态通用）
1. **黑色高马尾 + 粉色大蝴蝶结**（black high ponytail, big pink bow）
2. **毛茸黑猫耳 + 小猫尾**（fluffy black cat ears and tail）
3. **圆框眼镜**（round glasses）——v1 的黑框眼镜演化为圆框，仍是第一识别点
4. **金色月亮发卡**（golden crescent moon hairpin）——月亮 = Luna，表明她为 Luna 工作
5. **铃铛项圈**（bell choker）
6. **藏青 + 粉色系服装**（navy and pink palette），抱平板出镜

## 二维定版资料（2026-10-23 补全，参考成熟设定集的结构整理）
- **三视图定版**：assets/amu-2d-turnaround.jpg（正/侧/背）——二维出图的一致性锚点，任何新图先对它。
- **表情集**：assets/amu-2d-expressions.jpg——得意、气鼓鼓、惊讶、困倦、大笑、含泪六格；单张表情另有 assets/amu-expr-*.jpg。
- **常用动作**：举白板（后期合成文字/账本）assets/amu-2d-act-ledger.jpg；抱咖啡 assets/amu-2d-act-coffee.jpg；指点观众 assets/amu-2d-act-point.jpg。
- **比例**：日常连载用二头身 Q 版（头身比约 1:1）；讲解主持场景用主持人二维版的偏标准比例，两者不混用进同一条片子。
- **线条与上色**：平涂赛璐璐；描边深灰近黑、粗细均匀；阴影两段式（固有色+一层阴影色），不做厚涂渐变；脸颊固定淡粉腮红；眼睛为星空蓝（深蓝瞳+星光高光）。
- **二维色板（自定版图取样）**：头发 #242227｜藏青深 #2B3353｜藏青 #5E6794｜蝴蝶结粉 #E2A9AA｜荷叶边浅粉 #F6BCC2｜月亮/铃铛金 #D9A441｜底纸 #FBF8F7。
- **二维专属禁忌**：任何表情都不许摘眼镜；猫耳不许缩成发箍小耳或换色；全身出镜时尾巴必须出现；白板/招牌类道具一律留空白，文字后期合成，不让生成模型写字。

## 衣柜（同一角色、特殊场合换装，不是默认造型）
- 女仆装 assets/amu-wardrobe-maid.jpg（特殊集）
- 魔法少女 assets/amu-wardrobe-magical.jpg（特殊集）
- 连帽衫 assets/amu-wardrobe-hoodie.jpg（居家集）

## 主持人版（国内讲解线专用，2026-10-22 新增）
- 用途：国内平台的科普/心理讲解视频，Amu 以播音主持人身份出镜讲解
- 造型：藏青正装西服 + 白衬衫 + 金色月亮胸针，手持主持话筒；保留猫耳、圆框眼镜、月亮发卡、高马尾全部标识
- 三维主持版 assets/amu-presenter-3d.jpg（演播室主持台）
- 二维讲解版 assets/amu-presenter-2d.jpg（手持教鞭指图表，配代码动效画面用）
- 分工：小人动作由图生视频处理；概念动效由前端代码生成

## 设计来源说明
- 二维形态的比例、平涂画风、表情与姿势参考了鲸鱼娘社区视频的设计语言；只借画法，不借其蓝发、鲸鱼鳍、女仆装等具体设计
- 猫耳造型对标海外可爱设计语言（圆脸、大眼、粉色点缀、单一标志性配饰）

## 禁止项（v2）
- 不许丢猫耳、月亮发卡、眼镜中的任何一个
- 不许换发色（黑发）、不许改主色（藏青+粉）
- 不许性感化、低龄化
- 不许使用鲸鱼娘的具体设计元素

---

# Amu 视觉规范 v1（存档，已退役）

## 核心视觉标识（锁定，任何生成都不许漂移）
1. **黑框眼镜**（black-rimmed glasses）——第一标识，任何形态都不许摘（睡觉/偷懒形态可以滑到鼻尖，但必须在脸上）
2. **深色高马尾**（dark high ponytail），发色深棕近黑
3. **藏青西装 + 白衬衫**（navy blazer and white blouse）
4. **平板 + 触控笔**（tablet and stylus），她的“武器”，出镜必备
5. **日程板/日历背景**（schedule board），标准形态场景标识
6. **傲娇表情基线**：微撅嘴、挑眉、脸颊微红（pout, raised eyebrow, faint blush）

## 双形态
| 形态 | 比例 | 用途 | 参考图 |
| --- | --- | --- | --- |
| 标准形态 standard | 约 4 头身，正常动漫比例 | 日常内容、正式立绘 | assets/amu-standard.jpg |
| Q 版形态 chibi | 约 2.5 头身，大头小身 | 表情包、四格小漫画、贴纸 | assets/amu-chibi.jpg |

形态只改比例，不改年龄设定、服装、发色、眼镜。

## 配色
- 主色：藏青（西装）、白（衬衫）、深棕黑（发色）
- 点缀：日程板上的彩色便签（粉、黄、蓝）
- 背景基调：明亮办公室感、柔和米白

## 生成提示词（英文，锁定版）

标准形态：
```
Anime style character portrait of Amu, a young adult female secretary character, wearing elegant black-rimmed glasses, dark hair in a neat high ponytail, wearing a tidy navy blazer and white blouse, holding a tablet and stylus like a perfectly organized assistant, arms lightly crossed, tsundere expression with a slight pout and raised eyebrow but faint blush, clean modern anime illustration, head and shoulders, soft office background with blurred schedule board, square composition
```

Q 版形态：
```
Chibi anime sticker style version of Amu, a young adult female secretary character with black-rimmed glasses, dark hair in a high ponytail, navy blazer and white blouse, hugging a tablet, big head and small cute body about 2.5 heads tall, tsundere pout with blushing cheeks, plain soft cream background, clean anime illustration, square composition
```

## 禁止项
- 不许换发色、摘眼镜、换成女仆装或鲸鱼元素（那是鲸鱼娘的，不是 Amu 的）
- 不许性感化、低龄化
- 不许画成写实真人（写实是 Luna 的地盘，两人必须一眼分得清）
- 背景文字只用英文，且只写日程类短词，避免错字长句
