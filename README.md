# {{product_name}}

## Introduction

{{product_introduction}}

## Directory structure

### Option 1: general structure
```
{{directory_name}}/
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
{{directory_name}}/
├── Readme.md
├── analysis
│    └── report.Rmd
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
{{directory_name}}/
├── analysis
├── data/
│   ├── derived_data/
│   └── raw_data/
├── docs/
├── product/
└── R/
```

* **analysis** - Markdown or Jupyter notebooks
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
