# GitHub 图生视频仓库整理

## 📋 概述
本文档整理了 GitHub 上热门的图像生成视频（Image-to-Video）和文本生成视频（Text-to-Video）相关仓库，按功能分类介绍了各仓库的核心能力和应用场景。

---

## 🎬 核心文本转视频生成模型

### 1. **CogVideo** ⭐ 12.8K
- **链接**: https://github.com/zai-org/CogVideo
- **描述**: 文本和图像转视频生成：CogVideoX (2024) 和 CogVideo (ICLR 2023)
- **核心能力**:
  - 文本到视频生成
  - 图像到视频生成
  - 多代数模型支持
  - ICLR 2023 发表
  - 高质量视频生成
- **应用场景**: 创意视频创作、内容生成、学术研究

### 2. **Tune-A-Video** ⭐ 4.4K
- **链接**: https://github.com/showlab/Tune-A-Video
- **描述**: [ICCV 2023] 图像扩散模型的单步调整用于文本转视频生成
- **核心能力**:
  - 基于扩散模型的文本转视频
  - 快速模型调整
  - 高效生成
  - ICCV 2023 Oral 论文
- **应用场景**: 高效视频生成、模型微调

### 3. **Text2Video-Zero** ⭐ 4.2K
- **链接**: https://github.com/Picsart-AI-Research/Text2Video-Zero
- **描述**: [ICCV 2023 Oral] 文本转图像扩散模型是零样本视频生成器
- **核心能力**:
  - 零样本视频生成
  - 文本条件控制
  - 无需训练直接生成
  - ICCV 2023 Oral 论文
- **应用场景**: 快速视频生成、无需训练的应用

---

## 🎭 人像/说话头视频生成

### 4. **InfiniteTalk** ⭐ 6.8K
- **链接**: https://github.com/MeiGen-AI/InfiniteTalk
- **描述**: 无限长说话头视频生成，支持图像到视频和视频到视频生成
- **核心能力**:
  - 长时间说话头视频
  - 图像到视频转换
  - 视频到视频转换
  - 音频驱动动画
  - 流畅的嘴唇同步
- **应用场景**: 虚拟主播、数字化身、直播主播

### 5. **MusePose** ⭐ 2.7K
- **链接**: https://github.com/TMElyralab/MusePose
- **描述**: 基于姿态驱动的图像到视频框架，用于虚拟人类生成
- **核心能力**:
  - 姿态驱动的动画
  - 图像到视频转换
  - 虚拟人类生成
  - 舞蹈和动作控制
- **应用场景**: 虚拟化身、舞蹈视频、运动生成

### 6. **V-Express** ⭐ 2.4K
- **链接**: https://github.com/tencent-ailab/V-Express
- **描述**: 在参考图像、音频和 V-Kps 图像序列控制下生成说话头视频
- **核心能力**:
  - 多条件说话头视频生成
  - 音频驱动
  - 表情和动作控制
  - 高质量动画
- **应用场景**: 虚拟主播、数字化身、视频消息

### 7. **StableAnimator** ⭐ 1.4K
- **链接**: https://github.com/Francis-Rings/StableAnimator
- **描述**: [CVPR2025] 首个端到端 ID 保持视频扩散框架，从参考图像和姿态序列合成高质量视频
- **核心能力**:
  - ID 保持（面部识别）
  - 扩散变换器架构
  - 无后处理合成
  - 姿态驱动
  - CVPR 2025 论文
- **应用场景**: 人脸保留的视频生成、深度伪造防护

### 8. **StableAvatar** ⭐ 1.2K
- **链接**: https://github.com/Francis-Rings/StableAvatar
- **描述**: 首个端到端视频扩散变换器，从参考图像和音频合成无限长高质量音频驱动化身视频
- **核心能力**:
  - 音频驱动化身视频
  - 无限长视频
  - 扩散变换器
  - 无后处理
  - 流畅动画
- **应用场景**: 虚拟主播、数字化身、配音视频

### 9. **DreamPose** ⭐ 1.0K
- **链接**: https://github.com/johannakarras/DreamPose
- **描述**: 官方实现 "DreamPose: 通过 Stable Diffusion 进行时尚图像到视频合成"
- **核心能力**:
  - 时尚服装视频合成
  - 姿态转换
  - 基于扩散的生成
  - 服装保留
