# awesome-SD-UI
An awesome list of related projects based on the Stable Diffusion UI.

一个Stable Diffusion UI相关项目的惊奇列表。

⚠️请注意：
- 本列表原则上仅支持中文（主要为国内用户服务）。
- 本列表不求全，只求实用，以便帮助国内用户顺利入门。

## 项目地址
- 本项目国际地址：`https://github.com/hyper0x/awesome-SD-UI`。
- 本项目国内地址（镜像）：`https://gitee.com/hyper0x/awesome-SD-UI`。

## 作者
- 工信部工业文化发展中心认可的AIGC导师，AIGC技能普及者和证书推广者；
- 中国移动通信联合会认可的ICT行业专家级讲师；
- 曾为国内知名的Go语言编程专家（已隐退），出版发行过多部相关的教程、图书和专栏；
- SFBT取向的心理教练、动力催眠师，以及正念冥想的实践者。

## 版权说明
🌟本项目遵循 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 协议。

以下是此协议的简要说明：

本许可允许再使用者以任何媒介或格式分发、重新混合、改编和构建材料，但仅限于非商业目的，并且前提是注明出处。如果您重新混合、改编或基于材料进行构建，则必须根据相同的条款许可修改后的材料。

CC BY-NC-SA 包括以下元素： 
- BY：必须归功于创作者。
- NC：只允许将作品用于非商业用途。
- SA：改编作品必须在相同的条款下共享。

## 提交说明
如果你知道一些这里未曾列出的惊奇项目，欢迎提交[issue](https://github.com/hyper0x/awesome-SD-UI/issues/new)或[PR](https://github.com/hyper0x/awesome-SD-UI/compare)。

## 赞助
欢迎使用“爱发电”为我提供[赞助](https://afdian.net/a/hyper0x)！谢谢！

## 惊奇列表

### 1. Web UI

#### 1.1 衍生版
- [stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)：ControlNet作者的最新力作！Stable Diffusion WebUI Forge是一个基于[Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)（基于[Gradio](https://www.gradio.app)）的平台，可简化开发、优化资源管理并加快推理速度。“Forge”这个名字的灵感来自“Minecraft Forge”。这个项目旨在成为SD WebUI的Forge。

#### 1.2 插件（extension）
- [stable-diffusion-webui-localization-zh_Hans](https://github.com/hanamizuki-ai/stable-diffusion-webui-localization-zh_Hans)：简体中文翻译插件。
- [sd-webui-oldsix-prompt](https://github.com/thisjam/sd-webui-oldsix-prompt)：非常便捷的提示词库插件，话不多说，安装上就知道了。
- [sd-webui-prompt-all-in-one](https://github.com/Physton/sd-webui-prompt-all-in-one)：旨在提高提示词/反向提示词输入框使用体验的提示词库插件。它拥有更直观、强大的输入界面功能，它提供了自动翻译、历史记录和收藏等功能，它支持多种语言，满足不同用户的需求。
- [stable-diffusion-webui-wd14-tagger](https://github.com/picobyte/stable-diffusion-webui-wd14-tagger)：图像提示词猜测插件。该插件使用各种模型（例如DeepDanbooru）查询单个或多个图像文件的booru样式标签。
- [sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet)：Stable Diffusion必备插件！该插件基于[ControlNet](https://github.com/lllyasviel/ControlNet)，以及其他的以注入为基础的控件。ControlNet是一种神经网络结构，通过添加额外条件来控制扩散模型。
- [adetailer](https://github.com/Bing-su/adetailer)：脸部、手部修复插件。该插件可智能识别人物的脸部、手部等容易出错的部位，进行单独精修重绘，再拼回原图。
- [sd-webui-inpaint-anything](https://github.com/Uminosachi/sd-webui-inpaint-anything)：此插件基于[Segment Anything](https://github.com/facebookresearch/segment-anything)，可进行图像分割，并可作为蒙版重绘和图片修复的基础。使用Segment Anything，用户只需选择分割后的区域即可指定蒙版，而无需手动划定。这可以显著提高蒙版创建过程的效率和准确性，从而获得更高质量的修复结果，节省时间和精力。
- [sd-webui-deforum](https://github.com/deforum-art/sd-webui-deforum)：动画生成插件。该插件可实现文本自动生成视频的功能，甚至可将现有的视频转换为动画。
- [sd-webui-animatediff](https://github.com/continue-revolution/sd-webui-animatediff)：GIF生成插件。该插件可以让你用与生成图像完全相同的方式生成GIF。针对Stable Diffusion WebUI Forge，该插件作者还创建了[sd-forge-animatediff](https://github.com/continue-revolution/sd-forge-animatediff)。
- [sd-webui-qrcode-toolkit](https://github.com/antfu/sd-webui-qrcode-toolkit)：花式二维码生成插件，可以将图像与二维码结合起来。

### 2. ComfyUI

#### 2.1 插件（extension）
- [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)：ComfyUI-Manager是一个旨在增强ComfyUI可用性的扩展。它提供了安装、删除、禁用和启用ComfyUI的各种自定义节点的管理功能。此外，该扩展还提供了hub特性和便利函数，可以在ComfyUI中访问各种信息。

#### 2.2 工作流（workflow）


### 3. 模型（model）

#### 3.1 风格模型（checkpoint）


#### 3.2 控制网模型（controlnet）


#### 3.3 LoRA模型（LoRA）


### 4. 教程（tutorial）

#### 4.1 中文（zh）


#### 4.2 英文（en）


### 5. 服务（Service）
- [Huggingface镜像站](https://hf-mirror.com)：本站域名`hf-mirror.com`，用于镜像`huggingface.co`域名。作为一个公益项目，致力于帮助国内AI开发者快速、稳定的下载模型、数据集。


## 写在最后
谢谢阅读。希望本项目能够帮助到你！
