# 360° Reconstruction From a Single Image Using Space Carved Outpainting <br><sub>Official PyTorch Implementation of the SIGGRAPH ASIA 2023 Paper (Conference Track)</sub>

![Teaser image 1](http://cg.postech.ac.kr/research/POP3D/assets/figures/Teaser_v3ar.png)

**360° Reconstruction From a Single Image Using Space Carved Outpainting**<br>
Nuri Ryu, Minsu Gong, Geonung Kim, Joo-Haeng Lee, Sunghyun Cho<br>

[\[Paper\]](http://cg.postech.ac.kr/papers/2023_SIGAsia_Ryu.pdf)
[\[Supple\]](http://cg.postech.ac.kr/research/POP3D)
[\[Project Page\]](http://cg.postech.ac.kr/research/POP3D/)

Abstract: *We introduce POP3D, a novel framework that creates a full $360^\circ$-view 3D model from a single image. POP3D resolves two prominent issues that limit the single-view reconstruction. Firstly, POP3D offers substantial generalizability to arbitrary categories, a trait that previous methods struggle to achieve. Secondly, POP3D further improves reconstruction fidelity and naturalness, a crucial aspect that concurrent works fall short of. Our approach marries the strengths of four primary components: (1) a monocular depth and normal predictor that serves to predict crucial geometric cues, (2) a space carving method capable of demarcating the potentially unseen portions of the target object, (3) a generative model pre-trained on a large-scale image dataset that can complete unseen regions of the target, and (4) a neural implicit surface reconstruction method tailored in reconstructing objects using RGB images along with monocular geometric cues. The combination of these components enables POP3D to readily generalize across various in-the-wild images and generate state-of-the-art reconstructions, outperforming similar works by a significant margin.*

### Code
We will release the source code soon!

### Citation

```
 @inproceedings{Ryu2023POP3D,
  title     = {$360^\circ$ Reconstruction From a Single Image Using Space Carved Outpainting},
  author    = {Nuri Ryu and Minsu Gong and Geonung Kim and Joo-Haeng Lee and Sunghyun Cho},
  booktitle = {Proc. of ACM SIGGRAPH Asia},
  year      = {2023}}
```
