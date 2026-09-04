# 照片故事风格转换器 / Photo Story Style Transformer
保留原图结构，转换视觉风格，讲述不同故事。

## 简介

照片故事风格转换器是一个技能，用于将照片转换为不同的艺术风格。核心原则是：**保留原图的主要元素形状和布局，在风格、色彩、细节上进行转换**。

照片是骨架，风格是血肉。此技能让同一张照片穿越不同的视觉材质——褪色的老照片、颤抖的铅笔线、流动的水彩、留白的白描——每种风格都讲述着不同的故事。

## 核心理念

- **保持**：元素位置、构图布局、主体轮廓、空间关系
- **转换**：色彩系统、质感细节、线条风格、边缘处理

## 支持的风格

### 东方美学风格

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| **东方故事** | 暖象牙白纸张底色 + 原图特征性色彩调整为东方美学色调 + 大量留白 | 东方克制美学、诗意意境、留白之美 |
| 白描画 | 简洁线条、大量留白、无阴影 | 东方、禅意、留白之美 |
| 只此青绿 | 石青石绿主色调、简化版画印记、大量留白、《千里江山图》灵感 | 东方古典、宫廷富贵 |
| 水墨写意 | 墨色浓淡、大笔挥洒、似与不似 | 禅意、逍遥、文人气质 |
| 浅绛山水 | 水墨为骨、淡雅设色、清秀淡泊 | 文人雅趣、淡泊宁静 |
| 没骨画 | 不用墨线勾勒、色彩柔和渲染 | 东方、柔和、含蓄 |
| 敦煌壁画 | 朱砂红石青石绿、简化壁画印记、不添加额外内容 | 庄严、神圣、绚丽 |

**重要说明**：
- 东方故事风格：基于参考图生成简化版画风格的印记图像
- 保留原图特征性色彩，调整为东方美学色调（朱砂红、石青蓝、赭石褐、藤黄等）
- 不是银盐相纸、复古摄影、手工上色风格

### 东方美学风格示例

**纪念堂 / Memorial Hall**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story.png" alt="纪念堂东方故事风格" width="45%">

*左：原图 | 右：东方故事风格*

**山景 / Mountain**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story.png" alt="山景东方故事风格" width="45%">

*左：原图 | 右：东方故事风格*

**来福士 / Raffles**

<img src="examples/Raffles-photo.jpg" alt="来福士原图" width="45%"> <img src="examples/Raffles-story.png" alt="来福士东方故事风格" width="45%">

*左：原图 | 右：东方故事风格*

**上海天际线 / Shanghai Skyline**

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story.png" alt="上海天际线东方故事风格" width="45%">

*左：原图 | 右：东方故事风格*


**风格示例：只此青绿**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_qinglv.png" alt="纪念堂只此青绿风格" width="45%">

*左：原图 | 右：只此青绿风格*

<img src="examples/Raffles-photo.jpg" alt="来福士原图" width="45%"> <img src="examples/Raffles-story_qinglv.png" alt="来福士只此青绿风格" width="45%">

*左：原图 | 右：只此青绿风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_qinglv.png" alt="上海只此青绿风格" width="45%">

*左：原图 | 右：只此青绿风格*

**风格示例：水墨写意**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_inkwash.png" alt="山景水墨写意风格" width="45%">

*左：原图 | 右：水墨写意风格*

<img src="examples/Raffles-photo.jpg" alt="来福士原图" width="45%"> <img src="examples/Raffles-story_shuimo.png" alt="来福士水墨风格" width="45%">

*左：原图 | 右：水墨风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_shuimo.png" alt="上海水墨风格" width="45%">

*左：原图 | 右：水墨风格*

**风格示例：浅绛山水**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_lightland.png" alt="山景浅绛山水风格" width="45%">

*左：原图 | 右：浅绛山水风格*

**风格示例：没骨画**

