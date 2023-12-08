---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Relaxed local preserving regression for image feature extraction"
authors: 
- admin
- Zhihui Lai
- Xuechen Li

date: 2021-10-16T15:44:47+08:00
doi: "https://doi.org/10.1007/s11042-020-09802-9"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-16T15:44:47+08:00

# Publication type. 
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"] 


# Publication name and optional abbreviated publication name.
publication: Multimedia Tools and Applications
publication_short: MTA

abstract: 
The latest linear least regression (LSR) methods improved the performance of image feature extraction effectively by relaxing strict zero-one labels as slack forms. However, these methods have the following three disadvantages: 1) LSR-based methods are sensitive to the noises and may lose effectiveness in feature extraction task; 2) they only focus on the global structures of data, but ignore locality which is important to improve the performance; 3) they suffer from the small-class problem, which means the number of projections learned by methods is limited by the number of classes. To address these problems, we propose a novel method called Relaxed Local Preserving Regression (RLPR) for image feature extraction. By incorporating the relaxed label matrix and similarity graph-based regularization term, RLPR can not only explore the latent structure information of data, but also solve the small-class problem. In order to enhance the robustness to noises, we further proposed an extended version of RLPR based on l2, 1-norm, termed as ERLPR. The experimental results on image databases consistently show that the recognition rates of RLPR and ERLPR are superior to the compared methods and can achieve 98% in normal cases. Especially, even on the corrupted databases, the proposed methods can also achieve the classification accuracy of more than 58%.

# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Feature selection", "Label relaxation", "Linear least regression (LSR)", "Manifold learning"]
categories: ["Supervised learning"]
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
