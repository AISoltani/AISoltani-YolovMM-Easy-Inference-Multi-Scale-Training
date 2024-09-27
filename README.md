# AISoltani-Yolov10-Easy-Inference-Multi-Scale-Training
YOLOv10 toolbox for object detection, training, and benchmarking

<div align="center">
  <h1>OpenMMLab YOLO Series Toolbox</h1>
  <p>Your next-gen YOLO toolbox for object detection, training, and benchmarking.</p>
  
  [![License](https://img.shields.io/github/license/open-mmlab/mmyolo)](https://github.com/open-mmlab/mmyolo/blob/main/LICENSE)
  [![Open Issues](https://isitmaintained.com/badge/open/open-mmlab/mmyolo.svg)](https://github.com/open-mmlab/mmyolo/issues)
  [![Issue Resolution](https://isitmaintained.com/badge/resolution/open-mmlab/mmyolo.svg)](https://github.com/open-mmlab/mmyolo/issues)
  
  <p>English | <a href="README_zh-CN.md">简体中文</a></p>
  
  <p>
    <a href="https://openmmlab.medium.com/"><img src="https://user-images.githubusercontent.com/25839884/219255827-67c1a27f-f8c5-46a9-811d-5e57448c61d1.png" width="3%" alt="Medium" /></a>
    <a href="https://discord.com/channels/1037617289144569886/1046608014234370059"><img src="https://user-images.githubusercontent.com/25839884/218347213-c080267f-cbb6-443e-8532-8e1ed9a58ea9.png" width="3%" alt="Discord" /></a>
    <a href="https://twitter.com/OpenMMLab"><img src="https://user-images.githubusercontent.com/25839884/218346637-d30c8a0f-3eba-4699-8131-512fb06d46db.png" width="3%" alt="Twitter" /></a>
    <a href="https://www.youtube.com/openmmlab"><img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="YouTube" /></a>
  </p>
</div>

---

## Table of Contents
- [📘 Documentation](https://mmyolo.readthedocs.io/en/latest/)
- [🛠️ Installation](https://mmyolo.readthedocs.io/en/latest/get_started/installation.html)
- [👀 Model Zoo](https://mmyolo.readthedocs.io/en/latest/model_zoo.html)
- [🆕 Update News](https://mmyolo.readthedocs.io/en/latest/notes/changelog.html)
- [🤔 Reporting Issues](https://github.com/open-mmlab/mmyolo/issues/new/choose)
- [🚀 Quick Start](#quick-start)
- [🔧 Features](#features)
- [📊 Benchmark](#benchmark)
- [💻 Contributors](#contributors)

---

## Quick Start

Here's how you can get started with the OpenMMLab YOLO Toolbox:

```bash
# Clone the repository
git clone https://github.com/open-mmlab/mmyolo.git
cd mmyolo

# Install dependencies
pip install -r requirements.txt

# Run your first YOLO training
python tools/train.py configs/yolov5/yolov5_s_8xb16-300e_coco.py
