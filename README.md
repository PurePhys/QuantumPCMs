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
@article{strikis2022quantum,
  title={Quantum LDPC Codes for Modular Architectures},
  author={Strikis, Armands and Berent, Lucas},
  journal={arXiv preprint arXiv:2209.14329},
  year={2022}
}
```
