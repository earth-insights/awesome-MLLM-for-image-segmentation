[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/likyoo/awesome-MLLM-for-image-segmentation/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/likyoo/awesome-MLLM-for-image-segmentation)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/likyoo/awesome-MLLM-for-image-segmentation?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/likyoo/awesome-MLLM-for-image-segmentation?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/likyoo/awesome-MLLM-for-image-segmentation?style=social">

# <p align=center>`Awesome LLM/MLLM for Image Segmentation`</p>

## Related Task

**`[ReferIS]`**: Referring Image Segmentation  
**`[GRES]`**: Generalized Referring Expression Segmentation  
**`[ReasonIS]`**: Reasoning Image Segmentation  
**`[ReasonInstIS]`**: Reasoning Instance Image Segmentation  
**`[SiD]`**: Segmentation in Dialogue  
**`[GCG]`**: Grounded Conversation Generation  
**`[ReasonMIS]`**: Multi-image pixel-grounded Reasoning Segmentation
**`[MGSC]`**: MultiGranularity Segmentation and Captioning  
**`[ImgSemSeg]`**: Image Semantic Segmentation  
**`[ImgInstSeg]`**: Image Instance Segmentation  
**`[ImgPanSeg]`**: Image Panoptic Segmentation  
**`[ImgInteractSeg]`**: Image Iteractive Segmentation  
**`[OVSeg]`**: Open-Vocabulary Segmentation  
**`[VideoObjSeg]`**: Video Object Segmentation  
**`[ReferVOS]`**: Referring Video Object Segmentation  
**`[ReasonVOS]`**: Reasoning Video Object Segmentation  
**`[VideoInteractSeg]`**: Video Iteractive Segmentation  

Note: Only the tasks assessed in the paper are listed here.

## Survey

- Image Segmentation in Foundation Model Era: A Survey. arXiv'2024. [[paper](https://arxiv.org/abs/2408.12957)] | [[project](https://github.com/stanley-313/ImageSegFM-Survey)]
- Reasoning Segmentation for Images and Videos: A Survey. arXiv'2025. [[paper](https://arxiv.org/abs/2505.18816)]

## General

### MLLM with Segmentation Capability

- VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks. NeurIPS'2023. [[paper](https://arxiv.org/abs/2305.11175)] | [[code](https://github.com/OpenGVLab/VisionLLM)]
- VisionLLM v2: An End-to-End Generalist Multimodal Large Language Model for Hundreds of Vision-Language Tasks. NeurIPS'2024. [[paper](https://arxiv.org/abs/2406.08394)] | [[code](https://github.com/OpenGVLab/VisionLLM)]
- Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Xiao_Florence-2_Advancing_a_Unified_Representation_for_a_Variety_of_Vision_CVPR_2024_paper.html)] | [[code](https://huggingface.co/collections/microsoft/florence-6669f44df0d87d9c3bfb76de)]
- NExT-Chat: An LMM for Chat, Detection and Segmentation. ICML'2024. [[paper](https://arxiv.org/abs/2311.04498)] | [[code](https://github.com/NExT-ChatV/NExT-Chat)] | [[project](https://next-chatv.github.io/)]
- PaliGemma: A versatile 3B VLM for transfer. arXiv'2024. [[paper](https://arxiv.org/abs/2407.07726)] | [[code](https://github.com/google-research/big_vision)]
- PaliGemma 2: A Family of Versatile VLMs for Transfer. arXiv'2024. [[paper](https://arxiv.org/abs/2412.03555)] | [[code](https://github.com/google-research/big_vision)]
- REF-VLM: Triplet-Based Referring Paradigm for Unified Visual Decoding. arXiv'2025 [[paper](https://arxiv.org/abs/2503.07413)] | [[code](https://github.com/MacavityT/REF-VLM)]
- Patch-as-Decodable-Token: Towards Unified Multi-Modal Vision Tasks in MLLMs. arXiv'2025 [[paper](https://arxiv.org/abs/2510.01954)] | [[code](https://github.com/Gorilla-Lab-SCUT/PaDT)]

### Segmentation Model with LLM/MLLM

- **`[ReferIS][ReasonIS]`** LISA: Reasoning Segmentation via Large Language Model. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Lai_LISA_Reasoning_Segmentation_via_Large_Language_Model_CVPR_2024_paper.html)] | [[code](https://github.com/dvlab-research/LISA)]
- **`[ReferIS][ReasonIS][ReasonInstIS][SiD]`** LISA++: An Improved Baseline for Reasoning Segmentation with Large Language Model. arXiv'2023. [[paper](https://openreview.net/forum?id=NBQFAN228B)] | [[code](https://github.com/dvlab-research/LISA)]
- **`[ReferIS][GRES]`** GSVA: Generalized Segmentation via Multimodal Large Language Models. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Xia_GSVA_Generalized_Segmentation_via_Multimodal_Large_Language_Models_CVPR_2024_paper.html)] | [[code](https://github.com/LeapLabTHU/GSVA)]
- **`[ReferIS][ReasonIS]`** PixelLM: Pixel Reasoning with Large Multimodal Model. CVPR'2024. [[paper](https://arxiv.org/abs/2312.02228)] | [[code](https://github.com/MaverickRen/PixelLM)] | [[project](https://pixellm.github.io/)]
- **`[ReferIS][GCG]`** GLaMM: Pixel Grounding Large Multimodal Model. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Rasheed_GLaMM_Pixel_Grounding_Large_Multimodal_Model_CVPR_2024_paper.html)] | [[code](https://github.com/mbzuai-oryx/groundingLMM)] | [[project](https://mbzuai-oryx.github.io/groundingLMM/)]
- **`[ReferIS][GRES][ReasonIS]`** GROUNDHOG: Grounding Large Language Models to Holistic Segmentation. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_GROUNDHOG_Grounding_Large_Language_Models_to_Holistic_Segmentation_CVPR_2024_paper.html)] | [[project](https://groundhog-mllm.github.io/)]
- **`[ReasonIS]`** LLM-Seg: Bridging Image Segmentation and Large Language Model Reasoning. CVPRW'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024W/MMFM/html/Wang_LLM-Seg_Bridging_Image_Segmentation_and_Large_Language_Model_Reasoning_CVPRW_2024_paper.html)] | [[code](https://github.com/wangjunchi/LLMSeg)]
- **`[ReferIS][ReasonIS][GCG][ImgSemSeg][ImgInstSeg][ImgInteractSeg][ImgInteractSeg]`** OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding. NeurIPS'2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/83eb86be3e2f9fd66c44d9073c51ba4d-Abstract-Conference.html)] | [[code](https://github.com/lxtGH/OMG-Seg)] | [[project](https://lxtgh.github.io/project/omg_llava/)]
- **`[ReferIS][GRES][ImgSemSeg][ImgInstSeg][ImgInteractSeg][ImgInteractSeg][VideoObjSeg][OVSeg]`** PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model. ECCV'2024. [[paper](https://arxiv.org/abs/2403.14598)] | [[code](https://github.com/zamling/PSALM)]
- **`[ReferIS][GRES][ReasonIS]`** SAM4MLLM: Enhance Multi-Modal Large Language Model for Referring Expression Segmentation. ECCV'2024. [[paper](https://arxiv.org/abs/2409.10542)] | [[code](https://github.com/AI-Application-and-Integration-Lab/SAM4MLLM)]
- **`[ReferIS][ReasonIS][ReasonVOS]`** VISA: Reasoning Video Object Segmentation via Large Language Models. ECCV'2024. [[paper](https://arxiv.org/abs/2407.11325)] | [[code](https://github.com/cilinyan/VISA)]
- **`[ImgSemSeg][ReferIS][GRES]`** LaSagnA: Language-based Segmentation Assistant for Complex Queries. arXiv'2024. [[paper](https://arxiv.org/abs/2404.08506)] | [[code](https://github.com/congvvc/LaSagnA)]
- **`[ReferIS]`** EVF-SAM: Early Vision-Language Fusion for Text-Prompted Segment Anything Model. arXiv'2024. [[paper](https://arxiv.org/abs/2406.20076)] | [[code](https://github.com/hustvl/EVF-SAM)]
- **`[ReferIS][GRES][ReasonIS][GCG][MGSC]`** Instruction-guided Multi-Granularity Segmentation and Captioning with Large Multimodal Model. AAAI'2025. [[paper](https://arxiv.org/abs/2409.13407)] | [[code](https://github.com/lizhou-cs/mglmm)] | [[project](https://lizhou-cs.github.io/mglmm.github.io/)]
- **`[ReferIS][GRES]`** Text4Seg: Reimagining Image Segmentation as Text Generation. ICLR'2025. [[paper](https://arxiv.org/abs/2410.09855)] | [[code](https://github.com/mc-lan/Text4Seg)] | [[project](https://mc-lan.github.io/Text4Seg/)]
- **`[ReferIS][ReasonIS][ReferVOS][ReasonVOS]`** InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models. arXiv'2024. [[paper](https://arxiv.org/abs/2412.14006)] | [[code](https://github.com/congvvc/InstructSeg)]
- **`[ReasonMIS]`** PRIMA: Multi-Image Vision-Language Models for Reasoning Segmentation. arXiv'2024. [[paper](https://arxiv.org/abs/2412.15209)] | [[project](https://plan-lab.github.io/prima)]
- **`[ReferIS][GCG][ReferVOS][VideoInteractSeg]`** Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos. CVPRW'2025. [[paper](https://arxiv.org/abs/2501.04001)] | [[code](https://github.com/magic-research/Sa2VA)] | [[project](https://lxtgh.github.io/project/sa2va/)]
- **`[ReferIS][GRES][ReasonIS]`** HiMTok: Learning Hierarchical Mask Tokens for Image Segmentation with Large Multimodal Model. ICCV'2025. [[paper](https://arxiv.org/abs/2503.13026)] | [[code](https://github.com/yayafengzi/LMM-HiMTok)]
- **`[ReferIS]`** Pixel-SAIL: Single Transformer For Pixel-Grounded Understanding. arXiv'2025. [[paper](https://arxiv.org/abs/2504.10465)] | [[project](https://zhang-tao-whu.github.io/project/pixelsail)]
- **`[RES][ReferIS]`** Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement. arXiv'2025. [[paper](https://arxiv.org/abs/2503.06520)] | [[code](https://github.com/dvlab-research/Seg-Zero)]
- **`[RES][ReferIS]`** Think Before You Segment: High-Quality Reasoning Segmentation with GPT Chain of Thoughts. arXiv'2025. [[paper](https://arxiv.org/abs/2503.07503)] | [[project](https://cse.hkust.edu.hk/~skao/thinkfirst.html)]
- **`[RES][ReferIS]`** POPEN: Preference-Based Optimization and Ensemble for LVLM-Based Reasoning Segmentation. CVPR'2025. [[paper](https://arxiv.org/abs/2504.00640)] | [[project](https://lanyunzhu.site/POPEN/)]
- **`[ReasonIS][ReferIS]`** VisionReasoner: Unified Visual Perception and Reasoning via Reinforcement Learning. arXiv'2025. [[paper](https://arxiv.org/abs/2505.12081)] | [[code](https://github.com/dvlab-research/VisionReasoner)]
- **`[ReferIS]`** Jack of All Tasks, Master of Many: Designing General-purpose Coarse-to-Fine Vision-Language Model. CVPR'2024 [[paper](https://arxiv.org/abs/2312.12423)] | [[project](https://shramanpramanick.github.io/VistaLLM/)]
- **`[ReferIS]`** SegAgent: Exploring Pixel Understanding Capabilities in MLLMs by Imitating Human Annotator Trajectories. CVPR'2025 [[paper](https://arxiv.org/abs/2503.08625)] | [[code](https://github.com/aim-uofa/SegAgent?tab=readme-ov-file)] | [[project](https://aim-uofa.github.io/SegAgent/)]
- **`[ReferIS][ReasonIS]`** Your Large Vision-Language Model Only Needs A Few Attention Heads For Visual Grounding. CVPR'2025 [[paper](https://arxiv.org/abs/2503.06287)]
- **`[ReferIS][ReasonIS]`** SAM-R1: Leveraging SAM for Reward Feedback in Multimodal Segmentation via Reinforcement Learning. arXiv'2025 [[paper](https://arxiv.org/abs/2505.22596)]
- **`[ImgSemSeg][ImgInstSeg][ReferIS]`** ROSE: Revolutionizing Open-Set Dense Segmentation with Patch-Wise Perceptual Large Multimodal Model. arXiv'2025 [[paper](https://arxiv.org/abs/2412.00153)]
- **`[ReferIS][ReasonIS]`** PIXELTHINK: Towards Efficient Chain-of-Pixel Reasoning. arXiv'2025 [[paper](https://arxiv.org/abs/2505.23727)] | [[code](https://github.com/songw-zju/PixelThink)] | [[project](https://pixelthink.github.io/)]
- **`[ReferIS][ImgSemSeg]`** LlamaSeg: Image Segmentation via Autoregressive Mask Generation. arXiv'2025 [[paper](https://arxiv.org/abs/2505.19422)]
- **`[ReferIS][OVSeg]`** ALTo: Adaptive-Length Tokenizer for Autoregressive Mask Generation. arXiv'2025 [[paper](https://arxiv.org/abs/2505.16495)] | [[code](https://github.com/yayafengzi/ALToLLM)]
- **`[ReferVOS][ReasonVOS]`**: VIDEOMOLMO: Spatio-Temporal Grounding Meets Pointing. arXiv'2025 [[paper](https://arxiv.org/abs/2506.05336)] | [[code](https://github.com/mbzuai-oryx/VideoMolmo?tab=readme-ov-file)]
- **`[ReasonIS][ReferIX]`**: RSVP: Reasoning Segmentation via Visual Prompting and Multi-modal Chain-of-Thought. ACL'2025 [[paper](https://www.arxiv.org/abs/2506.04277)]
- **`[ReferVOS][ReasonVOS][ReasonIS][ReferIS]`**: One Token to Seg Them All: Language Instructed Reasoning Segmentation in Videos. NeurIPS'2024 [[paper](https://arxiv.org/abs/2409.19603)] | [[code](https://github.com/showlab/VideoLISA)]
- **`[RES][GCG]`**: GroundingFace: Fine-grained Face Understanding via Pixel Grounding Multimodal Large Language Model. CVPR'2025 [[paper](https://cvpr.thecvf.com/virtual/2025/poster/32585#:~:text=In%20this%20work%2C%20we%20introduce%20the%20textbf%20%7Btextit,dataset%2C%20meticulously%20curated%20for%20alignment%20pretraining%20and%20instruction-tuning.)]
- **`[ReferIS][ReasonIS]`**: Seg-R1: Segmentation Can Be Surprisingly Simple with Reinforcement Learning. arXiv'2025 [[paper](https://www.arxiv.org/abs/2506.22624)][[project](https://geshang777.github.io/seg-r1.github.io/)][[code](https://github.com/geshang777/Seg-R1)]
- **`[ReferIS][ReasonIS][GCG][GRES][ImgSemSeg][ImgInstSeg][ImgInteractSeg][ImgInteractSeg]`**: X-SAM: From Segment Anything to Any Segmentation. arXiv'2025 [[paper](https://arxiv.org/abs/2508.04655)][code](https://github.com/wanghao9610/X-SAM?tab=readme-ov-file)]
- **`[ReferIS][ReasonIS]`**: LENS: Learning to Segment Anything with Unified Reinforced Reasoning. arXiv'2025 [[paper](https://arxiv.org/abs/2508.14153)][[code](https://github.com/hustvl/LENS)]
- **`[ReferIS][ReasonIS][ReferVOS][ReasonVOS][ImgInteractSeg][VideoInteractSeg]`**: UniPixel: Unified Object Referring and Segmentation for Pixel-Level Visual Reasoning. NeurIPS'2025 [[paper](https://arxiv.org/abs/2509.18094)][[code](https://github.com/PolyU-ChenLab/UniPixel)]
- **`[ReferIS][ImgSemSeg][ImgInstSeg][ReasonIS]`**: UFO: A Unified Approach to Fine-grained Visual Perception via Open-ended Language Interface. NeurIPS'2025 [[paper](https://arxiv.org/abs/2503.01342)][[code](https://github.com/nnnth/UFO)]
- **`[ReferIS][ImgSemSeg][ImgInstSeg][OVSeg]`**: Advancing Visual Large Language Model for Multi-granular Versatile Perception. ICCV'2025 [[paper](https://arxiv.org/abs/2507.16213)][[code](https://github.com/xiangwentao666/MVP-LM)]
- **`[ReferVOS][ReferIS]`**: MomentSeg: Moment-Centric Sampling for Enhanced Video Pixel Understanding. arXiv'2025 [[paper](https://arxiv.org/abs/2510.09274)][[code](https://github.com/Dmmm1997/MomentSeg)]
- **`[ReferIS][ImgInteractSeg]`**: ARGenSeg: Image Segmentation with Autoregressive Image Generation Model. NeurIPS'2025 [[paper](http://arxiv.org/pdf/2510.20803v1)]

### Benchmark

- **`[ReasonIS][ReferIS]`** MMR: A Large-scale Benchmark Dataset for Multi-target and Multi-granularity Reasoning Segmentation. ICLR'2025. [[paper](https://arxiv.org/abs/2503.13881)] | [[code](https://github.com/jdg900/MMR)]
- **`[ReasonIS][ReferIS]`** Ground-V: Teaching VLMs to Ground Complex Instructions in Pixels. CVPR'2025. [[paper](https://arxiv.org/abs/2505.13788)]
- **`[ReferIS][GRES]`** GroundingSuite: Measuring Complex Multi-Granular Pixel Grounding. ICCV'2025. [[paper](https://arxiv.org/abs/2503.10596)] | [[code](https://github.com/hustvl/GroundingSuite)]

## Remote sensing

### MLLM with Segmentation Capability

- RSUniVLM: A Unified Vision Language Model for Remote Sensing via Granularity-oriented Mixture of Experts. arXiv'2024. [[paper](https://arxiv.org/abs/2412.05679)] | [[code](https://github.com/xuliu-cyber/RSUniVLM)] | [[project](https://rsunivlm.github.io/)]
- GeoGround: A Unified Large Vision-Language Model. for Remote Sensing Visual Grounding. arXiv'2024. [[paper](http://arxiv.org/abs/2411.11904)] | [[code](https://github.com/zytx121/GeoGround)]
- GeoPix: Multi-Modal Large Language Model for Pixel-level Image Understanding in Remote Sensing. arXiv'2025. [[paper](https://arxiv.org/abs/2501.06828)]
- Falcon: A Remote Sensing Vision-Language Foundation Model. arXiv'2025. [[paper](https://arxiv.org/abs/2503.11070)] | [[code](https://github.com/TianHuiLab/Falcon)]
- EarthMind: Towards Multi-Granular and Multi-Sensor Earth Observation with Large Multimodal Models. arXiv'2025. [[paper](https://arxiv.org/abs/2506.01667)] | [[code](https://github.com/shuyansy/EarthMind)]

### Segmentation Model with LLM/MLLM

- **`[ReferIS][GCG]`** GeoPixel: Pixel Grounding Large Multimodal Model in Remote Sensing. ICML'2025. [[paper](https://arxiv.org/abs/2501.13925)] | [[code](https://github.com/mbzuai-oryx/GeoPixel)] | [[project](https://mbzuai-oryx.github.io/GeoPixel/)]
- **`[ReferIS][ReasonIS]`** SegEarth-R1: Geospatial Pixel Reasoning via Large Language Model. arXiv'2025. [[paper](https://arxiv.org/abs/2504.09644)] | [[code](https://github.com/earth-insights/SegEarth-R1)] | [[project](https://earth-insights.github.io/SegEarth-R1/)]
- **`[ReasonIS]`** LISAt: Language-Instructed Segmentation Assistant for Satellite Imagery. NeurIPS'2025. [[paper](https://arxiv.org/abs/2505.02829)] | [[code](https://github.com/lisat-bair/LISAt_code)] | [[project](https://lisat-bair.github.io/LISAt/)]
- **`[ReferIS][GCG]`** GeoMag: A Vision-Language Model for Pixel-level Fine-Grained Remote Sensing Image Parsing. MM'2025 [[paper](https://arxiv.org/abs/2507.05887)]
- **`[ReferIS][ReasonIS]`** Geo-R1: Improving Few-Shot Geospatial Referring Expression Understanding with Reinforcement Fine-Tuning. arXiv'2025 [[paper](https://arxiv.org/abs/2509.21976)] | [[code](https://github.com/Geo-R1/geo-r1)] | [[project](https://geo-r1.github.io/)]

### Benchmark

- DisasterM3: A Remote Sensing Vision-Language Dataset for Disaster Damage Assessment and Response. NeurIPS'2025. [[paper](https://arxiv.org/abs/2505.21089)]
- GEOBench-VLM: Benchmarking Vision-Language Models for Geospatial Tasks. ICCV'2025 [[paper](https://arxiv.org/abs/2411.19325)] | [[code](https://github.com/The-AI-Alliance/GEO-Bench-VLM)]
  

## Contributing

If you find any errors, or you wish to add some papers, please feel free to contribute to this list by contacting [me](https://likyoo.github.io/) or by creating a [pull request](https://github.com/likyoo/awesome-MLLM-for-image-segmentation/pulls) using the following Markdown format:

```markdown
- Paper Name. Conference'Year. [[paper](link)] | [[code](link)] | ...
```

## Related Links

- [Awesome-MLLM-Segmentation](https://github.com/mc-lan/Awesome-MLLM-Segmentation)
