# Data Dictionary

- `id`: Unique integer identifier.
- `f_00` ... `f_59`: Continuous numerical features.
- `target`: Continuous regression target in `train.csv`.

## Notes
- Features are intentionally correlated and partially redundant.
- The target is generated from a strong linear relationship with observed features plus low Gaussian noise.
- Dimensionality reduction with PCA should help denoise and may improve optimization stability.

