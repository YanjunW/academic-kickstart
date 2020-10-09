+++
title = "[PLDI'20] Reconciling enumerative and deductive program synthesis"
date = 2020-06-19
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kangjing Huang", "Xiaokang Qiu", "Peiyuan Shen", "**Yanjun Wang**"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*41st ACM SIGPLAN Conference on Programming Language Design and Implementation*"
publication_short = "PLDI 2020"

# Abstract and optional shortened version.
abstract = "Syntax-guided synthesis (SyGuS) aims to find a program satisfying semantic specification as well as user-provided structural hypotheses. There are two main synthesis approaches: enumerative synthesis, which repeatedly enumerates possible candidate programs and checks their correctness, and deductive synthesis, which leverages a symbolic procedure to construct implementations from specifications. Neither approach is strictly better than the other: automated deductive synthesis is usually very efficient but only works for special grammars or applications; enumerative synthesis is very generally applicable but limited in scalability. In this paper, we propose a cooperative synthesis technique for SyGuS problems with the conditional linear integer arithmetic (CLIA) background theory, as a novel integration of the two approaches, combining the best of the two worlds. The technique exploits several novel divide-and-conquer strategies to split a large synthesis problem to smaller subproblems. The subproblems are solved separately and their solutions are combined to form a final solution. The technique integrates two synthesis engines: a pure deductive component that can efficiently solve some problems, and a height-based enumeration algorithm that can handle arbitrary grammar. We implemented the cooperative synthesis technique, and evaluated it on a wide range of benchmarks. Experiments showed that our technique can solve many challenging synthesis problems not possible before, and tends to be more scalable than state-of-the-art synthesis algorithms."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "pldi2020.ppsx"
url_video = ""
url_poster = ""
url_source = "https://github.com/purdue-cap/DryadSynth"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "https://doi.org/10.1145/3385412.3386027"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
