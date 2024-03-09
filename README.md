# comfyui-workflow
分享我所用到的 ComfyUI 高级工作流。

## 说明
👏 欢迎来到我的 ComfyUI 工作流集合地！

为了给大家提供福利，粗糙地搭建了一个平台，有什么反馈优化的地方，或者你想让我帮忙实现一些功能，可以提交 issue 或者邮件联系我 theboylzh@163.om。

### 如何使用

使用方法：
- 进入文件所在文件夹，下载 json 或者图片
- 直接在 ComfyUI 中加载即可生成工作流

工作流通常会使用很多第三方节点，所以下载下来免不了遇到报错，下面是安装缺失节点的方法。
https://www.bilibili.com/read/cv28500074/

## 文生图
### 输出多个风格
文件夹：[Advanced-Multiple-Style-With-Controlnet](https://github.com/theboylzh/comfyui-workflow/tree/8630c32f27ddbf3d88d157a85d02f1c77fcf7853/Advanced-Multiple-Style-With-Controlnet)

说明：这个工作流使用了 LCM 加速，多个风格 Lora，以及多个 Controlnet 来输出多个风格的图片。

工作流预览。
![工作流预览](https://github.com/theboylzh/comfyui-workflow/blob/main/Advanced-Multiple-Style-With-Controlnet/workflow.j-previewpeg.jpeg)

## 放大图片
注意，这里需要下载较多的节点和模型。包括：
- 去下载 controlnet tile SDXL 和 SD1.5 模型
- 安装第三方节点，ComfyUI-Advanced-ControlNet

另外你还需要：
- 下载放大模型 RealESRGAN 系列（按需下载即可，我的工作流只用到2倍放大模型）
- 下载第三方节点 Ultimate SD Upscale
- 工作流并非最完美，需要根据实际微调。图生图效果还不够好，等待我后续更新。


### 文生图
- SD1.5文件夹：[upscale-t2i-v15](https://github.com/theboylzh/comfyui-workflow/tree/749580543c66d0fb6d1e4e460bcc15bddc1b878f/upscale-t2i-v15)
- SDXL文件夹：[upscale-t2i-xl](https://github.com/theboylzh/comfyui-workflow/tree/749580543c66d0fb6d1e4e460bcc15bddc1b878f/upscale-t2i-xl)
 


- 工作流预览（SD1.5）
![工作流预览SD1.5](https://github.com/theboylzh/comfyui-workflow/blob/main/upscale-t2i-v15/preview.jpeg)
- 工作流预览（SDXL）
![工作流预览SDXL](https://github.com/theboylzh/comfyui-workflow/blob/main/upscale-t2i-xl/preview.jpeg)

### 图生图
- SD1.5文件夹：[upscale-i2i-v15](https://github.com/theboylzh/comfyui-workflow/tree/749580543c66d0fb6d1e4e460bcc15bddc1b878f/upscale-i2i-v15)
- SDXL文件夹：[upscale-i2i-xl](https://github.com/theboylzh/comfyui-workflow/tree/749580543c66d0fb6d1e4e460bcc15bddc1b878f/upscale-i2i-xl)
 


- 工作流预览（SD1.5）
![工作流预览SD1.5](https://github.com/theboylzh/comfyui-workflow/blob/main/upscale-i2i-v15/preview.jpeg)
- 工作流预览（SDXL）
![工作流预览SDXL](https://github.com/theboylzh/comfyui-workflow/blob/main/upscale-i2i-xl/preview.jpeg)


