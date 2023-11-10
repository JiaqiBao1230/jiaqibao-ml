---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Retargeted Regression Methods for Multi-label Learning"
authors: 
- Keigo Kimura 
- admin
- Mineichi Kudo
- Lu Sun

date: 2022
doi: "https://doi.org/10.1007/978-3-031-23028-8_21"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-16T15:44:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference paper"]

# Publication name and optional abbreviated publication name.
publication:  Structural, Syntactic, and Statistical Pattern Recognition
publication_short: S+SSPR 2022

abstract: In Multi-Label Classification, utilizing label relationship is a key to improve classification accuracy. Label Space Dimension Reduction or Classifier Chains utilizes the relationship explicitly however those utilization are still limited. In this paper, we propose Retargeted Regression methods for Multi-Label classification by extending Retargeted Linear Least Squares originally proposed for Multi-Class Classification. Retargeted methods not only learn classifiers but also modify targets with margin constraints. Since in Multi-Label Classification, an instance may have more than one label, large margin constraints between all pairs of positive labels and negative labels are introduced. This enables to utilize the label relationship with taking ranking of labels for each instance into consideration. We also propose a simple heuristic to determine a threshold parameter for each instance to earn zero-one classification. On nine benchmark datasets, the proposed method outperformed conventional methods in the sense of instance-wise ranking. In best cases, classification accuracy was improved at on AUC metric.


# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Multi-label learning", "Linear Least Squares"]
categories: ["Multi-label learning"]
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
