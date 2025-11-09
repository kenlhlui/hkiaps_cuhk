# HKIAPS Publications Scraper

This repo contains serveral python scripts and a Jupyter notebook to scrape publication data from the Hong Kong Institute of Asia-Pacific Studies (HKIAPS) website.

# File Descriptions
Each ipynb file contains the script for crawling the corresponding section. The csv files contain the scraped publication data.

There are four sections in total:
HKIAPS Publications: crawl_hkiaps-publications.ipynb ; hkiaps-publications/hkiaps-publications.csv

SRC Publications: crawl_src-publications.ipynb ; src-publications/hkiaps_src_publications.csv

CCAS Publications: crawl_ccas-publications.ipynb ; ccas-publications/hkiaps_ccas_publications.csv

CHKS Publications: crawl_chks-publications.ipynb ; chks-publications/hkiaps_chks_publications.csv

# Data table
Each csv file contains the following columns:
- id: unique identifier for each publication assigned by HKIAPS
- title: title of the publication
- metadata: additional information about the publication. May contain author(s), physical format of the original publication, ISBN, etc.
- pdf_url: URL to the PDF version of the publication
- toc_pdf: URL to the table of contents PDF (only in hkiaps-publications)
- abstract_url: URL to the abstract (only in hkiaps-publications)
- image_url: URL to the image (only in hkiaps-publications)
