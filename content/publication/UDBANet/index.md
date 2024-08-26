---
title: 'Uncertainty Driven Bottleneck Attention U-Net for Organ at Risk Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nazib
  - admin
  - Zahid
  - Clinton Fookes

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-05-30T00:00:00Z'
doi: '10.1109/ISBI56570.2024.10635587'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Biomedical Imaging*
publication_short: In *ISBI*

abstract: Organ at risk (OAR) segmentation in computed tomography (CT) imagery is a difficult task for automated segmentation methods and can be crucial for downstream radiation treatment planning. U-net has become a de-facto standard for medical image segmentation and is frequently used as a common baseline in medical image segmentation tasks. In this paper, we propose a multiple decoder U-net architecture and use the segmentation disagreement between the decoders as attention to the bottleneck of the network for segmentation refinement. While feature correlation is considered as attention in most cases, in our case it is the uncertainty from the network used as attention. For accurate segmentation, we also proposed a CT intensity integrated regularization loss. Proposed regularisation helps model understand the intensity distribution of low contrast tissues. We tested our model on two publicly available OAR challenge datasets. We also conducted the ablation on each datasets with the proposed attention module and regularization loss. Experimental results demonstrate a clear accuracy improvement on both datasets.

# Summary. An optional shortened abstract.
summary: The paper introduces a multiple decoder U-net architecture for improved Organ at Risk (OAR) segmentation in CT images, crucial for radiation treatment planning. It uses segmentation disagreement between decoders as an attention mechanism and incorporates a CT intensity integrated regularization loss to handle low contrast tissues. Tested on two public OAR challenge datasets, the proposed methods significantly enhance segmentation accuracy.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://ieeexplore.ieee.org/document/10635587'

url_pdf: 'https://arxiv.org/pdf/2303.10796'
url_code: 'https://github.com/riadhassan/UDBA-UNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - [Uncertainty driven segmentation]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
