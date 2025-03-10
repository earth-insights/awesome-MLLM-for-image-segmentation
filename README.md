[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/likyoo/awesome-MLLM-for-image-segmentation/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/likyoo/awesome-MLLM-for-image-segmentation)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/likyoo/awesome-MLLM-for-image-segmentation?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/likyoo/awesome-MLLM-for-image-segmentation?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/likyoo/awesome-MLLM-for-image-segmentation?style=social">

# <p align=center>`Awesome LLM/MLLM for Image Segmentation`</p>

## Related Task

**`[ReferIS]`**: Referring Image Segmentation  
**`[GRES]`**: Generalized Referring Expression Segmentation  
**`[ReasonIS]`**: Reasoning Image Segmentation  
**`[ReasonInstIS]`**: Referring Instance Image Segmentation  
**`[SiD]`**: Segmentation in Dialogue  
**`[GCG]`**: Grounded Conversation Generation  
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

## General

### MLLM with Segmentation Capability

- VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks. arXiv'2023. [[paper](https://arxiv.org/abs/2305.11175)] | [[code](https://github.com/OpenGVLab/VisionLLM)]
- VisionLLM v2: An End-to-End Generalist Multimodal Large Language Model for Hundreds of Vision-Language Tasks. arXiv'2024. [[paper](https://arxiv.org/abs/2406.08394)] | [[code](https://github.com/OpenGVLab/VisionLLM)]
- Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Xiao_Florence-2_Advancing_a_Unified_Representation_for_a_Variety_of_Vision_CVPR_2024_paper.html)] | [[code](https://huggingface.co/collections/microsoft/florence-6669f44df0d87d9c3bfb76de)]
- NExT-Chat: An LMM for Chat, Detection and Segmentation. ICML'2024. [[paper](https://arxiv.org/abs/2311.04498)] | [[code](https://github.com/NExT-ChatV/NExT-Chat)] | [[project](https://next-chatv.github.io/)]
- PaliGemma: A versatile 3B VLM for transfer. arXiv'2024. [[paper](https://arxiv.org/abs/2407.07726)] | [[code](https://github.com/google-research/big_vision)]
- PaliGemma 2: A Family of Versatile VLMs for Transfer. arXiv'2024. [[paper](https://arxiv.org/abs/2412.03555)] | [[code](https://github.com/google-research/big_vision)]

### Segmentation Model with LLM/MLLM

- **`[ReferIS][ReasonIS]`** LISA: Reasoning Segmentation via Large Language Model. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Lai_LISA_Reasoning_Segmentation_via_Large_Language_Model_CVPR_2024_paper.html)] | [[code](https://github.com/dvlab-research/LISA)]
- **`[ReferIS][ReasonIS][ReasonInstIS][SiD]`** LISA++: An Improved Baseline for Reasoning Segmentation with Large Language Model. arXiv'2023. [[paper](https://openreview.net/forum?id=NBQFAN228B)] | [[code](https://github.com/dvlab-research/LISA)]
- **`[ReferIS][GRES]`** GSVA: Generalized Segmentation via Multimodal Large Language Models. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Xia_GSVA_Generalized_Segmentation_via_Multimodal_Large_Language_Models_CVPR_2024_paper.html)] | [[code](https://github.com/LeapLabTHU/GSVA)]
- **`[ReferIS][ReasonIS]`** PixelLM: Pixel Reasoning with Large Multimodal Model. CVPR'2024. [[paper](https://arxiv.org/abs/2312.02228)] | [[code](https://github.com/MaverickRen/PixelLM)] | [[project](https://pixellm.github.io/)]
- **`[ReferIS][GCG]`** GLaMM: Pixel Grounding Large Multimodal Model. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Rasheed_GLaMM_Pixel_Grounding_Large_Multimodal_Model_CVPR_2024_paper.html)] | [[code](https://github.com/mbzuai-oryx/groundingLMM)] | [[project](https://mbzuai-oryx.github.io/groundingLMM/)]
- **`[ReferIS][GRES][ReasonIS]`** GROUNDHOG: Grounding Large Language Models to Holistic Segmentation. CVPR'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_GROUNDHOG_Grounding_Large_Language_Models_to_Holistic_Segmentation_CVPR_2024_paper.html)] | [[project](https://groundhog-mllm.github.io/)]
- **`[ReasonIS]`** LLM-Seg: Bridging Image Segmentation and Large Language Model Reasoning. CVPRW'2024. [[paper](https://openaccess.thecvf.com/content/CVPR2024W/MMFM/html/Wang_LLM-Seg_Bridging_Image_Segmentation_and_Large_Language_Model_Reasoning_CVPRW_2024_paper.html)] | [[code](https://github.com/wangjunchi/LLMSeg)]
- **`[ReferIS][ReasonIS][GCG][ImgSemSeg][ImgInstSeg][ImgInteractSeg][ImgInteractSeg]`** OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding. NeurIPS'2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/83eb86be3e2f9fd66c44d9073c51ba4d-Abstract-Conference.html)] | [[code](https://github.com/lxtGH/OMG-Seg)] | [[project](https://lxtgh.github.io/project/omg_llava/)]
- **`[ReferIS][GRES][ReasonIS][GCG][ImgSemSeg][ImgInstSeg][ImgInteractSeg][ImgInteractSeg][VideoObjSeg][OVSeg]`** PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model. ECCV'2024. [[paper](https://arxiv.org/abs/2403.14598)] | [[code](https://github.com/zamling/PSALM)]
- **`[ReferIS][ReasonIS][ReasonVOS]`** VISA: Reasoning Video Object Segmentation via Large Language Models. ECCV'2024. [[paper](https://arxiv.org/abs/2407.11325)] | [[code](https://github.com/cilinyan/VISA)]
- **`[ImgSemSeg][ReferIS][GRES]`** LaSagnA: Language-based Segmentation Assistant for Complex Queries. arXiv'2024. [[paper](https://arxiv.org/abs/2404.08506)] | [[code](https://github.com/congvvc/LaSagnA)]
- **`[ReferIS]`** EVF-SAM: Early Vision-Language Fusion for Text-Prompted Segment Anything Model. arXiv'2024. [[paper](https://arxiv.org/abs/2406.20076)] | [[code](https://github.com/hustvl/EVF-SAM)]
- **`[ReferIS][GRES][ReasonIS][GCG][MGSC]`** Instruction-guided Multi-Granularity Segmentation and Captioning with Large Multimodal Model. arXiv'2024. [[paper](https://arxiv.org/abs/2409.13407)] | [[code](https://github.com/lizhou-cs/mglmm)] | [[project](https://lizhou-cs.github.io/mglmm.github.io/)]
- **`[ReferIS][GRES]`** Text4Seg: Reimagining Image Segmentation as Text Generation. ICLR'2025. [[paper](https://arxiv.org/abs/2410.09855)] | [[code](https://github.com/mc-lan/Text4Seg)] | [[project](https://mc-lan.github.io/Text4Seg/)]
- **`[ReferIS][ReasonIS][ReferVOS][ReasonVOS]`** InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models. arXiv'2024. [[paper](https://arxiv.org/abs/2412.14006)] | [[code](https://github.com/congvvc/InstructSeg)]
- **`[ReferIS][GCG][ReferVOS][VideoInteractSeg]`** Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos. arXiv'2025. [[paper](https://arxiv.org/abs/2501.04001)] | [[code](https://github.com/magic-research/Sa2VA)] | [[project](https://lxtgh.github.io/project/sa2va/)]

## Remote sensing

### MLLM with Segmentation Capability

- RSUniVLM: A Unified Vision Language Model for Remote Sensing via Granularity-oriented Mixture of Experts. arXiv'2024. [[paper](https://arxiv.org/abs/2412.05679)] | [[code](https://github.com/xuliu-cyber/RSUniVLM)] | [[project](https://rsunivlm.github.io/)]
- GeoGround: A Unified Large Vision-Language Model. for Remote Sensing Visual Grounding. arXiv'2024. [[paper](http://arxiv.org/abs/2411.11904)] | [[code](https://github.com/zytx121/GeoGround)]
- GeoPix: Multi-Modal Large Language Model for Pixel-level Image Understanding in Remote Sensing. arXiv'2025. [[paper](https://arxiv.org/abs/2501.06828)]

### Segmentation Model with LLM/MLLM

- **`[ReferIS][GCG]`** GeoPixel: Pixel Grounding Large Multimodal Model in Remote Sensing. arXiv'2025. [[paper](https://arxiv.org/abs/2501.13925)] | [[code](https://github.com/mbzuai-oryx/GeoPixel)] | [[project](https://mbzuai-oryx.github.io/GeoPixel/)]


## Contributing

If you find any errors, or you wish to add some papers, please feel free to contribute to this list by contacting [me](https://likyoo.github.io/) or by creating a [pull request](https://github.com/likyoo/awesome-MLLM-for-image-segmentation/pulls) using the following Markdown format:

```markdown
- Paper Name. Conference'Year. [[paper](link)] | [[code](link)] | ...
```

## Related Links

- [Awesome-MLLM-Segmentation](https://github.com/mc-lan/Awesome-MLLM-Segmentation)
