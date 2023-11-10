---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust embedding regression for semi-supervised learning"
authors: 
- admin
- Mineichi Kudo
- Keigo Kimura
- Lu Sun

date: 2024-01-18T15:44:47+08:00
doi: "https://doi.org/10.1016/j.patcog.2023.109894"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-16T15:44:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: Pattern Recognition
publication_short: PR

abstract: To utilize both labeled data and unlabeled data in real-world applications, semi-supervised learning is widely used as an effective technique. However, most semi-supervised methods do not perform well when there are many noises and redundant information in the original data. To address these issues, in this paper, we proposed a novel approach called robust embedding regression (RER) for semi-supervised learning by inheriting the advantages of the existing semi-supervised learning, robust linear regression, and low-rank representation techniques. Specifically, RER constructs a more robust and accurate graph by adaptively arranging the weight coefficient for each data point. Furthermore, the low-rank representation is introduced to reduce the negative influence of the redundant features and noises residing in the original data while the graph construction. More importantly, the proper norms are imposed on both the reconstruction and regularization terms to further improve the robustness and earn feature/sample selection. We designed an effective iterative algorithm to optimize the problem of RER. Comprehensive experimental results conducted on both synthetic and real-world datasets indicate that RER is superior in classification and clustering performance and robust to different types of noise compared with the existing semi-supervised methods.

# Summary. An optional shortened abstract.
# summary: "We propose the first low-code FL platform, EasyFL, to enable users with various levels of expertise to experiment and prototype FL applications with little coding. We achieve this goal while ensuring great flexibility and extensibility for customization by unifying simple API design, modular design, and granular training flow abstraction. Besides, EasyFL expedites distributed training by 1.5x."

tags: ["Feature selection", "Semi-supervised learning", "Ridge regression", "Nuclear norm"]
categories: ["Semi-supervised learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.sciencedirect.com/science/article/pii/S0031320323005927"
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
