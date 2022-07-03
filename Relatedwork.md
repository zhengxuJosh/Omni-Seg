*Panoramicmic images semantic segmentation*
| Year | Pub |  Method  | Task | Details / Motivation |
| :----: | :----: | :----: | :----: | :----: |  
| 2018 | ECCV | [DIstConv](https://openaccess.thecvf.com/content_ECCV_2018/papers/Keisuke_Tateno_Distortion-Aware_Convolutional_Filters_ECCV_2018_paper.pdf) | Sup-Semantic Seg / Depth Estimation | Specifically developed distortion-aware deformable convolution filter|
| 2018 | CVPR | [DenseASPP](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_DenseASPP_for_Semantic_CVPR_2018_paper.pdf) | Sup-Semantic Seg | Densely connected Atrous Spatial Pyramid Pooling for driving scenes |
| 2019 | ICCV | [HexRUNet](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Orientation-Aware_Semantic_Segmentation_on_Icosahedron_Spheres_ICCV_2019_paper.pdf) | Sup-Omni seg | An orientation-aware CNN framework for the icosahedron mesh|
| 2019 | CVPR | [KTN](https://openaccess.thecvf.com/content_CVPR_2019/papers/Su_Kernel_Transformer_Networks_for_Compact_Spherical_Convolution_CVPR_2019_paper.pdf) | Transfer CNN -> omni-image |KTN learns a function that transforms a kernel to account for the distortion in the equirectangular projection of 360◦ images |
| 2019 | CVPR | [SpherePHD](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_SpherePHD_Applying_CNNs_on_a_Spherical_PolyHeDron_Representation_of_360deg_CVPR_2019_paper.pdf) | A new representation for panoramas| Utilize a spherical polyhedron to represent omni-directional views | 
| 2019 | TITS | [RDC](https://arxiv.org/pdf/1801.00708.pdf) | Sup-Omni seg | Propose Restricted Deformable Convolution to handle the large distortions|
| 2019 | Sensors | [ERFNetPSP](https://www.mdpi.com/1424-8220/19/3/503/htm) | Fisheye-Seg | - |
| 2019 | ICLR | [Spherical CNNs](https://arxiv.org/pdf/1901.02039.pdf) | Sup-Omni seg | Perform convolution on unstructured grids using parameterized differential operators as convolution kernels|
| 2019 | IV | [Method](https://www.researchgate.net/profile/Kailun-Yang/publication/335497975_Bridging_the_Day_and_Night_Domain_Gap_for_Semantic_Segmentation/links/5d6b9a42458515088604c67c/Bridging-the-Day-and-Night-Domain-Gap-for-Semantic-Segmentation.pdf) | DA-Seg(Day-Night)| GAN |
| 2020 | TITS | [PASS](https://ieeexplore.ieee.org/document/8835049) | Sup-Omni seg | Fuse the feature maps of differnent segments to fulfill panoramas | | | 2020 | TITS | [Omnisupervised](https://www.researchgate.net/profile/Kailun-Yang/publication/345419595_Omnisupervised_Omnidirectional_Semantic_Segmentation/links/609daf06458515c2658cb643/Omnisupervised-Omnidirectional-Semantic-Segmentation.pdf)| **UDA-Omni seg** | An omnisupervised learning framework for efficient CNN | 
| 2020 | CVPR |[Tangent](https://openaccess.thecvf.com/content_CVPR_2020/papers/Eder_Tangent_Images_for_Mitigating_Spherical_Distortion_CVPR_2020_paper.pdf) | A spherical image representation | render a spherical image to a set of distortion-mitigated, locally-planar image grids tangent to a subdivided icosahedron |
| 2021 | IV | [PRF](https://arxiv.org/pdf/2103.00868.pdf) | **UDA-Omni seg** & Contrastive | Unsupervised visual representation learning / contrastive learning |
| 2021 | ITSC | [P2PDA](https://arxiv.org/pdf/2108.06383.pdf) | **UDA-Omni seg** | Investigate different DA modules both in a separate and joint manner |
| 2021 | TIP | [Omni-supervised](http://www.yangkailun.com/publications/tip2021_kailun.pdf)| **UDA-Omni seg** | -|
| 2021 | ICCV | [PIT](https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_PIT_Position-Invariant_Transform_for_Cross-FoV_Domain_Adaptation_ICCV_2021_paper.pdf) | Image transform | -|
| 2021 | CVPR | [ECANet](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Capturing_Omni-Range_Context_for_Omnidirectional_Segmentation_CVPR_2021_paper.pdf) | **UDA-Omni seg** | Capture inherent omni-range dependencies that stretch across 360◦|
| 2021 | CVPR | [HoHoNet](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_HoHoNet_360_Indoor_Holistic_Understanding_With_Latent_Horizontal_Features_CVPR_2021_paper.pdf)| Dense prediction tasks | Learning compact latent horizontal features for dense modalities modeling of omnidirectional images | 
| 2021 | TPAMI | [Syherical](https://ieeexplore.ieee.org/abstract/document/9497715) | survey | - |
| 2021 | TITS | [P2PDA](https://arxiv.org/pdf/2110.11062.pdf) | **UDA-Omni seg** | DA in output-, feature-, feature confidence spaces|
| 2022 | CVPR | [Trans4PASS](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Bending_Reality_Distortion-Aware_Transformers_for_Adapting_to_Panoramic_Semantic_Segmentation_CVPR_2022_paper.pdf) | **UDA-Omni seg** | The Deformable Patch Embedding (DPE) and the Deformable MLP (DMLP) module endow Trans4PASS with distortion awareness|

**UDA-Omni seg**
| Year | Pub |  Method  | Network Structure | Data Form / Augment | UDA method |
| :----: | :----: | :----: | :----: | :----: | :----: | 
| 2020 | TITS | [Omnisupervised](https://www.researchgate.net/profile/Kailun-Yang/publication/345419595_Omnisupervised_Omnidirectional_Semantic_Segmentation/links/609daf06458515c2658cb643/Omnisupervised-Omnidirectional-Semantic-Segmentation.pdf)| Teacher-Student Model | Unlabeled ERP & Labeled 2D / Panorama Segments | Pseudo labels |
| 2021 | IV | [PRF](https://arxiv.org/pdf/2103.00868.pdf) | Pretrained of backbone & Supervised with two heads(classifiers)| ERP | Pretrained |
| 2021 | ITSC | [P2PDA](https://arxiv.org/pdf/2108.06383.pdf) | Dual backbones & designed attention module | ERP & 2D images individually | feature & logits |
| 2021 | CVPR | [ECANet](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Capturing_Omni-Range_Context_for_Omnidirectional_Segmentation_CVPR_2021_paper.pdf) | Model ensemble | Unlabeled ERP & Labeled 2D / Panorama Segments | Pseudo labels |
| 2022 | CVPR | [Trans4PASS](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Bending_Reality_Distortion-Aware_Transformers_for_Adapting_to_Panoramic_Semantic_Segmentation_CVPR_2022_paper.pdf) | Trans4PASS & Mutual Prototype Memory | ERP & 2D images | Mutual Prototype Memory | 

**UDA**
| Year | Pub |  Method  | Task | Details / Motivation |
| :----: | :----: | :----: | :----: | :----: | 
| 2022 | CVPR | [CCDistill](https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_Cross-Domain_Correlation_Distillation_for_Unsupervised_Domain_Adaptation_in_Nighttime_Semantic_CVPR_2022_paper.pdf) | UDA-Nighttime Semantic Seg | Cope with the inherent difference between datasets caused by the camera equipment and the urban style | 
| 2017 | TPAMI | [Optimal Transport for Domain Adaptation](https://arxiv.org/pdf/1507.00504.pdf) | Survey | - |
| 2020 | CVPR | [RWOT](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)| UDA-Cls| Existing optimal transport in DA don't consider intra-domain structure of both domains |
| 2020 | CVPR | [ETD](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf) | UDA-Cls | The transport distance cannot relect the discriminant information from either domain knowledge or category prior |
