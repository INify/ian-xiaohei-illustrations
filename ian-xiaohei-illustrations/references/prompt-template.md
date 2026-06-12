# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, and no realistic UI.

Recurring IP character required:
Mochi (麻糬豆), a small solid-black mochi-shaped creature with slightly uneven hand-drawn edges. Mochi has two white dot eyes, with one eye slightly smaller than the other, a tiny horizontal mouth, thin stick arms and legs, and a calm serious expression. Mochi must perform the core conceptual action, not decorate the scene. Mochi is earnest, focused, and quietly dedicated to its task.

Theme:
明天的我，总觉得比今天的我更厉害。

Structure type:
概念隐喻

Core idea:
People often believe that their future self will magically become more motivated and capable, so they keep postponing today's responsibilities. In reality, tomorrow's self simply passes the work to an even later version of themselves, creating an endless cycle of procrastination.

Composition:
A giant hand-drawn conveyor belt runs across the center of the scene. On the left, Today's Mochi is seriously pushing a stack of assignments and responsibilities into a machine labeled 「明天处理」. On the right side of the machine, Tomorrow's Mochi receives the same pile without any surprise and immediately pushes it into another nearly identical machine labeled 「后天处理」. That machine leads back into the same looping conveyor system, suggesting an infinite cycle.

At the bottom corner, a tiny exhausted Mochi quietly holds a small sign that says 「救命」 while watching the loop continue.

Suggested elements:
输送带 / 作业文件堆 / 明天处理机器 / 后天处理机器 / 无限回路

Chinese handwritten labels:
明天
后天
再等等
无限循环
救命

Color use:
Black for all line art and Mochi characters.
Orange for conveyor paths and arrows showing the endless loop.
Red only for warning emphasis such as 「无限循环」.
Blue only for secondary notes and feedback annotations.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Make it strange but clean, funny but deadpan, relatable but not childish. The humor should come from how seriously Mochi participates in an obviously absurd system.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小黑 more central to the conceptual action. 小黑 should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
