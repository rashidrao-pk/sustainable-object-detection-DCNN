# Migration Notes

This cleaned repository reorganizes the original archive into a structure better suited for public sharing and maintenance.

## Main changes

- Moved MATLAB scripts into `src/matlab/`
- Moved the paper PDF into `paper/`
- Collected representative images into `assets/`
- Added community files: `LICENSE`, `CITATION.cff`, `CONTRIBUTING.md`, and `CODE_OF_CONDUCT.md`
- Excluded the embedded `.git/` folder and archive leftovers from redistribution

## Recommended next improvements

- Replace hard-coded paths in MATLAB scripts with `fullfile(...)`
- Add a short reproducibility guide with expected inputs and outputs
- Add a lightweight sample dataset layout in `data/samples/`
- Consider a modern PyTorch reimplementation