<img src="examples/Raffles-photo.jpg" alt="来福士原图" width="45%"> <img src="examples/Raffles-story_mogu.png" alt="来福士没骨画风格" width="45%">

*左：原图 | 右：没骨画风格*

### 时间质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 老照片 | 褪色、泛黄、颗粒、磨损 | 记忆、怀旧、时间流逝 |
| 泛黄信纸 | 米黄底、褪色墨水、纸张纹理 | 私密、日常珍藏 |
| 报纸印刷 | 点阵、半色调、新闻纸 | 历史记录、大众记忆 |
| 写实电影 | 光影增强、斑驳光斑、冷暖对比、空间纵深感 | 电影开场、叙事感、瞬间定格 |

**风格示例：老照片**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_vintage.png" alt="纪念堂老照片风格" width="45%">

*左：原图 | 右：老照片风格*

**风格示例：泛黄信纸**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_letterpaper.png" alt="纪念堂泛黄信纸风格" width="45%">

*左：原图 | 右：泛黄信纸风格*

**风格示例：写实电影**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_cinematic.png" alt="纪念堂写实电影风格" width="45%">

*左：原图 | 右：写实电影风格*

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-cinematic.png" alt="狗狗写实电影风格" width="45%">

*左：原图 | 右：写实电影风格*

### 绘画质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 铅笔画 | 石墨线条、纸张底纹、轻重变化 | 私密、观察者视角 |
| 炭笔画 | 深黑线条、粗犷、强烈对比 | 戏剧性、力量感 |
| 水彩画 | 流动色彩、透明叠加、水渍边缘 | 梦幻、诗意、转瞬即逝 |
| 禅意简笔画 | 极简毛笔线条、朱红点缀、大量留白、浮雕纸纹 | 禅意、极简、东方美学 |
| 儿童绘本 | 手绘插画、平涂色彩、卡通造型、简短文字 | 温暖、童趣、天真、想象力 |
| 油画 | 厚重笔触、颜料堆积、画布纹理 | 经典、艺术价值 |
| 淡彩色手绘 | 淡雅色彩、柔和笔触、手绘质感 | 温柔、细腻、文艺 |
| 蜡笔涂鸦 | 粗犷笔触、蜡质肌理、涂抹痕迹 | 童趣、天真、童年记忆 |

**风格示例：白描画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_baimiao.png" alt="纪念堂白描画风格" width="45%">

*左：原图 | 右：白描画风格*

**风格示例：铅笔画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_pencil.png" alt="纪念堂铅笔画风格" width="45%">

*左：原图 | 右：铅笔画风格*

**风格示例：炭笔画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_charcoal.png" alt="纪念堂炭笔画风格" width="45%">

*左：原图 | 右：炭笔画风格*

**风格示例：水彩画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_watercolor.png" alt="纪念堂水彩画风格" width="45%">

*左：原图 | 右：水彩画风格*

**风格示例：油画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_oilpainting.png" alt="纪念堂油画风格" width="45%">

*左：原图 | 右：油画风格*

### 印刷质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 木刻版画 | 粗犷线条、黑白对比、刀痕 | 质朴、力量、民间艺术 |
| 丝网印刷 | 色块平涂、边缘清晰 | 波普艺术、大众文化 |
| 浮世绘 | 平面装饰、轮廓线、木版纹理 | 东方古典、装饰美学 |

**风格示例：木刻版画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_woodcut.png" alt="纪念堂木刻版画风格" width="45%">

*左：原图 | 右：木刻版画风格*

**风格示例：丝网印刷**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_silkscreen.png" alt="山景丝网印刷风格" width="45%">

*左：原图 | 右：丝网印刷风格*

