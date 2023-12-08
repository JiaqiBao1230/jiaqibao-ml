---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Redirected Transfer Learning for Robust Multi-Layer Subspace Learning"
authors: 
- admin
- Mineichi Kudo
- Keigo Kimura
- Lu Sun

date: 2021-10-16T15:44:47+08:00
# doi: "https://doi.org/10.1007/s11042-020-09802-9"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-012-16T15:44:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Pattern Analysis and Applications
publication_short: PAA

abstract: Unsupervised transfer learning methods usually exploit the labeled source data to learn a classifier for unlabeled target data with a different but related distribution. However, most of the existing transfer learning methods leverage 0-1 matrix as labels which greatly narrows the flexibility of transfer learning. Another major limitation is that these methods are influenced by the redundant features and noises residing in cross-domain data. To cope with these two issues simultaneously, this paper proposes a Redirected Transfer Learning (RTL) approach for unsupervised transfer learning with a multi-layer subspace learning structure. Specifically, in the first layer, we first learn a robust subspace where data from different domains can be well interlaced. This is made by reconstructing each target sample with the lowest-rank representation of source samples. Besides, imposing the $L_{2,1}$-norm sparsity on the regression term and regularization term brings robustness against noise and works for selecting informative features, respectively. In the second layer, we further introduce a redirected label strategy in which the strict binary labels are relaxed into continuous values for each datum. To handle effectively unknown labels of the target domain, we construct the pseudo-labels iteratively for unlabeled target samples to improve the discriminative ability in classification. The superiority of our method in classification tasks is confirmed on several cross-domain datasets.

# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Transfer learning",  "Regression", "Robustness", " Sparsity", "Discriminative."]
categories: ["Transfer learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/article/10.1007/s11042-020-09802-9#citeas"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: [flsys]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

