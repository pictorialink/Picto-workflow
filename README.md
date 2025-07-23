## 工作流维护仓库

### 介绍
这是一个用于维护工作流的仓库，包含了多个工作流的json和eson及其对应的脚本文件。

### 工作流列表
- box_to_img: 区域生图（框生图）
- brush_doodle_to_img: 笔刷生图
- txt_to_box: 智能构图（文本框）
- refine_img: refine 生图
- local_redrawing: 局部重绘
- text_to_img: 文本图
- img_guidance: 提取主体、背景文本
- pencil_sketch.eson: 草图生图/风格化
- stylize_img.eson: 草图生图/风格化
- smart_fusion: 智能融合
- pose_to_img: pose 生图
- img_to_txt: 图推文、草图推词

### 注意

1. main分支内容为pictorial应用正在使用的工作流；
2. workflow.json 是 ComfyUI 原生工作流 json 文件
3. workflow.eson 是适配客户端的 eson 文件