- **应用场景**: 时尚展示、虚拟试穿、服装营销

### 10. **DreamID-V** ⭐ 648
- **链接**: https://github.com/bytedance/DreamID-V
- **描述**: 通过扩散变换器桥接图像到视频间隙，用于高保真面部交换
- **核心能力**:
  - 高保真人脸交换
  - 图像到视频扩展
  - 扩散变换器
  - 身份保持
- **应用场景**: 面部交换、虚拟化身、创意效果

---

## 🎨 图像动画和运动生成

### 11. **HunyuanVideo-I2V** ⭐ 1.8K
- **链接**: https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V
- **描述**: 基于 HunyuanVideo 的可定制图像到视频模型
- **核心能力**:
  - 可定制的图像到视频
  - 高质量生成
  - 灵活控制
  - 腾讯混元技术
- **应用场景**: 自定义视频生成、内容创作

### 12. **MOFA-Video** ⭐ 766
- **链接**: https://github.com/MyNiuuu/MOFA-Video
- **描述**: [ECCV 2024] 通过生成运动场自适应进行可控图像动画
- **核心能力**:
  - 可控图像动画
  - 运动场生成
  - 冻结模型自适应
  - ECCV 2024 论文
- **应用场景**: 图像动画化、创意视频效果

### 13. **DepthFlow** ⭐ 1.4K
- **链接**: https://github.com/BrokenSource/DepthFlow
- **描述**: 图像转差视差效果视频
- **核心能力**:
  - 深度估计
  - 视差效果
  - 3D 视觉效果
  - 平滑动画
- **应用场景**: 创意视频效果、社交媒体内容

---

## 🎯 特定场景视频生成

### 14. **ASCII-generator** ⭐ 8.3K
- **链接**: https://github.com/vietnh1009/ASCII-generator
- **描述**: ASCII 生成器（图像转文本、图像转图像、视频转视频）
- **核心能力**:
  - 图像到 ASCII 艺术
  - 视频到 ASCII 视频
  - 视觉效果转换
  - 创意过滤
- **应用场景**: 艺术转换、创意效果、视频美化

### 15. **Cartoonize** ⭐ 622
- **链接**: https://github.com/experience-ml/cartoonize
- **描述**: 将图像和视频转换为卡通风格的演示 Web 应用
- **核心能力**:
  - 卡通化转换
  - 图像和视频支持
  - Web 应用
  - 实时处理
- **应用场景**: 视频美化、卡通化处理、内容创作

### 16. **DeepMosaics** ⭐ 2.6K
- **链接**: https://github.com/HypoX64/DeepMosaics
- **描述**: 自动移除或添加图像和视频中的马赛克
- **核心能力**:
  - 马赛克去除和添加
  - 视频处理
  - 深度学习模型
  - 隐私保护
- **应用场景**: 隐私保护、视频编辑、内容处理

---

## 🛠️ 工作流和集成工具

### 17. **ComfyUI-PainterI2V** ⭐ 612
- **链接**: https://github.com/princepainter/ComfyUI-PainterI2V
- **描述**: 增强的 Wan2.2 图像到视频节点，专门设计用于修复 4 步 LoRA 中的慢动作问题
- **核心能力**:
  - ComfyUI 集成节点
  - 图像到视频转换
  - LoRA 支持
  - 慢动作修复
- **应用场景**: ComfyUI 工作流集成

### 18. **ComfyUI-AnimateAnyone-Evolved** ⭐ 560
- **链接**: https://github.com/MrForExample/ComfyUI-AnimateAnyone-Evolved
- **描述**: 改进的 AnimateAnyone 实现，允许使用姿态图像序列和参考图像生成风格化视频
- **核心能力**:
  - AnimateAnyone 改进版
  - 姿态驱动动画
  - 风格化生成
  - ComfyUI 节点
- **应用场景**: ComfyUI 创意工作流

### 19. **MiniMax-MCP** ⭐ 1.5K
- **链接**: https://github.com/MiniMax-AI/MiniMax-MCP
- **描述**: 官方 MiniMax 模型上下文协议（MCP）服务器，支持文本转语音、图像生成和视频生成 API
- **核心能力**:
  - MCP 服务器
  - 文本转视频 API
  - 图像生成 API
  - 文本转语音 API
