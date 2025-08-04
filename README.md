# AI多模型抠图比对器

一个基于Streamlit的AI图像背景移除工具，支持多种AI模型的比较和批量处理。

## 功能特点

- 🎯 **多模型支持**: 支持多种AI抠图模型
- 🔄 **批量比较**: 同时使用多个模型处理同一张图片
- 📏 **尺寸控制**: 支持自定义输出图片尺寸
- 🎨 **多种缩放模式**: 保持比例、拉伸填充、裁剪适应、居中填充
- 💾 **多格式输出**: 支持PNG和JPEG格式
- 🖼️ **实时预览**: 即时查看处理结果

## 快速开始

### 环境要求

- Python 3.8+
- Streamlit
- rembg
- Pillow
- OpenCV

### 安装依赖

```bash
pip install streamlit rembg pillow opencv-python
```

### 启动应用

#### 方法1：使用批处理文件（推荐）

双击运行 `start_complete_fixed.bat`

#### 方法2：命令行启动

```bash
streamlit run multi_model_comparator_complete_fixed.py --server.port 8505
```

### 访问应用

打开浏览器访问：http://localhost:8505

## 使用说明

1. **上传图片**: 在左侧边栏上传要处理的图片
2. **选择模型**: 选择要使用的AI模型
3. **设置尺寸**: 选择输出图片尺寸（原始/常用/自定义）
4. **选择缩放模式**: 选择图片缩放方式
5. **开始处理**: 点击处理按钮开始抠图
6. **查看结果**: 查看和下载处理结果

## 项目结构