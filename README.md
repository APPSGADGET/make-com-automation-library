# make-com-automation-library# seo-keyword-cluster-tool
Python script to cluster keywords by semantic similarity for content planning.

## Features
- CSV input of keywords
- Text vectorization (TF-IDF / embeddings)
- KMeans-based clustering
- Output cluster CSV for content buckets

## Usage
pip install -r requirements.txt
python src/cluster.py --input keywords.csv --output clusters.csv

seo-keyword-cluster-tool/
├─ data/
├─ src/
│  └─ cluster.py
├─ README.md
└─ requirements.txt
