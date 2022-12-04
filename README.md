# MAiVAR: Multimodal Audio-Image and Video Action Recognizer
### [Project Page](https://zju3dv.github.io/loftr) | [Paper](https://arxiv.org/pdf/2209.04780.pdf) 
<br/>

> MAiVAR: Multimodal Audio-Image and Video Action Recognizer.   
> [Muhammad Bilal Shaikh](https://mbs.onrender.com/)<sup>\*</sup>, [Douglas Chai](https://www.ecu.edu.au/schools/engineering/staff/profiles/associate-deans/dr-douglas-chai))<sup>\*</sup>, [Syed Mohammed Shamsul Islam](https://www.ecu.edu.au/schools/science/staff/profiles/senior-lecturers/sislam)<sup>\*</sup>, [Naveed Akhtar](https://research-repository.uwa.edu.au/en/persons/naveed-akhtar).   
> VCIP 2022

![demo_vid](assets/loftr-github-demo.gif)

## TODO List and ETA
- [x] Inference code and pretrained models (DS and OT) (2021-4-7)
- [x] Code for reproducing the test-set results (2021-4-7)
- [x] Webcam demo to reproduce the result shown in the GIF above (2021-4-13)
- [x] Training code and training data preparation (expected 2021-6-10)

Discussions about the paper are welcomed in the [discussion panel](https://github.com/zju3dv/LoFTR/discussions).

:thinking: **FAQ**

1. Undistorted images from D2Net are not available anymore.  
   For a temporal alternative, please use the undistorted images provided by the MegaDepth_v1 (should be downloaded along with the required depth files). We numerically compared these images and only found very subtle difference.

:triangular_flag_on_post: **Updates**
- Check out [QuadTreeAttention](https://github.com/Tangshitao/QuadTreeAttention), a new attention machanism that improves the efficiency and performance of LoFTR with less demanding GPU requirements for training.
- :white_check_mark: Integrated to [Huggingface Spaces](https://huggingface.co/spaces) with [Gradio](https://github.com/gradio-app/gradio). See [Gradio Web Demo](https://huggingface.co/spaces/akhaliq/Kornia-LoFTR)


## Citation

If you find this code useful for your research, please use the following BibTeX entry.


```bibtex
@article{sun2021loftr,
  title={{MAiVAR}: Multimodal Audio-Image and Video Action Recognizer},
  author={Shaikh, Muhammad Bilal and Chai, Douglas and Islam, Syed Mohammed Shamsul and Akhtar, Naveed},
  journal={{VCIP}},
  year={2022}
}
```

## Copyright
This work is affiliated with Centre for Artificial Intelligence and Machine Learning (CAIML)  of Edith Cowan Univetsity, and its intellectual property belongs to Edith Cowan University.

```
Copyright SenseTime. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


