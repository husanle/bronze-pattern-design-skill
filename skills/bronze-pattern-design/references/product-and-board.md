# 产品转译与展板 / Product Application and Boards

## 从原纹到上物 / From source to product

1. **选图先看版位 / Choose by placement.** 对称主纹用单枚，沿边走向的纹样用窄带，可以独立接缝的单元才平铺。写出从实际触摸、阅读和装配角度必须留空的区域。 / Use a single motif for a symmetrical focal point, a strip for an edge, and a repeat only if seams work. Specify the areas that hands, readers, and assembly need kept clear.
2. **分两层做图 / Keep two artworks.** 近源稿保留可见形态；应用稿可以删地纹、加粗弱线，或展平曲带。对照说明改了什么。不要要求同一图片同时当复刻、印刷分色和最终效果图。 / Keep visible structures in a close study. In the application art, simplify ground ornament, strengthen fragile strokes, or straighten a strip; document what changed. Do not use one image as a tracing, color separation, and final render.
3. **选介质而非堆材质 / Pick a process, not an effect.** 尺背印要避开刻度与读数区；织标和刺绣检查针距、边缘与反白；压凹检查尖角、纸厚及阴影下的可读性；包装跨折线时检查接缝和展开图。不承诺未经打样的线宽、色差或耐磨值。 / Keep reverse-side ruler graphics clear of graduations and reading zones. For weaving or embroidery, test stitch resolution, edges, and negative spaces; for debossing, check corners, stock and legibility; for packaging, verify folds, seams, and the dieline. Do not guarantee line widths, color tolerance, or wear without samples.

## ImageGen 提示结构 / ImageGen prompt structure

> 依据所附局部做近源重绘，不重新设计。保留［朝向、关键部位数量、连接、正负形与轮廓］。去掉反光、纸纹、色偏和背景，不补画无法辨认处，不添加标题、边框或额外装饰。［黑纹白底或指定反白］，完整保留画面并预留裁切边距。

> Redraw the supplied crop closely; do not redesign it. Retain [orientation, count of key components, connections, positive and negative shapes, and outline]. Remove glare, grain, color cast and background; do not invent obscured details or add text, frames, or ornament. Use [black on white or specified reversal] and leave a small crop-safe margin.

附整张展板仍看不清时，改用逐枚局部；只有确实需要时才整组出图。生成后逐项确认（例：鱼的条数、首尾方向、环形火纹的钩数和回旋方向）。不通过时改提示重试，或将低可信细节明确标为待核；不要靠裁切掩盖结构错误。 / If a panel is too small, use individual crops rather than generating a batch from a distant board. Verify counts, orientation, and connections (for example, fish count and direction, or hook count and turning direction in a roundel). If a result fails, revise the prompt and retry or mark the uncertain detail; do not crop away structural errors to pass review.

## 示例：五件文具 / Example: five stationery items

此例说明功能安排，不提供历史归属或生产尺寸。 / This example demonstrates functional placement, not historical attribution or manufacturing dimensions.

| 产品 / Item | 放哪 / Place it here | 不占用 / Keep clear | 样件检查 / Prototype check |
|---|---|---|---|
| 笔袋 / Pouch | 兽面放主面，窄带走底边 / Mask on front, border along base | 拉链、车缝和拿取空间 / Zipper, seams, access | 量内净长，确认能装下配套尺 / Check internal length against the ruler |
| 按动笔 / Click pen | 龙纹顺笔杆低干扰区 / Dragon along the barrel | 握位、观墨窗与换芯结构 / Grip, ink window, refill access | 换芯后测试出芯和防滚 / Test tip travel and anti-roll after refill |
| 橡皮 / Eraser | 火纹只印纸套 / Flame roundel on sleeve only | 擦拭面、推用缺口 / Erasing surfaces and thumb notch | 测试能否顺手推移、纸套是否松脱 / Check push travel and sleeve retention |
| 透明尺 / Transparent ruler | 波曲纹走非刻度边 / Wave strip on non-graduated edge | 刻度、数字、透明读图区 / Ticks, numbers, clear window | 原尺寸打印，与标准尺比对后再打样 / Proof at 1:1 and compare with a reference ruler |
| 笔记本 / Notebook | 凤鸟单枚上封面，连珠节奏转作点引 / Bird on cover; bead spacing inspires dot guides | 姓名栏、装订区和主要书写面 / Name field, binding, writing area | 检查摊平、透墨、点引可见性 / Check lay-flat, show-through, and guide legibility |

## 展板与出图检查 / Board and export checks

- **分清图片类型。** 主视觉表现五金、材料和使用情景；重绘区展示贴近原纹的图；来源区给局部和用户要求的来源文字。可不标图号，以同序或纹样名对应。效果图的刻度、文字和工艺不视为制造依据。  
  **Separate image roles.** The hero shows materials and use, the redraw section shows close studies, and the source section pairs crops with the requested credit. If numbers are omitted, use the same order or motif names. Do not treat mockup graduations, text, or finishes as production specifications.
- **白底印刷。** 同时保证深浅层次和留白，不用深灰底铺满；在 A4 或 A3 的指定方向出单页 PDF，留出实际打印边距。校对中英文字形、裁切、色转灰后图案是否还能分辨；给一张预览。涉及真实尺或刀模，另给按比例的文件并注明打印设定。  
  **Monochrome proof.** Use a white stock background, distinct tones, and margins printable at the intended paper size; export a one-page PDF in the requested orientation. Check glyphs, clipping and detail after grayscale conversion, and include a preview. For a physical ruler or dieline, provide a separate scaled file with print settings.
- **包只交允许分享的内容。** 源照片、现场标牌、馆标、商标、授权字体分别检查；没有授权的商业再用不能靠署名替代。公共样例可只给链接、原创示意和原创设计描述。  
  **Package only permitted material.** Check rights separately for source photography, signage, institutional marks, trademarks, and fonts. Credit does not substitute for commercial-use permission. Public examples may use links, original diagrams, and original design descriptions.
