
# PlumSPECTRA data

Private peer-review dataset for the PlumSPECTRA manuscript. It contains one path-free
analysis row per retained fruit, the 228-band absorbance vector, twelve observed
targets, the frozen outer fold and the full out-of-fold prediction ledger.

## Files

- `data/plumspectra_analysis_ready.parquet`: 4,853 retained fruit; list-valued wavelength and absorbance columns.
- `data/oof_predictions.parquet`: 58,206 fruit-trait predictions.
- `data/sample_fold_manifest.csv`: one frozen outer-fold assignment per retained fruit.
- `data/analysis_exclusions.csv`: model-independent source-ledger exclusions.
- `registries/`: cultivar and endpoint definitions.
- `schemas/`: machine-readable column and dtype descriptions.

Raw ARC texture archives and original instrument exports are not stored in Git. The
analysis-ready representation retains the quantitative values needed for the reported
models while removing workstation paths. Redistribution rights and the final public
data license remain pending institutional confirmation.
