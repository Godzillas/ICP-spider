## 警告

本项目仅限用于学习研究

任何后果与本人无关

## 特点

- 使用yolov8识别滑动验证码，用魔法打败魔法
- 准确率在95%以上，如有需要可自行训练模型
- 超高性能，CPU识别一次仅需50ms
- 直接对接官网，数据权威准确
- 在线体验 [![](https://app.roboflow.com/images/try-model-badge.svg)](https://universe.roboflow.com/ravizhan-xc2or/captcha-border-detection/model/)

## 使用方法
安装依赖

```
pip install -r requirements.txt
```

修改`main.py`中要查询的域名 

运行 `main.py` 即可

## 备注

- 官网反爬策略较为玄学，请勿疯狂请求

- 项目中有两种格式的模型，CPU推理使用`onnx`更快，GPU推理使用`pt`更快，默认为`onnx`

  位置在`capture.py`

- 本模型使用预训练模型yolov5n进行训练