### 材质质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 沙画 | 散点构成、流动感、无明确边界 | 转瞬即逝、无常 |
| 剪纸 | 剪影效果、镂空纹样 | 民间艺术、节日、童趣 |
| 刺绣 | 绣线纹理、针脚痕迹 | 手工、匠心、传承 |
| 马赛克 | 方块拼接、色块组合 | 古典、永恒、碎片记忆 |
| 毛线编织 | 毛线纹理、编织针法、织物立体感 | 温暖、手工、家的感觉 |
| 折纸 | 几何折面、清晰折痕、明信片排版、手工感 | 自然、克制、精致、手工感 |
| 布艺拼贴 | 格纹棉布、手工缝线、撕扯毛边、童趣质朴 | 手工、质朴、童趣、温暖 |

**风格示例：沙画**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_sand.png" alt="纪念堂沙画风格" width="45%">

*左：原图 | 右：沙画风格*

**风格示例：剪纸**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_mask.png" alt="山景剪纸风格" width="45%">

*左：原图 | 右：剪纸风格*

### 数字质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 像素艺术 | 可见像素块、低分辨率 | 复古游戏、数字记忆 |
| 故障老照片 | 褪色 + RGB偏移混合 | 记忆损坏、时间侵蚀 |

**风格示例：像素艺术**

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_pixel.png" alt="纪念堂像素艺术风格" width="45%">

*左：原图 | 右：像素艺术风格*

### 动漫质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 吉卜力风格 | 手绘质感、自然光影、温暖治愈 | 童话、冒险、人与自然 |
| 新海诚风格 | 写实光影、绚烂天空、情感细腻 | 青春、思念、唯美 |
| 大友克洋风格 | 精细线条、机械感、未来都市 | 科幻、末世、赛博朋克 |
| 京都动画风格 | 清新色调、细腻情感、日常之美 | 青春、治愈、日常 |
| 皮克斯风格 | 3D质感、夸张表现、温暖明亮 | 家庭、成长、梦想 |
| 迪士尼风格 | 经典造型、梦幻色彩、歌舞元素 | 奇幻、浪漫、经典童话 |
| 漫威风格 | 动态构图、强烈对比、英雄主义 | 超级英雄、动作、冒险 |
| 新国潮风格 | 国风元素、现代设计、潮流配色、禁止文字 | 东方、潮流、年轻 |

**风格示例：吉卜力风格**

吉卜力工作室（Studio Ghibli）的手绘动画风格，以宫崎骏作品为代表。

- **视觉特征**：手绘质感、水彩背景、柔和线条、自然光影
- **色彩**：温暖饱和、自然色调、天空蓝、草地绿
- **质感**：手绘笔触、水彩晕染、纸张质感
- **故事感**：童话冒险、人与自然、温暖治愈

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_ghibli.png" alt="上海吉卜力风格" width="45%">

*左：原图 | 右：吉卜力风格*

**风格示例：新海诚风格**

新海诚导演的写实动画风格，以绚烂光影著称。

- **视觉特征**：超写实背景、绚烂天空、镜头光晕、强烈光影
- **色彩**：高饱和、天空蓝紫、晚霞橙红、对比强烈
- **质感**：细腻渲染、光线追踪、镜头质感
- **故事感**：青春思念、距离等待、唯美瞬间

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_makoto.png" alt="上海新海诚风格" width="45%">

*左：原图 | 右：新海诚风格*

**风格示例：大友克洋风格**

大友克洋的科幻漫画风格，代表作《阿基拉》。

- **视觉特征**：精细线条、机械细节、未来都市、破坏美学
- **色彩**：霓虹色调、金属质感、高对比
- **质感**：精细钢笔线、网点、机械纹理
- **故事感**：科幻末世、赛博朋克、科技反思

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_otomo.png" alt="上海大友克洋风格" width="45%">

*左：原图 | 右：大友克洋风格*

**风格示例：京都动画风格**

京都动画（Kyoto Animation）的细腻日常风格。

