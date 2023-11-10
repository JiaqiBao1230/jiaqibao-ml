---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Embedding Regression for Face Recognition"
authors: 
- admin
- Jianglin Lu
- Zhihui Lai
- Ning Liu
- Yuwu Lu

date: 2019-10-16T15:44:47+08:00
doi: "https://doi.org/10.1007/978-3-030-31723-2_9"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-16T15:44:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference paper"]

# Publication name and optional abbreviated publication name.
publication: Chinese Conference on Pattern Recognition and Computer Vision
publication_short: PRCV2019

abstract:  Classical subspace learning methods such as spectral regression (SR) and its sparse extensions are all two-step ways, which will lead to a suboptimal subspace for feature extraction. Another potential drawback is that these methods are not robust to the outliers and the variations of data because they use Frobenius norm as the basic distance metric. To address these problems, a novel face recognition method called robust embedding regression (RER) is proposed, which performs low-dimensional embedding and jointly sparse regression simultaneously. By this way, the optimal subspace can be obtained. Besides, we not only emphasize L2,1-norm minimization on both loss function and regularization terms, but also use L2,1-norm as the basic distance metric. Therefore, we can obtain jointly sparse projections in the regression process and more stable and robust low-dimensional reconstruction in the embedding process. Moreover, we use a more generalized constraint to improve the generalization of RER. The corresponding optimal solution can be computed by generalized eigen-decomposition via an iterative optimization algorithm. Theoretical analysis and experimental results prove the convergence of RER. Extensive experiments show the proposed RER has a better performance than other related methods on four well-known datasets.
# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Robust low-dimensional embedding", "Jointly sparse projection", "Subspace learning", "Face recognition"]
categories: ["Unsupervised learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/chapter/10.1007/978-3-030-31723-2_9#citeas"
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
