# Paper Resources
This repository contains the parity-check matrices that were used in our recent paper "Quantum LDPC Codes for Modular Architectures" [[1]](https://arxiv.org/abs/2209.14329).

The parity-check matrices are provided as binary matrices (using spaces and newlines as delimeters) *.txt and *.mtx files, respectively. The filenames refer to the example numbers in the paper.

The following files are currently included: 

* Example-5A.txt and Example-6B-Classical.txt: parity check matrices of classical codes used in Sections 5 and 6
* Example-6B-Hx/Hz: parity check matrices of the balanced product quantum code (in *.txt and *.mtx format)

The MTX format ([[2]](https://math.nist.gov/MatrixMarket/formats.html)) can be used in the GAP package QDistRnd [[3]](https://doi.org/10.21105/joss.04120).

# Referencing

If you use our resources for your research, we will be thankful for an according citation: 

```bibtex
@article{PRXQuantum.4.020321,
  title = {Quantum Low-Density Parity-Check Codes for Modular Architectures},
  author = {Strikis, Armands and Berent, Lucas},
  journal = {PRX Quantum},
  volume = {4},
  issue = {2},
  pages = {020321},
  numpages = {14},
  year = {2023},
  month = {May},
  publisher = {American Physical Society},
  doi = {10.1103/PRXQuantum.4.020321},
  url = {https://link.aps.org/doi/10.1103/PRXQuantum.4.020321}
}
```