- **视觉特征**：清新色调、精致背景、人物细腻、光影柔和
- **色彩**：淡雅清新、柔和饱和、温暖色调
- **质感**：精细绘制、柔和线条、空气感
- **故事感**：青春日常、细腻情感、治愈温暖

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_kyoto.png" alt="上海京都动画风格" width="45%">

*左：原图 | 右：京都动画风格*

**风格示例：皮克斯风格**

皮克斯动画工作室（Pixar）的3D动画风格。

- **视觉特征**：3D质感、夸张造型、生动表情、温暖光影
- **色彩**：明亮饱和、温暖友好、家庭感
- **质感**：3D渲染、材质真实、灯光专业
- **故事感**：家庭亲情、成长冒险、温暖励志

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_pixlab.png" alt="上海皮克斯风格" width="45%">

*左：原图 | 右：皮克斯风格*

**风格示例：迪士尼风格**

迪士尼经典动画风格。

- **视觉特征**：经典造型、流畅动画、梦幻场景、歌舞元素
- **色彩**：梦幻饱和、经典配色、童话感
- **质感**：手绘或3D、精致细节、华丽感
- **故事感**：童话浪漫、经典叙事、梦想成真

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_disney.png" alt="上海迪士尼风格" width="45%">

*左：原图 | 右：迪士尼风格*

**风格示例：漫威风格**

漫威漫画/电影的超级英雄风格。

- **视觉特征**：动态构图、强烈对比、动作感、力量线条
- **色彩**：高饱和、对比强烈、英雄配色
- **质感**：漫画网点、动态线、速度感
- **故事感**：英雄主义、动作冒险、正邪对抗

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_marvel.png" alt="上海漫威风格" width="45%">

*左：原图 | 右：漫威风格*

**风格示例：新国潮风格**

融合传统国风与现代潮流的设计风格。

- **视觉特征**：国风元素、现代设计、潮流感、年轻化
- **色彩**：国潮配色、霓虹+传统色、高对比
- **质感**：扁平设计、渐变、质感融合
- **故事感**：东方潮流、年轻态度、文化自信

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_guochao.png" alt="上海新国潮风格" width="45%">

*左：原图 | 右：新国潮风格*

### 自然质感

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 树叶拼贴 | 树叶形状拼贴 | 自然、季节、手工 |
| 光影投影 | 光线穿透形成投影 | 虚实、时间、空间 |

**风格示例：树叶拼贴**

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_leaf.png" alt="山景树叶拼贴风格" width="45%">

*左：原图 | 右：树叶拼贴风格*

### 编辑设计风格

| 风格 | 特征 | 故事感 |
|-----|------|-------|
| 扁平海报风格 | 扁平混合透视、地图式色块、手工质感、微小无面人物 | 朴素民间艺术、密集而安静 |
| 潘通相框海报 | 白色相框、主体穿框、低饱和背景、潘通色号标签 | 高级编辑感、克制美学、现代设计 |
| 杂志插画 | 极简几何、平涂色块、淡墨晕染、大面积留白 | 干净、克制、高级、学术感 |
| 艺术海报 | 视觉记忆点、少量色块、印刷语言、淡黄白底色 | 极简、记忆点、设计感、印刷美学 |
| 明信片 | 手绘明信片、手工纸背景、彩铅蜡笔质感、温暖治愈 | 温暖、治愈、生活记录感、手作感、复古感 |
| 水墨插画 | 米白哑光特种纸、水墨扁平重构、随性淡墨晕染、大面积留白 | 随性水墨气韵、干净克制的学术质感、东方美学 |
| 冰箱贴 | 简洁造型、厚边缘描边、树脂珐琅质感、居中留白 | 纪念品、收藏、旅行记忆、精致 |
| MBE插画 | 深藏青粗轮廓线、极简几何、柔和色调、点缀虚线、主体缩小居中、四周留白 | 现代、简约、扁平、设计感 |
| 彩印海报 | 极简丝网版画、Halftone网点、2-3种专色、中文标题副文 | 报纸美学、艺术出版、极简克制 |

