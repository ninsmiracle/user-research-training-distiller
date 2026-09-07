# User Research Training Distiller

一个把用户研究教学视频变成可用学习资产的 Codex Skill。

它适合把已提供的课程视频、字幕或可回指时间点的课程报告，整理为：

- FFmpeg 可直接使用的 PPT / 白板关键帧时间点；
- 带证据时间点的逐集教学报告；
- 每一步都讲清“目的、做得好、做得不好”的用户研究 SOP；
- 面向学员、业务同学的中文培训手册。

它不替用户“补课”：课程没有讲、画面没有看清、音频没有听清的地方，会写成“待确认”。输出默认说大白话，不把概念堆成黑话。

## 快速使用

把 `user-research-training-distiller/` 放到 Codex Skills 目录，或从这个仓库按你自己的 Skill 安装方式安装。然后可以这样说：

```text
使用 user-research-training-distiller，严格根据我提供的课程视频，
给我一份可用 FFmpeg 精确截取关键帧的逐集报告。
```

或者：

```text
使用 user-research-training-distiller，把这几节原始课程串成一条用户研究 SOP。
每一步讲清目的、好例子和坏例子；语言说人话；课程没讲到的地方写待确认。
```

## 隐私与来源边界

这个仓库不包含原始课程视频、截图、逐字稿、内部链接、讲师资料或学员数据。它只提供工作流和交付格式。任何对课程内容的结论，都必须回到调用时提供的原始来源核验。

详见 [SKILL.md](SKILL.md) 和 [交付格式与质量门](references/output-contract.md)。
