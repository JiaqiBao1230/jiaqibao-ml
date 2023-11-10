---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Discriminative low-rank projection for robust subspace learning"
authors: 
- Zhihui Lai
- admin
- Heng Kong
- Minghua Wan
- Guowei Yang

date: 2020
doi: "https://doi.org/10.1007/s13042-020-01113-"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-16T15:44:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication:  International Journal of Machine Learning and Cybernetics
publication_short: IJMLC

abstract: The robustness to outliers, noises, and corruptions has been paid more attention recently to increase the performance in linear feature extraction and image classification. As one of the most effective subspace learning methods, low-rank representation (LRR) can improve the robustness of an algorithm by exploring the global representative structure information among the samples. However, the traditional LRR cannot project the training samples into low-dimensional subspace with supervised information. Thus, in this paper, we integrate the properties of LRR with supervised dimensionality reduction techniques to obtain optimal low-rank subspace and discriminative projection at the same time. To achieve this goal, we proposed a novel model named Discriminative Low-Rank Projection (DLRP). Furthermore, DLRP can break the limitation of the small class problem which means the number of projections is bound by the number of classes. Our model can be solved by alternatively linearized alternating direction method with adaptive penalty and the singular value decomposition. Besides, the analyses of differences between DLRP and previous related models are shown. Extensive experiments conducted on various contaminated databases have confirmed the superiority of the proposed method.
# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Feature selection", "Low-rank representation", "Image classification", "Subspace learning"]
categories: ["Superivised Learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/article/10.1007/s13042-020-01113-7#citeas"
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
  focal_point: ""
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
