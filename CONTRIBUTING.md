# Contributing Guidelines

Thank you for your interest in contributing to this project.

This repository contains research code for object recognition using fused deep features from VGG19 and Inception-v3.

## Ways to Contribute

You can contribute in several ways:

- Reporting bugs
- Suggesting improvements
- Improving documentation
- Extending the method to other datasets or frameworks
- Adding reproducible experiments or benchmarks

## Getting Started

1. Fork the repository.
2. Clone your fork:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

3. Create a new branch:

```bash
git checkout -b feature/my-feature
```

## Code Style

- Keep code clean and readable.
- Add comments where necessary.
- Avoid hard-coded dataset paths.
- Prefer relative paths and documented configuration.

## Experiments and Research Contributions

If you add new experiments:

- Clearly describe the datasets used
- Provide reproducible steps
- Include evaluation metrics
- Add generated outputs to `results/` only when they are lightweight and useful

## Documentation

- Update `README.md` when needed
- Add notes in `docs/` for larger changes
- Use concise and clear language

## Pull Request Process

1. Ensure the code runs correctly.
2. Write a clear pull request description.
3. Link related issues when relevant.
4. Wait for review before merging.

## What Not to Do

- Do not upload large datasets to the repository
- Do not include sensitive or private data
- Avoid breaking existing functionality without explanation

## Suggested Future Improvements

Contributions are welcome in areas such as:

- PyTorch reimplementation
- Explainable AI integrations such as GradCAM, SHAP, or LIME
- Modern backbones such as ResNet or Vision Transformers
- Better experiment reproducibility and configuration handling

## Contact

Maintainer: Muhammad Rashid  
GitHub: https://github.com/rashidrao-pk