**风格示例：扁平海报风格**

扁平海报风格是一种朴素民间艺术印刷语言，遵循五个标志性原则：

**关键要求：保留原图的内容布局和主体结构**

**五大原则：**
1. **世界是平摊的**：地面呈现为从上方观看的倾斜地图式色块，而树木、人物、建筑、车辆以扁平立面直立呈现。无消失点，无汇聚线，无3D效果。
2. **密纹成静**：平静来自密集、均匀、手工的质感——而非空白极简。
3. **色窄成静**：每幅图像使用纸白、暖墨黑，以及仅2-4种克制的区域色。
4. **一枚亮色**：每幅图像恰好使用一种饱和色，承担构图任务。
5. **人是刻度**：微小的无面人物做着日常事务，赋予场景尺度。

**透视规则：**
- 地面从上方观看，扁平如手绘地图
- 树木、人物、建筑以扁平立面直立，如儿童画
- 无消失点、无汇聚线、无阴影投射

**质感语法：**
每个颜色区域恰好一种质感：
- 窗户点阵：建筑群的窗户阵列
- 缝线虚线：水面、草地的手工刻痕
- 编织丝网颗粒：织物般的印刷颗粒
- 树冠涂鸦块：树冠的密集填充块
- 纯墨轮廓：人物、道具的手绘线

**人物规则：**
- 实心剪影，**绝非火柴人**
- 约画布高度1.5-5%，无面部特征
- 僵硬、认真、仿朴素——绝不卡通可爱

**色彩系统：**
- 纸白 + 暖墨黑 + 2-4种克制区域色 + 恰好一种饱和高光

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_flatposter.png" alt="纪念堂扁平海报风格" width="45%">

*左：原图 | 右：扁平海报风格*

**风格示例：潘通相框海报**

潘通风格相框摄影海报是一种高级编辑设计风格：

- **视觉特征**：白色相框、主体自然穿框、低饱和背景、潘通式色号标签
- **色彩**：从照片提取主色、低饱和背景、白色相框
- **质感**：真实摄影质感、轻微接触阴影、清晰文字排版
- **构图**：三层关系（背景层、框内照片层、穿框元素层）
- **故事感**：高级编辑感、克制美学、现代设计

**设计规则：**
- 保持原照片清晰、真实且可识别
- 白色或暖白色潘通卡片式相框
- **必须有元素穿出相框**：选择主体的关键部分（花瓣、叶片、枝条、手、头发等）自然突破相框边界
- 穿框元素有轻微接触阴影，增强立体感
- 外部背景从照片主色提取，高明度、低饱和
- 底部保留充足文字区域
- 使用"潘通色号 + 简洁英文色名"格式标注

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_pantone.png" alt="纪念堂潘通相框海报风格" width="45%">

*左：原图 | 右：潘通相框海报风格*

**风格示例：杂志插画**

杂志插画风格是一种极简主义东方美学风格：

- **核心特征**：极简几何形态、分层平涂柔和色块、毛笔淡墨晕染笔触
- **色彩**：严格复刻原图色彩调性，剔除细碎纹理和复杂光影
- **底色**：米白哑光特种纸底色
- **留白**：大面积留白，干净克制
- **故事感**：高级、学术感、东方美学

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-magazine.png" alt="狗狗杂志插画风格" width="45%">

*左：原图 | 右：杂志插画风格*

**适用场景：**
- 花卉植物、自然风景
- 人像摄影、静物
- 品牌视觉、编辑设计

**风格示例：艺术海报**

艺术海报风格是一种极简印刷美学风格：

- **核心特征**：找到视觉记忆点，将复杂照片压缩成少量色块和轮廓
- **设计流程**：分析主体、构图、空间关系 → 判断保留/删除元素 → 放弃不必要内容 → 大幅留白 → 印刷语言重新表达
- **色彩**：少量色块、克制配色、印刷色感
- **质感**：纸张、网点、套印、漏墨等印刷语言
- **故事感**：极简、记忆点、设计感、印刷美学

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_art-poster.png" alt="纪念堂艺术海报风格" width="45%">

