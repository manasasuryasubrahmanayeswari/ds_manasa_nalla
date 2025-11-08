# ds_manasa_nalla

**Assignment:** Trader Behavior Insights vs. Bitcoin Fear & Greed Index

## Structure

ds_manasa_nalla/
├── notebook_1.ipynb # (optional) if you add a Colab notebook
├── csv_files/ # Processed & intermediate CSVs
├── outputs/ # Visuals (PNGs)
├── ds_report.pdf # Final summarized insights
└── README.md




## How to Reproduce
1. Open the Colab notebook used to generate this folder.
2. Place/Download `historical_data.csv` and `fear_greed_index.csv` into the runtime.
3. Run cells in order (environment → load/merge → KPIs → charts → PDF).
4. Outputs will be saved under `csv_files/`, `outputs/`, and `ds_manasa_nalla/ds_report.pdf`.

## Highlights
- KPIs by sentiment (Fear vs Greed): PnL, win rate, notional/volume, long-bias.
- Visualizations saved as static PNGs for quick review.
