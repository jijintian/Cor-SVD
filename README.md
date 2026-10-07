# NeurIPS2026: K-OR and Cor-SVD
The code for the NeurIPS 2026 work: Permutation Sensitivity in t-SVD-based Multi-view Clustering. 

Both method folders provide these entry scripts:

| Script | Experiment |
| --- | --- |
| `run_Cor.m` | Data-derived transform basis |
| `run_fft_sample.m` | FFT along the sample dimension |
| `run_fft_view.m` | FFT along the view dimension |
| `run_fft_KOR.m` | FFT with k-means-based sample reordering |

Replace `run_Cor` in the example with the desired script name.

## Data and Results

The scripts use **MSRCv1** by default. Dataset files contain `data` (a cell array of view matrices, with samples in columns) and `truelabel` (labels accessed as `truelabel{1}`).
