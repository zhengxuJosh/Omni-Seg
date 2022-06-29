*Panoramicmic images semantic segmentation*
| Year | Pub |  Method  | Task | Details / Motivation |
| :----: | :----: | :----: | :----: | :----: | 
| 2022 | CVPR | [CCDistill](https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_Cross-Domain_Correlation_Distillation_for_Unsupervised_Domain_Adaptation_in_Nighttime_Semantic_CVPR_2022_paper.pdf) | UDA-Nighttime Semantic Seg | Cope with the inherent difference between datasets caused by the camera equipment and the urban style | 
| 2018 | ECCV | [DIstConv](https://openaccess.thecvf.com/content_ECCV_2018/papers/Keisuke_Tateno_Distortion-Aware_Convolutional_Filters_ECCV_2018_paper.pdf) | Sup-Semantic Seg / Depth Estimation | Specifically developed distortion-aware deformable convolution filter|
| 2018 | CVPR | [DenseASPP](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_DenseASPP_for_Semantic_CVPR_2018_paper.pdf) | Sup-Semantic Seg | Densely connected Atrous Spatial Pyramid Pooling for driving scenes |
| 2019 | ICCV | [HexRUNet](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Orientation-Aware_Semantic_Segmentation_on_Icosahedron_Spheres_ICCV_2019_paper.pdf) | Sup-Omni seg | An orientation-aware CNN framework for the icosahedron mesh|
| 2019 | CVPR | [KTN](https://openaccess.thecvf.com/content_CVPR_2019/papers/Su_Kernel_Transformer_Networks_for_Compact_Spherical_Convolution_CVPR_2019_paper.pdf) | Transfer CNN -> omni-image |KTN learns a function that transforms a kernel to account for the distortion in the equirectangular projection of 360◦ images |
| 2019 | CVPR | [SpherePHD](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_SpherePHD_Applying_CNNs_on_a_Spherical_PolyHeDron_Representation_of_360deg_CVPR_2019_paper.pdf) | A new representation for panoramas| Utilize a spherical polyhedron to represent omni-directional views | 
| 2019 | TITS | [RDC](https://arxiv.org/pdf/1801.00708.pdf) | Sup-Omni seg | Propose Restricted Deformable Convolution to handle the large distortions|
| 2019 | Sensors | [ERFNetPSP](https://www.mdpi.com/1424-8220/19/3/503/htm) | Fisheye-Seg | |
| 2019 | ICLR | [Spherical CNNs](https://arxiv.org/pdf/1901.02039.pdf) | Sup-Omni seg | Perform convolution on unstructured grids using parameterized differential operators as convolution kernels|
| 2019 | IV | [Method](https://www.researchgate.net/profile/Kailun-Yang/publication/335497975_Bridging_the_Day_and_Night_Domain_Gap_for_Semantic_Segmentation/links/5d6b9a42458515088604c67c/Bridging-the-Day-and-Night-Domain-Gap-for-Semantic-Segmentation.pdf) | DA-Seg(Day-Night)| GAN |
| 2020 | TITS | [PASS](https://ieeexplore.ieee.org/document/8835049) | Sup-Omni seg | Fuse the feature maps of differnent segments to fulfill panoramas | | | 2020 | TITS | [Omnisupervised](https://www.researchgate.net/profile/Kailun-Yang/publication/345419595_Omnisupervised_Omnidirectional_Semantic_Segmentation/links/609daf06458515c2658cb643/Omnisupervised-Omnidirectional-Semantic-Segmentation.pdf)| **UDA-Omni seg** | An omnisupervised learning framework for efficient CNN | 
| 2020 | CVPR | 
[Tangent](https://openaccess.thecvf.com/content_CVPR_2020/papers/Eder_Tangent_Images_for_Mitigating_Spherical_Distortion_CVPR_2020_paper.pdf) | a spherical
image representation | render a spherical image to a set of distortion-mitigated, locally-planar image grids tangent to a subdivided icosahedron |
