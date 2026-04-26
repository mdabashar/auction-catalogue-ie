# Auction Catalogue Information Extraction Web App

## Overview

This application extracts structured information from historical auction catalogue PDFs using OCR and rule-based parsing.

## Features

* PDF upload via web interface
* OCR-based text extraction
* Lot and front-page detection
* Review flagging system
* Export to CSV and JSON

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/auction-catalogue-ie.git
cd auction-catalogue-ie/webapp

pip install flask
pip install -e ../historical_auction_catalogue_ie/

python app.py
```

## Requirements

* Python 3.9+
* Tesseract OCR
* Poppler

## Usage

1. Open browser at http://localhost:5000
2. Upload a PDF
3. Wait for processing
4. Download results

## Outputs

* lots.csv
* front_pages.csv
* review_flags.csv

## License

MIT License
