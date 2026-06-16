# OVRO LWA Solar Observation Examples

This directory contains draft AWS Open Data tutorial material for the OVRO LWA
Solar Observation dataset.

The main notebook follows the AWS Open Data Sponsorship Program "Get To Know A
Dataset" template described in section 2.3 of the onboarding handbook:

- [get-to-know-a-dataset.ipynb](get-to-know-a-dataset.ipynb)

The notebook is intentionally written as a draft because the AWS S3 bucket and
sample object key have not been created yet. Replace the placeholder bucket and
sample-key values before executing the S3 cells end to end.

## Local Setup

Install the lightweight tutorial dependencies:

```sh
python -m pip install -r requirements.txt
```

The optional `lwasolarutl` package provides OVRO-LWA specific FITS/HDF
conversion and plotting helpers:

```sh
python -m pip install git+https://github.com/ovro-eovsa/lwa-solar-util.git
```

