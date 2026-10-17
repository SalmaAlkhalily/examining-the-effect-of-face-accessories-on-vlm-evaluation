The 40 image files are already in the shared pilot; match exact filename and SHA-256 in manifest.csv
Only two tasks for the evaluuation, job fitness and accessories prediction for both of the models (siglip and minicpm)

- raw_*.jsonl preserves every model output, including abstentions and invalid formats
- *_jobs.csv includes all 120 planned job questions/scores per model. Missing numeric scores remain empty
- *_paired_differences.csv includes every planned contrast and its validity, not only usable pairs
- *_accessory_predictions.csv contains model predictions