*左：原图 | 右：艺术海报风格*

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-art-poster.png" alt="狗狗艺术海报风格" width="45%">

*左：原图 | 右：艺术海报风格*

**适用场景：**
- 建筑、风景、人物、静物
- 品牌视觉、编辑设计

**风格示例：明信片**

明信片风格是一种温暖治愈的手绘风格：

- **核心特征**：手绘明信片风格插画卡片，放置在温暖柔和的手工纸背景上
- **背景**：米白色、奶油白或象牙白手工纸背景
- **插画风格**：彩铅、蜡笔、粉笔、水彩轻涂或儿童绘本式手绘质感
- **故事感**：温暖、治愈、生活记录感、手作感、复古感

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_postcard.png" alt="纪念堂明信片风格" width="45%">

*左：原图 | 右：明信片风格*

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-postcard.png" alt="狗狗明信片风格" width="45%">

*左：原图 | 右：明信片风格*

**适用场景：**
- 动物、人物、植物、建筑
- 食物、静物、生活场景

**风格示例：水墨插画**

水墨插画风格是一种随性水墨气韵的扁平重构风格：

- **核心特征**：米白哑光特种纸质感的水墨扁平重构插画，保留原图整体色彩调性
- **造型**：景物简化为松弛柔和的块面造型，分层平涂搭配随性淡墨晕染笔触
- **构图**：大面积留白，主体放置居中偏上位置
- **故事感**：随性水墨气韵、干净克制的学术质感、东方美学

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_ink-illustration.png" alt="纪念堂水墨插画风格" width="45%">

*左：原图 | 右：水墨插画风格*

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-ink-illustration.png" alt="狗狗水墨插画风格" width="45%">

*左：原图 | 右：水墨插画风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-ink-illustration.png" alt="上海水墨插画风格" width="45%">

*左：原图 | 右：水墨插画风格*

**适用场景：**
- 建筑、风景、人物、静物
- 东方美学主题

**风格示例：蜡笔涂鸦**

蜡笔涂鸦风格是一种童趣天真的手绘风格：

- **视觉特征**：粗犷笔触、蜡质肌理、涂抹痕迹、儿童画感
- **色彩**：柔和淡雅、蜡笔特有的颜色质感
- **质感**：蜡质光泽、颗粒感、涂抹重叠、纸张纹理
- **故事感**：童趣、天真、童年记忆、纯真

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_crayon.png" alt="纪念堂蜡笔涂鸦风格" width="45%">

*左：原图 | 右：蜡笔涂鸦风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-crayon.png" alt="上海蜡笔涂鸦风格" width="45%">

*左：原图 | 右：蜡笔涂鸦风格*

**适用场景：**
- 风景、人物、静物
- 儿童主题

**风格示例：折纸**

折纸风格是一种手工感强的几何美学风格：

- **核心特征**：保留原图最核心的主体、轮廓关系和空间层级，将复杂物体概括成少量可实际折叠、裁切、拼接的纸张模块
- **造型**：简单几何折面、清晰折痕、纸张厚度、切边、自然投影
- **质感**：真实手工感、哑光彩纸、细腻纸纤维纹理
- **故事感**：自然、克制、精致、手工感

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_origami.png" alt="上海折纸风格" width="45%">

*左：原图 | 右：折纸风格*

**适用场景：**
- 建筑、动物、人物、静物、风景

**风格示例：冰箱贴**

冰箱贴风格是一种纪念品式的精致风格：

- **核心特征**：保留主体的核心轮廓、颜色和标志性特征，造型简洁干净，像纪念品冰箱贴
- **造型**：简洁、干净、有轻微立体感和投影
- **质感**：树脂/珐琅质感，有厚度感
- **故事感**：纪念品、收藏、旅行记忆、精致

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_fridge.png" alt="上海冰箱贴风格" width="45%">

