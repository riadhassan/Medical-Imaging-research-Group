---
title: "Enhancing Semantic Segmentation with Adaptive Focal Loss: A Novel Approach"
authors:
- Rakib
- admin
- Nazib
-  Kien Nguyen
- Clinton Fookes
- Zahid
date: "2024-07-13"
# doi: "10.48550/arXiv.2407.09828"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-13"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Deep learning has achieved outstanding accuracy in medical image segmentation, particularly for objects like organs or tumors with smooth boundaries or large sizes. Whereas, it encounters significant difficulties with objects that have zigzag boundaries or are small in size, leading to a notable decrease in segmentation effectiveness. In this context, using a loss function that incorporates smoothness and volume information into a model's predictions offers a promising solution to these shortcomings. In this work, we introduce an Adaptive Focal Loss (A-FL) function designed to mitigate class imbalance by down-weighting the loss for easy examples that results in up-weighting the loss for hard examples and giving greater emphasis to challenging examples, such as small and irregularly shaped objects. The proposed A-FL involves dynamically adjusting a focusing parameter based on an object's surface smoothness, size information, and adjusting the class balancing parameter based on the ratio of targeted area to total area in an image. We evaluated the performance of the A-FL using ResNet50-encoded U-Net architecture on the Picai 2022 and BraTS 2018 datasets. On the Picai 2022 dataset, the A-FL achieved an Intersection over Union (IoU) of 0.696 and a Dice Similarity Coefficient (DSC) of 0.769, outperforming the regular Focal Loss (FL) by 5.5% and 5.4% respectively. It also surpassed the best baseline Dice-Focal by 2.0% and 1.2%. On the BraTS 2018 dataset, A-FL achieved an IoU of 0.883 and a DSC of 0.931. The comparative studies show that the proposed A-FL function surpasses conventional methods, including Dice Loss, Focal Loss, and their hybrid variants, in IoU, DSC, Sensitivity, and Specificity metrics. This work highlights A-FL's potential to improve deep learning models for segmenting clinically significant regions in medical images, leading to more precise and reliable diagnostic tools.

# Summary. An optional shortened abstract.
summary: The Adaptive Focal Loss (A-FL) function enhances medical image segmentation by addressing class imbalance and improving accuracy for small or irregularly shaped objects. Incorporating smoothness and volume information, A-FL dynamically adjusts parameters based on object characteristics. Tested on the Picai 2022 and BraTS 2018 datasets with a ResNet50-encoded U-Net architecture, A-FL achieved significant improvements in Intersection over Union (IoU) and Dice Similarity Coefficient (DSC), outperforming standard Focal Loss and other methods. This approach offers a promising enhancement for deep learning models in medical diagnostics.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: https://arxiv.org/abs/2407.09828
url_pdf: https://arxiv.org/pdf/2407.09828
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
