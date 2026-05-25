# NSI Public Datasets

This repository maintains splash pages and supporting materials for public
cone-beam CT datasets distributed through Purdue Data Depot.

Each dataset is organized as a self-contained directory with an `index.html`
splash page describing the data, acquisition parameters, download links, and,
when available, figures, preprocessing scripts, and citation information.

## Available Datasets

| Dataset | Description | Splash Page |
| --- | --- | --- |
| NSI Plastic Phantom CBCT: Paired Metal and Metal-Free Scans | Paired cone-beam CT scans of the same plastic phantom acquired with and without metal for metal artifact evaluation and correction. | [View page](nsi_phantom_metal_pair/index.html) |
| NSI 4D Phantom CBCT: NSI Phantom Dynamic Scan | Dynamic cone-beam CT scan of a 4D phantom for time-resolved reconstruction evaluation. | [View page](nsi_4D_phantom/index.html) |

## Repository Layout

```text
NSI_public_datasets/
  README.md
  nsi_phantom_metal_pair/
    index.html
  nsi_4D_phantom/
    index.html
```

As additional datasets are added, the preferred directory layout is:

```text
<dataset_name>/
  index.html
  data/       # Optional downloadable files or preprocessing scripts
  figs/       # Optional figures referenced by the splash page
```

## Dataset Page Convention

Splash pages are designed for deployment on a Purdue Data Depot personal web
space and generally include:

- A concise dataset title and description.
- Links to downloadable dataset archives.
- A table of acquisition parameters.
- Optional figures, preprocessing code, and citation information.

Download files may either be stored alongside a page or linked directly from
their Data Depot hosting location.

## Current Dataset Downloads

### NSI Plastic Phantom CBCT: Paired Metal and Metal-Free Scans

- [Plastic phantom without metal - 1200 views](https://www.datadepot.rcac.purdue.edu/bouman/data/demo_nsi_vert_no_metal_all_views.tgz)
- [Plastic phantom with metal - 1200 views](https://www.datadepot.rcac.purdue.edu/bouman/data/demo_nsi_vert_metal_all_views.tgz)
