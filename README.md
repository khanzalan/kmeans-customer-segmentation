# K-Means Customer Segmentation

Segments synthetic customer data into three spending tiers — low, mid, and high spenders — using K-Means clustering on annual spend and purchase frequency.

## What it does

1. Generates 90 synthetic customers across 3 spending groups using `numpy` normal distributions (low, mid, high spenders, 30 each)
2. Fits `sklearn.cluster.KMeans` with `k=3` to discover the groups
3. Plots a before/after comparison — raw scattered data vs. color-coded clusters with centroids marked
4. Prints each cluster's average spend and purchase frequency

## Setup

```bash
pip install scikit-learn matplotlib numpy
```

## Usage

Open `k_means.ipynb` and run all cells. Outputs a `kmeans_clusters.png` comparison plot alongside console stats for each cluster.

## Example output

Three clusters roughly matching:
- **Low Spenders** — ~$200/year, ~5 purchases
- **Mid Spenders** — ~$500/year, ~15 purchases
- **High Spenders** — ~$900/year, ~30 purchases

## License

MIT