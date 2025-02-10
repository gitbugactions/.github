# GitBug-Actions

Welcome to GitBug-Actions - We build executable code datasets using GitHub Actions!

## About Us

GitBug-Actions is a research initiative that develops tools for mining and executing software repositories. Our main focus is on creating reproducible bug-fix benchmarks by leveraging GitHub Actions, ensuring that discovered bugs and their fixes can be reliably reproduced in the future.

## Key Projects

### 🛠️ [gitbugactions](https://github.com/gitbugactions/gitbugactions)
Our flagship tool that mines repositories and builds executable code datasets. It:
- Analyzes GitHub repositories and their commit history
- Executes GitHub Actions locally to extract execution information (e.g., tests)
- Creates Docker images with reproducible environments
- Ensures long-term reproducibility

### ☕ [gitbug-java](https://github.com/gitbugactions/gitbug-java)
A comprehensive Java bug benchmark featuring recent bugs from real-world projects:
- [Web Interface](https://nfsaavedra.github.io/gitbug-java)
- Available on [HuggingFace](https://huggingface.co/datasets/gitbugactions/gitbug-java)
- Fully reproducible environment with Docker support
- Detailed test execution results and metadata

## Research

If you use our tools in your research, please cite:

```bibtex
@inproceedings{gitbugactions,
 title = {GitBug-Actions: Building Reproducible Bug-Fix Benchmarks with GitHub Actions},
 year = {2024},
 doi = {10.1145/3639478.3640023},
 author = {Saavedra, Nuno and Silva, Andr{\'e} and Monperrus, Martin},
 booktitle = {Proceedings of the ACM/IEEE 46th International Conference on Software Engineering: Companion Proceedings},
}
```

```bibtex
@inproceedings{gitbugjava,
  title={GitBug-Java: A Reproducible Benchmark of Recent Java Bugs},
  author={Silva, Andr{\'e} and Saavedra, Nuno and Monperrus, Martin},
  booktitle={Proceedings of the 21st International Conference on Mining Software Repositories},
  doi={10.1145/3643991.3644884}
}
```

## Getting Started

Visit our main repositories to get started:
- [gitbugactions](https://github.com/gitbugactions/gitbugactions) - For the main mining tool
- [gitbug-java](https://github.com/gitbugactions/gitbug-java) - For the Java bug benchmark

Each repository includes detailed setup instructions and usage examples.

## Contributing

We welcome contributions to any of our projecs, feel free to open a PR!