- **应用场景**: API 集成、多模态应用

### 20. **ComfyUI_Qwen3-VL-Instruct** ⭐ 550
- **链接**: https://github.com/IuvenisSapiens/ComfyUI_Qwen3-VL-Instruct
- **描述**: Qwen3-VL-Instruct 系列到 ComfyUI 平台的集成，支持文本查询、视频查询、单图查询和多图查询
- **核心能力**:
  - 多模态查询
  - 视频理解
  - 图像字幕
  - ComfyUI 集成
- **应用场景**: 视频理解、图像字幕生成

### 21. **Bjornulf_custom_nodes** ⭐ 535
- **链接**: https://github.com/justUmen/Bjornulf_custom_nodes
- **描述**: ComfyUI：163 个节点，用于显示、操作和编辑文本、图像、视频、LoRA 等
- **核心能力**:
  - 163 个自定义节点
  - 视频处理节点
  - 文本和图像处理
  - LoRA 管理
- **应用场景**: ComfyUI 全能工作流

---

## 📊 视频理解和分析

### 22. **ClassyVision** ⭐ 1.6K
- **链接**: https://github.com/facebookresearch/ClassyVision
- **描述**: 端到端 PyTorch 框架，用于图像和视频分类
- **核心能力**:
  - 视频分类
  - 图像分类
  - 端到端学习框架
  - Facebook Research
- **应用场景**: 视频分类、内容分析

### 23. **ClipBERT** ⭐ 730
- **链接**: https://github.com/jayleicn/ClipBERT
- **描述**: [CVPR 2021 最佳学生论文荣誉奖，Oral] 图像-文本和视频-文本任务的端到端学习框架
- **核心能力**:
  - 视频-文本对齐
  - 多模态理解
  - 高效框架
  - CVPR 2021 获奖
- **应用场景**: 视频理解、视频字幕生成

### 24. **UForm** ⭐ 1.2K
- **链接**: https://github.com/unum-cloud/UForm
- **描述**: 内容理解和生成的袖珍多模态 AI，支持多语言文本、图像和视频
- **核心能力**:
  - 多模态理解
  - 文本和视频处理
  - 多语言支持
  - 5 倍快于 CLIP
- **应用场景**: 视频理解、内容生成

### 25. **eb_jepa** ⭐ 672
- **链接**: https://github.com/facebookresearch/eb_jepa
- **描述**: 联合嵌入预测架构（JEPA）的开源库，包含来自图像、视频和动作条件视频的表示学习代码
- **核心能力**:
  - 视频表示学习
  - 动作条件模型
  - 规划框架
- **应用场景**: 视频理解、行为预测

---

## 📝 文本到视觉生成

### 26. **Aphantasia** ⭐ 791
- **链接**: https://github.com/eps696/aphantasia
- **描述**: CLIP + FFT/DWT/RGB = 文本到图像/视频
- **核心能力**:
  - 文本到图像生成
  - 文本到视频生成
  - 频率域处理
  - CLIP 模型利用
- **应用场景**: 创意视觉生成

### 27. **DesmosBezierRenderer** ⭐ 700
- **链接**: https://github.com/kevinjycui/DesmosBezierRenderer
- **描述**: 简单的图像/视频转 Desmos 图表转换器，本地运行
- **核心能力**:
  - 图像转矢量图
  - 视频处理
  - Desmos 兼容
  - 本地运行
- **应用场景**: 艺术转换、教育可视化

---

## 🔍 数据处理和质量工具

### 28. **fastdup** ⭐ 1.9K
- **链接**: https://github.com/visual-layer/fastdup
- **描述**: 强大的免费工具，用于快速从图像和视频数据集生成有价值的见解
- **核心能力**:
  - 数据集分析
  - 重复检测
  - 质量评估
  - 标签改进
  - 可扩展性强
- **应用场景**: 数据集清理、质量管理

### 29. **auto-archiver** ⭐ 1.1K
- **链接**: https://github.com/bellingcat/auto-archiver
- **描述**: 自动从 Google Sheets 和更多来源归档视频、图像和社交媒体内容的链接
- **核心能力**:
  - 自动归档
  - 多来源支持
  - 视频下载
  - 批量处理
- **应用场景**: 内容归档、数据收集

