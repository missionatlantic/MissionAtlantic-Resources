# Template for Mission Atlantic analysis

## Introduction

{{product_introduction}}

This is a template to be used for the different Mission Atlantic Work Packages and Case Studies, to document and collaborate on the data processing steps.

## Directory structure

### Option 1: general structure
```
WP5-Case_study_A/
├── analysis
├── data/
│   ├── derived_data/
│   └── raw_data/
├── docs/
├── product/
└── scripts/
```
* **analysis** - Markdown or Jupyter notebooks
* **data** - Raw and derived data
* **docs** - Rendered reports
* **product** - Output product files
* **scripts** - Reusable code

so a structure with some files could look like this:

```
WP5-Case_study_A/
├── Readme.md
├── analysis
│    └── report.Rmd
│    └── report.ipynb
├── data/
│    ├── raw_data/
│    │   └── my_data.csv
│    └── derived_data/
│        └── my_processed_data.csv
├── docs/
│     └── report.html
│     └── report.pdf
├── product/
└── scripts/
      └── myfunctions.R
```



### Option 2: R structure
```
WP5-Case_study_A/
├── analysis
│    └── report.Rmd
├── data/
│   ├── derived_data/
│   └── raw_data/
├── docs/
├── product/
└── R/
```

* **analysis** - RMarkdown notebooks
* **data** - Raw and derived data
* **docs** - Rendered reports
* **product** - Output product files
* **R** - Reusable R scripts/code

## Data series

{{data_series}}

```
{{data_wfs_request}}
```

## Data product

{{data_product_description}}

## More information:

### References

### Code and methodology

{{link_code}}

### Citation and download link

This product should be cited as:

{{product_citation}}

Available to download in:

{{link_download}}

### Authors

{{product_authors}}
