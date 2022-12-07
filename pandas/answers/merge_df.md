## merge_df.ipynb "p_range"

```{python}
merged_df["low_score"] = merged_df[["p1", "p2", "p3"]].min(axis = 1)
merged_df["high_score"] = merged_df[["p1", "p2", "p3"]].max(axis = 1)
merged_df["p_range"] = merged_df["high_score"] - merged_df["low_score"]
merged_df
```