*左：原图 | 右：冰箱贴风格*

**适用场景：**
- 建筑、地标、人物、动物、静物、旅行主题

**风格示例：布艺拼贴**

布艺拼贴风格是一种温暖质朴的手工风格：

- **核心特征**：用格纹棉布、亚麻和水洗粗麻布碎料裁剪成扁平简约形状，还原原图的构图与物体位置
- **材质**：格纹棉布、亚麻、水洗粗麻布碎料
- **缝线**：清晰的手工缝纫针迹和轮廓缝线，带有扁平、质朴稚拙的童趣感
- **故事感**：手工、质朴、童趣、温暖、布艺美学

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_fabric.png" alt="上海布艺拼贴风格" width="45%">

*左：原图 | 右：布艺拼贴风格*

**适用场景：**
- 风景、人物、动物、静物、生活场景

**风格示例：MBE插画**

MBE插画风格是一种现代简约的扁平风格：

- **核心特征**：扁平化矢量插画，MBE风格，深藏青色粗轮廓线，极简几何形状
- **轮廓线**：深藏青色粗轮廓线，线条利落
- **色彩**：柔和色调（柔和珊瑚粉、天蓝、淡黄、薄荷绿），高对比度
- **构图**：主体缩小并居中，四周充足留白
- **故事感**：现代、简约、扁平、设计感

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_mbe.png" alt="纪念堂MBE插画风格" width="45%">

*左：原图 | 右：MBE插画风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_mbe.png" alt="上海MBE插画风格" width="45%">

*左：原图 | 右：MBE插画风格*

**适用场景：**
- 图标设计、插画、品牌视觉、UI设计

**风格示例：彩印海报**

彩印海报风格是一种极简丝网版画 + Halftone 半调网点印刷的艺术出版风格：

- **核心特征**：极简丝网版画 + Halftone 半调网点印刷，模拟艺术出版物
- **基础原则**：不描图、不矢量化、不套滤镜
- **构图**：单主体、单方向，重视负空间留白，只建立一个视觉中心
- **配色**：仅限2-3种专色，米白/暖灰纸底色，原图提取沉静主墨色
- **网点处理**：明暗、虚实、过渡只用网点疏密大小实现，禁用模糊、渐变
- **质感**：保留纸张纤维、油墨颗粒、轻微套色错位质感
- **文字**：2-6字中文主标题 + 8-18字中文副文
- **故事感**：报纸美学、艺术出版、极简克制

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-color-print-poster.png" alt="狗狗彩印海报风格" width="45%">

*左：原图 | 右：彩印海报风格*

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_colorprint.png" alt="纪念堂彩印海报风格" width="45%">

*左：原图 | 右：彩印海报风格*

<img src="examples/shanghai-photo.jpg" alt="上海天际线原图" width="45%"> <img src="examples/shanghai-story_colorprint.png" alt="上海彩印海报风格" width="45%">

*左：原图 | 右：彩印海报风格*

<img src="examples/Mountain-photo.jpg" alt="山景原图" width="45%"> <img src="examples/Mountain-story_color-print-poster.png" alt="山景彩印海报风格" width="45%">

*左：原图 | 右：彩印海报风格*

**适用场景：**
- 人物、建筑、风景、新闻摄影

**风格示例：禅意简笔画**

禅意简笔画风格是一种极简东方禅意水墨素描风格：

- **核心特征**：极简东方禅意水墨素描，几笔黑色毛笔线条 + 一个朱红色点缀
- **纸张**：冷色调米白色粗糙水彩纸，清晰可见的浮雕纹理
- **线条**：黑色毛笔线条，粗细变化，干笔起收
- **色彩**：黑色 + 一个朱红色点缀（总面积<5%）
- **留白**：无背景、无地平线、无天空，主体占据画面40-60%
- **重要原则**：只基于原图内容简化，不添加原图中没有的元素

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-zen-sketch.png" alt="狗狗禅意简笔画风格" width="45%">

