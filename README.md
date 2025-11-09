# Tool Window Usage Analysis

This project analyzes IDE tool window logs to find whether automatically opened windows stay open longer than manually opened ones.

## Technologies
- Python (Pandas, NumPy, Matplotlib, SciPy)
- Google Colab

## Summary
After cleaning and pairing open/close events, results showed that automatically opened windows have a significantly higher average and median duration. Statistical tests (t-test and Mann–Whitney U) confirmed the difference (p < 0.05).

## Files
`Toolwindow_Usage_Analysis.ipynb` — main analysis code

`toolwindow_events.csv` - data
