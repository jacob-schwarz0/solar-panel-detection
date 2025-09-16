# Solar Panel Detection from Satellite Imagery

This repository contains code, data, and notebooks for a computer vision project that detects solar panels on residential properties using satellite imagery and YOLO object detection.

## Project Overview

- **Goal:** Identify properties with solar panels using satellite images and machine learning.
- **Tech Stack:** Python, Jupyter Notebooks, OpenCV, Selenium, Ultralytics YOLO, Label Studio.
- **Data:** Scraped address data, geocoded locations, and satellite images for Aberfoyle Park, Adelaide.
- **Model:** YOLO object detection, fine-tuned for solar panel detection.
- **Results:** Achieved 92% classification accuracy.

## Directory Structure

- `*.ipynb` — Jupyter notebooks for data collection, geocoding, image processing, and model training.
- `satellite_imagery/` — Raw satellite images.
- `scraped_addresses/` — Address and geocoding CSVs.
- `Upload to Google Colab/` — Datasets, annotations, and exported models.
- `requirements.txt` — Python dependencies.

## Blog Article

Read the full story and technical details in the blog post:  
[Counting with Computers: Using YOLO to Spot Solar Panels in Satellite Imagery](https://www.blog.example.com)

## Usage

1. Install dependencies:  
   `pip install -r requirements.txt`
2. Run the notebooks in order for data collection, processing, and model training.
3. Review results and exported models in the `Upload to Google Colab/` folder.
