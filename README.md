# Awesome-Computer-Vision-Image-Classification

# Awesome-Computer-Vision-Image-Classification

# Top Computer Vision Image Classification Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual Recognition, Deep Learning & Production Inference*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer Vision Image Classification**. These tools enable developers and organizations to build, train, and deploy models that classify images into categories — powering use cases from content moderation to medical imaging, industrial quality control, and retail analytics.

**Examples** include Salesforce Einstein Image Classification, Google Cloud Vision, AWS Rekognition, Azure Computer Vision, Clarifai, Roboflow, Landing AI, Nyckel, V7 Go, and Scale AI (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom model training, and production inference pipelines — ideal for researchers, ML engineers, and developers seeking transparent, vendor-independent computer vision solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Einstein Image Classification](https://www.salesforce.com/)**  
  Einstein Vision service enabling developers to build deep learning models for image classification and object detection. Supports multi-label classification and custom training with your own datasets. Integrates directly with Salesforce CRM workflows .

- **[Google Cloud Vision](https://cloud.google.com/vision)**  
  Pre-trained and customizable computer vision models for image classification, object detection, OCR, and content moderation. Label detection returns recognized labels with confidence and topicality scores. Python, Go, and Java client libraries available .

- **[AWS Rekognition](https://aws.amazon.com/rekognition/)**  
  Deep learning-based image and video analysis service. Features object/scene detection, text detection, unsafe content moderation, celebrity recognition, facial analysis, and Custom Labels for training classifiers on proprietary objects .

- **[Azure Computer Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)**  
  Prebuilt and customizable models for image analysis, tagging, caption generation, and domain-specific detection (celebrities, landmarks). Supports custom model training with your own images .

- **[Clarifai](https://www.clarifai.com/)**  
  Production tagging platform with model training and customization. Supports versioned models for repeatable inference baselines and configurable threshold governance for audit-ready deployments .

- **[Roboflow](https://roboflow.com/)**  
  Dataset preparation and deployment platform with versioning and managed annotation workflows. Preserves traceability into training exports for controlled label iteration .

- **[Landing AI](https://landing.ai/)**  
  Computer vision platform focused on data-centric AI. Provides tools for visual inspection, defect detection, and model deployment for industrial and enterprise use cases .

- **[Nyckel](https://www.nyckel.com/)**  
  No-code AI platform for image and text classification. Provides dataset management, training, and evaluation controls tied to iterative model updates for controlled change behavior .

- **[V7 Go](https://www.v7labs.com/)**  
  AI-powered document and image analysis platform. Combines computer vision with document understanding for automated data extraction and classification workflows .

- **[Scale AI](https://scale.com/)**  
  Data platform for AI with annotation, curation, and model evaluation services. Supports computer vision teams with training data pipelines for classification and detection models.

## Open-Source GitHub Projects

- **[PyTorch](https://github.com/pytorch/pytorch)**  
  Leading open-source deep learning framework (BSD license) with first-class support for computer vision. TorchVision provides pretrained ResNet, VGG, EfficientNet, and ConvNeXt models with ImageNet weights, plus data loading and augmentation utilities. Foundation for most modern CV research and production systems .

- **[TorchVision](https://github.com/pytorch/vision)**  
  Official PyTorch library for computer vision (BSD license). Features classification, detection, and segmentation models with pretrained weights. Includes transforms, datasets (ImageNet, CIFAR, MNIST), and ONNX export support. 120 FPS inference on V100 for ResNet variants .

- **[TensorFlow](https://github.com/tensorflow/tensorflow)**  
  End-to-end open-source ML platform (Apache-2.0). Keras high-level API for building image classification models, with prebuilt layers for CNNs, data augmentation, and transfer learning. TensorFlow Lite enables mobile and edge deployment.

- **[Timm (PyTorch Image Models)](https://github.com/huggingface/pytorch-image-models)**  
  Massive collection of pretrained image classification models (Apache-2.0). Includes ResNet, EfficientNet, ViT, Swin Transformer, ConvNeXt, and hundreds more with pretrained weights. Standard library for state-of-the-art CV model access .

- **[OpenMMLab MMPretrain](https://github.com/open-mmlab/mmpretrain)**  
  OpenMMLab pre-training toolbox and benchmark (Apache-2.0). Provides unified interface for training and evaluating image classification models. Includes configs for ResNet, ViT, Swin, ConvNeXt, and other architectures. Part of the comprehensive OpenMMLab CV ecosystem .

- **[PaddleClas](https://github.com/PaddlePaddle/PaddleClas)**  
  Visual classification and recognition toolbox by PaddlePaddle (Apache-2.0). Features 200+ pretrained models, knowledge distillation, and deployment tools. 5,400+ GitHub stars. Includes practical industrial classification recipes .

- **[FastAI](https://github.com/fastai/fastai)**  
  High-level deep learning library (Apache-2.0) built on PyTorch. Simplifies image classification with best practices baked in. Includes `vision_learner` for quick model training and `interpret` module for model analysis .

- **[FujiCV](https://github.com/fujicv/fujicv)**  
  Open-source Python package for image classification and regression (license varies) built on timm + torchvision. Features backbone factory for any timm model, classification/regression/multilabel task heads, 15 loss functions, 16 metrics, Optuna HPO, ONNX export, and W&B integration .

- **[Detectron2](https://github.com/facebookresearch/detectron2)**  
  Modular detection and segmentation framework by Facebook AI Research (Apache-2.0). Includes classification backbones and utilities. Foundation for many production CV systems .

- **[MMDetection](https://github.com/open-mmlab/mmdetection)**  
  OpenMMLab detection toolbox (Apache-2.0) with classification components. 85 FPS inference on V100. Comprehensive configs and pretrained models for industrial CV applications .

- **[SuperGradients](https://github.com/Deci-AI/super-gradients)**  
  Training library for computer vision models (Apache-2.0). Provides recipes for classification, detection, and segmentation with automatic hyperparameter tuning and hardware-aware optimization .

- **[FiftyOne](https://github.com/voxel51/fiftyone)**  
  Open-source tool (Apache-2.0) for curating high-quality datasets and refining visual AI models. Features dataset visualization, model evaluation, and embedding analysis. 8,800+ GitHub stars. Essential for dataset-centric workflows .

- **[Gradio](https://github.com/gradio-app/gradio)**  
  Build and share ML demos (Apache-2.0). Quick UI for image classification models with file upload, webcam capture, and real-time inference. Widely used for model prototyping and stakeholder demos.

### Additional Strong Open-Source Options

- **[OpenCV](https://github.com/opencv/opencv)** — The most widely used computer vision library (Apache-2.0) with DNN module for running classification models .
- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)** — Classic ML library (BSD) with SVM, random forest, and other classifiers for feature-based image classification.
- **[Label Studio](https://github.com/HumanSignal/label-studio)** — General-purpose labeling platform (Apache-2.0) for building classification training datasets .
- **[CVAT](https://github.com/cvat-ai/cvat)** — Computer vision annotation tool (MIT) for image labeling and dataset management .
- **[LabelImg](https://github.com/HumanSignal/labelImg)** — Simple image labeling tool (MIT) for classification and detection datasets .
- **[Cleanlab](https://github.com/cleanlab/cleanlab)** — Data-centric AI library (AGPL) for finding label errors and training robust classifiers.
- Community **HuggingFace** model hubs for pretrained classification models and **Weights & Biases** for experiment tracking.

**Frameworks for building custom systems**: Combine **PyTorch** with **Timm** for access to state-of-the-art pretrained backbones, **FujiCV** or **FastAI** for streamlined training pipelines, **FiftyOne** for dataset curation and model evaluation, and **ONNX Runtime** or **TensorRT** for optimized inference — creating a fully self-hosted, production-grade image classification stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Image classification systems must comply with privacy, biometric, and data protection regulations (GDPR, BIPA, CCPA, etc.).
- Self-hosted open-source solutions require proper GPU provisioning, model versioning, and ongoing maintenance for production reliability.

---

**Made for ML engineers, data scientists, researchers, and developers building transparent computer vision solutions.**  
Let's make image classification more open, data-driven, and accessible.
