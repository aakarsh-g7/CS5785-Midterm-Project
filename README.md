# CS 5785 midterm

Run the notebooks in a Python 3 Jupyter kernel with NumPy, pandas, SciPy, scikit-learn, Matplotlib, and RDKit. All notebooks were last run from a fresh kernel with Python 3.14.7, scikit-learn 1.9.1, RDKit 2026.09.1, pandas 3.1.1, NumPy 2.5.4, SciPy 1.18.1 and Matplotlib 3.11.2.

1. Open **Part 1/part1.ipynb** from the **Part 1** directory and run all cells (under a minute). It writes:
   - **part1_submission.csv**, the average of LR and SVM with the best expected F1 rule (0.892 on the public leaderboard);
   - **part1_submission_challenger.csv**, the challenger with joint reason sets and nearby labeled trials (0.89871 on the public leaderboard);
   - **reason_labels.csv**, the true and predicted reason labels used in the Part 2 error analysis;
   - the figures **reason_share_by_year.pdf** and **gmm_clusters.pdf**.
2. Open **Part 2/part2.ipynb** from the **Part 2** directory or the repo root and run all cells (about 2 minutes). It reproduces the Part 2 blend in **part2_submission.csv** (0.59100 on the public leaderboard) and writes **part2_validation_metrics.csv**, **part2_stopping_reason_errors.csv** and **part2_calibration_metrics.csv**. It also shows the calibration plot used in the report.
3. **Part 2/part2_experiments.ipynb** contains the separate train-only experiments (about 4 minutes). It writes **part2_submission_train_only.csv** (0.61463 on the public leaderboard), **part2_submission_round2.csv** (not scored on Kaggle) and the tables **baseline_val_preds.csv**, **part2_val_comparison.csv** and **part2_error_analysis.csv**.

**midterm-project.ipynb** in the top folder runs the RDKit example from the assignment on **Part 1/part1_train.csv**.

For the report, upload **Report/Midterm.pdf** separately. The editable sources and figures are in **Report/** and use the [official CVPR 2026 author kit](https://github.com/cvpr-org/author-kit/releases/tag/CVPR2026-v1%28latex%29). Build from the **Report** directory with a full TeX Live installation, or upload the contents of **Report/** to Overleaf.

For the code upload, rename this folder to **midterm**, as the assignment requires.
