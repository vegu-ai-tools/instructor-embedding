# Instructor-Embedding (Fork for Talemate)

> **Note**: This is a minimal fork of [HKUNLP/instructor-embedding](https://github.com/HKUNLP/instructor-embedding) created solely to fix installation issues within the [Talemate](https://github.com/vegu-ai/talemate) project.

## Purpose

This fork exists **only** to resolve installation issues when using instructor-embedding with Talemate. There are no plans to maintain this fork beyond ensuring it remains functional for Talemate's needs.

### What's Fixed

- Python 3.10+ compatibility (supports 3.10, 3.11, 3.12, 3.13)
- Dependency conflicts that prevented clean installation in modern Python environments
- Migrated to pyproject.toml with Poetry support

## Installation

```bash
pip install git+https://github.com/vegu-ai-tools/instructor-embedding.git
```

## Documentation

For all usage documentation, model details, and API reference, please see:
- [Original Repository](https://github.com/HKUNLP/instructor-embedding)
- [Original README](README-original.md)

## License

Apache License 2.0 (same as original project)

## Citation

If you use this in research, please cite the original authors:

```bibtex
@inproceedings{INSTRUCTOR,
  title={One Embedder, Any Task: Instruction-Finetuned Text Embeddings},
  author={Su, Hongjin and Shi, Weijia and Kasai, Jungo and Wang, Yizhong and Hu, Yushi and  Ostendorf, Mari and Yih, Wen-tau and Smith, Noah A. and  Zettlemoyer, Luke and Yu, Tao},
  url={https://arxiv.org/abs/2212.09741},
  year={2022},
}
```
