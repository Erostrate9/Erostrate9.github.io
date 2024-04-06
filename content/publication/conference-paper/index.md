---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Linxu Guo
  - Teik-Toe Teoh

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 15th International Conference on Computer Research and Development (ICCRD)*
publication_short: In *ICCRD*

abstract: Pneumonia has been a tough and dangerous human illness for a history-long time, notably since the COVID-19 pandemic outbreak. Many pathogens, including bacteria or viruses like COVID-19, can cause pneumonia, leading to inflammation in patients' alveoli. A corresponding symptom is the appearance of lung opacities, which are vague white clouds in the lungs' darkness in chest radiographs. Modern medicine has indicated that pneumonia-associated opacities are distinguishable and can be seen as fine-grained labels, which make it possible to use deep learning to classify chest radiographs as a supplementary aid for disease diagnosis and performing pre-screening. However, deep learning-based medical imaging solutions, including convolutional neural networks, often encounter a performance bottleneck when encountering a new disease due to the dataset's limited size or class imbalance. This study proposes a deep learning-based approach using transfer learning and weighted loss to overcome this problem. The contributions of it are three-fold. First, we propose an image classification model based on pre-trained Densely Connected Convolutional Networks using Weighted Cross Entropy. Second, we test the effect of masking non-lung regions on the classification performance of chest radiographs. Finally, we summarize a generic practical paradigm for medical image classification based on transfer learning. Using our method, we demonstrate that pre-training on the COVID-19 dataset effectively improves the model's performance on the non-COVID Pneumonia dataset. Overall, the proposed model achieves excellent performance with 95.75% testing accuracy on a multiclass classification for the COVID-19 dataset and 98.29% on a binary classification for the Pneumonia dataset.

# Summary. An optional shortened abstract.
summary: A transfer learning method for Chest Radiograph image classification.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/Erostrate9/TLM-for-COVID-and-Pneumonia-Diagnosis'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/10080197'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'High-level architecture'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
