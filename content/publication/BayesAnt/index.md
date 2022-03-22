---
title: "Inferring taxonomic placement from DNA barcoding allowing discovery of new taxa"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tommaso Rigon
- David B. Dunson

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

#date: "2013-07-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: Predicting the taxonomic affiliation of DNA sequences collected from biological samples is a fundamental step in biodiversity assessment. This task is performed by leveraging on existing databases containing reference DNA sequences whose taxa are known. However, environmental sequences can be from organisms that are either unknown to science or for which there are no reference sequences available. Thus, taxonomic novelty of a sequence needs to be accounted for when doing classification. We propose Bayesian nonparametric taxonomic classifiers, BayesANT, which use species sampling model priors to allow new taxa to be discovered at each taxonomic rank.  Using a simple product multinomial likelihood with conjugate Dirichlet priors at the lowest rank, a highly efficient algorithm is developed to provide a probabilistic prediction of the taxa placement of each sequence at each rank. BayesANT is shown to have excellent performance when many sequences in the test set belong to unobserved taxa.
# Summary. An optional shortened abstract.
summary: We develop BayesANT (Bayesian Nonparametric Taxonomic Classifier), an algorithm that predicts the taxonomic annotations (e.g. *Phylum*, *Class*, *Order*..) of insect DNA sequence while accounting for potential species novelty. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2201.09782.pdf
url_code: https://alessandrozito.github.io/BayesANT/vignette.html
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#	caption: "" 'Pitman-Yor urn scheme for insect DNA sequences'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

