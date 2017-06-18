+++
# Date this page was created.
date = "2017-06-14"

# Project title.
title = "Panbiom"

# Project summary to display on homepage.
summary = "Panbiom is a tool to estimate the core operational taxonomic units (OTUs) of a user-defined set of samples and replicates."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "card_1.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bioinformatics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
---
# Download and documentation

The source code is freely available on the official [panbiom github repository page](https://github.com/timkahlke/panbiom). Documentation and use cases can be found on the projects [wikipage](https://github.com/timkahlke/panbiom/wiki).

---

# Usage
```
panbiom.py [options] BIOM_FILE OUTPUT_FILE

Options:
-t, --treatments
List of samples (treatments) that should be considered for analysis

-m, --abundance_minimum: Minimum abundance (between 0-1) an OTU must have to be considered present (default: 0.0)

-p, --abundance_parameter: Defines whether the abundance threshold should be based on the complete data set (c) or on the defined treatments (t) (default: t)

-r, --replicate_threshold: If groups/replicates are defined in the treatments file (second column) the given abundance threshold has to be met in at least given number of replicates.

```
