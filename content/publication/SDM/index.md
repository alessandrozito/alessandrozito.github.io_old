---
title: "Bayesian modelling of sequential discoveries"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tommaso Rigon
- Otso Ovaskainen
- David B. Dunson

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

#date: "2013-07-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*
abstract: We aim at modelling the appearance of distinct tags in a sequence of labelled objects. Common examples of this type of data include words in a corpus or distinct species in a sample. These sequential discoveries are often summarised via accumulation curves, which count the number of distinct entities observed in an increasingly large set of objects. We propose a novel Bayesian method for species sampling modelling by directly specifying the probability of a new discovery, therefore allowing for flexible specifications. The asymptotic behavior and finite sample properties of such an approach are extensively studied. Interestingly, our enlarged class of sequential processes includes highly tractable special cases. We present a subclass of models characterized by appealing theoretical and computational properties, including one that shares the same discovery probability with the Dirichlet process. Moreover, due to strong connections with logistic regression models, the latter subclass can naturally account for covariates. We finally test our proposal on both synthetic and real data, with special emphasis on a large fungal biodiversity study in Finland.

# Summary. An optional shortened abstract.
summary:  We present a framework to model and extrapolate species accumulation curves, allowing for both a finite and an infinite species richness. Connections with Bayesian Nonparametric models are extensively discussed. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2011.06629.pdf
url_code: https://alessandrozito.github.io/BNPvegan/vignette.html
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://vimeo.com/manage/videos/591096595

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

