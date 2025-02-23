---
title: 'Automated Radiomics Based Clinically Significant Prostate Cancer (csPCa) Grade Classification From Biparametric MRI'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rakib
  - Nazib
  - admin
  - Abu Rumman Refat 
  - Kien Nguyen
  - Zahid
  - Clinton Fookes

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '13 February 2025'
doi: '10.1109/DICTA63115.2024.00073'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-2-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 International Conference on Digital Image Computing Techniques and Applications*
publication_short: In *DICTA*

abstract: Prostate cancer (PCa) is one of the most common cancers in males, and clinically significant PCa (csPCa) is one of the leading causes of death worldwide. Multi-parametric MRI (mp-MRI) has gained widespread acceptance as the primary diagnostic method for prostate cancer diagnosis. However, there are still difficulties with the widespread utilization of contrast agents based on gadolinium that brings on nephrogenic systemic fibrosis, increased complexity of interpretation, and lower productivity. To overcome the drawbacks of mp-MRI, Bi-parametric MRI (bp-MRI) is an emerging solution. Here, we propose a fully automated csPCa grade classification framework that utilizes bp-MRI for segmenting csPCa lesions and uses radiomics features. We use 124 different radiomics features from 8 feature categories and select statistically significant features to train three machine learning classifiers namely SVM, KNN, Bayesian, XGBoost and Random forest. Our framework with XGBoost classifier achieved a classification accuracy of 96% in distinguishing clinically significant PCa (ISUP 4+5) and non-significant PCa (ISUP 2+3) using the predicted maps drawn by our segmentation method.

# Summary. An optional shortened abstract.
summary: This study presents a fully automated csPCa grade classification framework using bp-MRI for lesion segmentation and radiomics feature extraction. A total of 124 radiomics features were analyzed, with statistically significant features selected to train five machine learning classifiers (SVM, KNN, Bayesian, XGBoost, and Random Forest). The XGBoost classifier achieved the highest accuracy of 96% in distinguishing significant (ISUP 4+5) from non-significant (ISUP 2+3) PCa based on segmentation-predicted maps.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://ieeexplore.ieee.org/document/10869575'

url_pdf: ''
url_code: ''
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
  - [Radiomics Driven PCa grade classification]

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
