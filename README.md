# Awesome-Computer-Vision-Image-Classification

# Awesome-Computer-Vision-Image-Classification

## Top Computer Vision Image Classification Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Visual Recognition, Deep Learning & Production Inference*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer Vision Image Classification**. These tools enable developers and organizations to build, train, and deploy models that classify images into categories — powering use cases from content moderation to medical imaging, industrial quality control, and retail analytics.



**Examples** include Salesforce Einstein Image Classification, Google Cloud Vision, AWS Rekognition, Azure Computer Vision, Clarifai, Roboflow, Landing AI, Nyckel, V7 Go, and Scale AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom model training, and production inference pipelines — ideal for researchers, ML engineers, and developers seeking transparent, vendor-independent computer vision solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global computer vision market is estimated at approximately $23B to $33B in 2025–2026, projected to surpass $80B–$100B+ into the mid-2030s at a CAGR of ~15%–19%. The sector exhibits **moderate concentration / fragmentation**: while core foundational models and cloud compute APIs are concentrated among hyperscale cloud providers (Microsoft, Alphabet, Amazon), the broader ecosystem is fragmented across specialized platforms for visual inspection, data-centric annotation, and domain-specific classification.

## SaaS/Hosted Platforms

| Platform | Company | Company Scale (Market Cap / Valuation / Revenue) | Description | Pricing (Starting Paid Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Google Cloud Vision](https://cloud.google.com/vision)** | Alphabet / Google | ~$4.2T Market Cap (~$403B+ Rev) | Pre-trained and AutoML vision models for label detection, classification, OCR, and moderation. | $1.50 per 1,000 units (1,001–5,000,000 units/mo) | 1,000 units per month free forever (plus $300 new customer credit) |
| **[Azure Computer Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)** | Microsoft | ~$3.9T Market Cap (~$331.8B Rev) | Prebuilt and customizable models for image tagging, classification, caption generation, and domain detection. | $1.00 per 1,000 transactions (Standard S1 tier) | 5,000 transactions per month (F0 Free Tier, max 20 calls/min) |
| **[AWS Rekognition](https://aws.amazon.com/rekognition/)** | Amazon | ~$2.7T Market Cap (~$600B+ Rev) | Deep learning image & video analysis for object/scene classification, moderation, and Custom Labels. | $1.00 per 1,000 images analyzed (Tier 1: first 1M images/mo) | 5,000 images analyzed per month during the 12-month AWS Free Tier |
| **[Salesforce Einstein Image Classification](https://www.salesforce.com/)** | Salesforce | ~$187B Market Cap (~$41.5B Rev) | Deep learning image classification and object detection service integrated with Salesforce CRM workflows. | $25/user/month (Starter Suite) to $500+/mo via Einstein add-on credits / Agentforce usage packs | 2,000 free prediction calls/month (developer tier historically) or 30-day trial |
| **[Scale AI](https://scale.com/)** | Scale AI | ~$29B Valuation (~$1B Rev) | Data curation, automated labeling, and model evaluation platform for production classification pipelines. | $0.05 per labeling unit (Self-Serve pay-as-you-go above allowance) | 1,000 labeling units & 10,000 images in free self-serve tier |
| **[Clarifai](https://www.clarifai.com/)** | Clarifai (Nebius) | ~$100M+ Raised / Acquired | Visual AI tagging and classification platform supporting custom model training and evaluation. | $30/month (Essential plan) | 1,000 operations (API calls) per month free forever (Community plan) |
| **[Roboflow](https://roboflow.com/)** | Roboflow | ~$60M+ Raised | End-to-end computer vision platform with dataset versioning, auto-labeling, and model deployment. | $39/month billed annually ($99/month billed monthly, Core plan) | $60/month recurring credits (up to 10 projects, 250k public images) |
| **[Landing AI](https://landing.ai/)** | Landing AI | ~$57M Raised (~$34.2M Rev) | Data-centric computer vision platform specialized in visual inspection, defect detection, and document extraction. | $250/month (Team plan) or $0.01 per extraction credit pay-as-you-go | 14-day free trial with 1,000 free credits |
| **[V7 Go](https://www.v7labs.com/)** | V7 Labs | ~$33M–$36M Raised/Valuation | Multimodal AI platform combining computer vision with document understanding and classification workflows. | $5,400/year (Darwin Team) / custom annual contracts for V7 Go | Free forever plan with baseline Go Tokens allocation for workflows |
| **[Nyckel](https://www.nyckel.com/)** | Nyckel | ~$3M Estimated Annual Rev | Quick-deploy API and no-code platform for custom image and text classification. | $149/month (Standard tier) | 1,000 classifications per month free forever |

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