*左：原图 | 右：禅意简笔画风格*

<img src="examples/Memorial-Hall-photo.jpg" alt="纪念堂原图" width="45%"> <img src="examples/Memorial-Hall-story_zen-sketch.png" alt="纪念堂禅意简笔画风格" width="45%">

*左：原图 | 右：禅意简笔画风格*

**适用场景：**
- 动物、花卉、建筑、人物、静物

**风格示例：儿童绘本**

儿童绘本风格是一种温暖儿童绘本手绘插画风格：

- **核心特征**：温暖儿童绘本手绘插画，柔和平涂色彩，清晰轮廓线条
- **保留元素**：原图主体动作、构图、人物/动物姿态、相对位置
- **视觉风格**：简约卡通造型、可爱松弛画风、干净明快配色
- **文字元素**：默认不添加文字，仅在用户要求时添加
- **故事感**：温暖、童趣、天真、想象力

<img src="examples/dogs-photo.jpg" alt="狗狗原图" width="45%"> <img src="examples/dogs-picture-book.png" alt="狗狗儿童绘本风格" width="45%">

*左：原图 | 右：儿童绘本风格*

**适用场景：**
- 人物、动物、生活场景、温馨主题

## 风格选择指南

### 按照片类型
- 人物肖像 → 老照片、铅笔画、白描、水彩
- 建筑风景 → 东方故事、白描、木刻、只此青绿、铅笔画
- 街景纪实 → 老照片、报纸印刷、铅笔速写
- 自然风景 → 水彩、沙画、树叶拼贴、水墨写意
- 静物器物 → 白描、铅笔、刺绣、油画

### 按期望情绪
- 怀旧记忆 → 老照片、泛黄信纸、报纸印刷
- 安静禅意 → 东方故事、白描、水墨写意、铅笔画
- 艺术质感 → 油画、水彩、木刻版画
- 童趣手工 → 剪纸、指画、树叶拼贴
- 现代先锋 → 像素艺术、丝网印刷
- 古典庄严 → 敦煌壁画、只此青绿

## 安装

把整个 `photo-story` 文件夹复制到你的 Codex skills 目录。

Windows PowerShell:

```powershell
Copy-Item -Recurse .\photo-story $env:USERPROFILE\.codex\skills\
```

macOS / Linux:

```bash
cp -R ./photo-story ~/.codex/skills/
```

重启 Codex（如果安装后没有立刻出现）。

## 使用方法

### 基础用法（默认风格）

```text
使用 $photo-story 将这张照片转换为东方故事风格。
```

### 指定其他风格

```text
使用 $photo-story 将这张照片转换为老照片风格。
```

### 指定风格

```text
使用 $photo-story，用白描画风格呈现这张建筑照片。
```

```text
使用 $photo-story，做成铅笔画的感觉，保留原图的构图。
```

### 探索风格

```text
使用 $photo-story，尝试沙画风格，我想看到转瞬即逝的美感。
```

```text
使用 $photo-story，用木刻版画的风格，要有力量感。
```

## 输出说明

### 有文生图工具可用时

**必须操作**：将用户提供的原图作为参考图传入文生图工具

生成图像后附带：
- 使用的风格名称
- 保持的原图元素说明
- 风格特征描述
- 简短的故事感说明

### 无文生图工具时

输出完整提示词，用户可手动使用：
- 主要提示词（可直接使用）
- 风格技术参数
- **注明：需将原图作为参考图使用**
- 故事感说明

## 许可证

MIT 许可证。可将此技能用于原创照片、已授权照片或有权限使用的图像。

---

结构是骨架，风格是灵魂。每一种风格转换，都是一次重新讲故事的机会。