### 30. **Pinry** ⭐ 3.4K
- **链接**: https://github.com/pinry/pinry
- **描述**: 图像板系统，用于保存、标记和共享图像、视频和网页
- **核心能力**:
  - 图像板平台
  - 视频托管
  - 标签系统
  - 开源自托管
- **应用场景**: 内容管理、图像共享平台

---

## 📈 能力对比表

| 仓库名称 | 文本转视频 | 图像转视频 | 说话头 | 人脸保留 | 姿态驱动 | 音频驱动 | Stars |
|---------|----------|----------|-------|--------|--------|--------|-------|
| CogVideo | ✅ | ✅ | - | - | - | - | 12.8K |
| Tune-A-Video | ✅ | ✅ | - | - | - | - | 4.4K |
| Text2Video-Zero | ✅ | - | - | - | - | - | 4.2K |
| InfiniteTalk | - | ✅ | ✅ | - | - | ✅ | 6.8K |
| MusePose | - | ✅ | - | - | ✅ | - | 2.7K |
| V-Express | - | ✅ | ✅ | - | - | ✅ | 2.4K |
| StableAnimator | - | ✅ | - | ✅ | ✅ | - | 1.4K |
| StableAvatar | - | ✅ | ✅ | - | - | ✅ | 1.2K |
| DreamPose | - | ✅ | - | - | ✅ | - | 1.0K |
| ASCII-generator | ✅ | ✅ | - | - | - | - | 8.3K |
| MOFA-Video | - | ✅ | - | - | - | - | 766 |
| DepthFlow | - | ✅ | - | - | - | - | 1.4K |

---

## 🎯 使用建议

### 文本转视频（最通用）
- **CogVideo** (12.8K ⭐): 最强大，支持文本和图像输入
- **Tune-A-Video** (4.4K ⭐): 快速高效，适合快速生成
- **Text2Video-Zero** (4.2K ⭐): 零样本方案，无需训练

### 虚拟主播/说话头生成
- **InfiniteTalk** (6.8K ⭐): 最完整的说话头方案
- **V-Express** (2.4K ⭐): 多条件控制，表情精细
- **StableAvatar** (1.2K ⭐): 音频驱动，质量高

### 人脸保留和交换
- **StableAnimator** (1.4K ⭐): ID 保持效果最好
- **DreamID-V** (648 ⭐): 高保真面部交换

### 姿态驱动动画
- **MusePose** (2.7K ⭐): 虚拟人类生成
- **DreamPose** (1.0K ⭐): 时尚服装视频

### 图像动画（有运动控制）
- **MOFA-Video** (766 ⭐): 可控运动场
- **DepthFlow** (1.4K ⭐): 视差效果

### ComfyUI 集成（工作流使用）
- **ComfyUI-PainterI2V** (612 ⭐): 图像到视频节点
- **ComfyUI-AnimateAnyone-Evolved** (560 ⭐): 动画生成
- **Bjornulf_custom_nodes** (535 ⭐): 全能节点集合

### 创意效果
- **ASCII-generator** (8.3K ⭐): ASCII 艺术风格
- **Cartoonize** (622 ⭐): 卡通化效果
- **Aphantasia** (791 ⭐): 频率域创意效果

### 数据处理
- **fastdup** (1.9K ⭐): 数据集质量管理
- **auto-archiver** (1.1K ⭐): 内容归档

---

## 🔗 相关链接
- [图生视频搜索结果](https://github.com/search?q=image+to+video+OR+text+to+video&sort=stars&type=repositories)
- [视频生成论文汇总](https://github.com/search?q=video+generation&type=repositories)

---

## 💡 技术趋势

### 新兴技术方向
1. **扩散变换器** - StableAnimator、StableAvatar 采用的新架构
2. **ID 保持** - 面部识别与身份保留的结合
3. **多模态控制** - 文本、音频、姿态等多条件驱动
4. **无限长视频** - InfiniteTalk、StableAvatar 的方向
5. **ComfyUI 集成** - 越来越多项目支持可视化工作流

### 应用前景
- 虚拟直播和主播自动化
- 电商虚拟试穿和展示
- 创意视频内容快速生成
- 教育和培训视频制作
- 社交媒体内容创作
- 企业视频营销

---

*文档生成时间: 2026-06-03*
*总仓库数: 6883 个图生视频相关项目（本文档展示前 30 个热门项目）*
