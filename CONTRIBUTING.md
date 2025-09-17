<div style="display: flex; justify-content: space-between;">
  <a href="README.md"><img src="https://img.shields.io/badge/homepage-red?style=for-the-badge" /></a>
  <a href="CONTRIBUTING_CN.md"><img src="https://img.shields.io/badge/简体中文-blue?style=for-the-badge" /></a>
</div>


# 🤝 Contributing to Our Repository

Thank you for your interest in contributing to this repository! This project relies on community contributions to stay comprehensive and up-to-date. Your attention as one of our collaborators is greatly appreciated.

## 📖 Table of Contents

- [🤝 Contributing to Our Repository](#-contributing-to-our-repository)
  - [📖 Table of Contents](#-table-of-contents)
  - [📝 How to Contribute](#-how-to-contribute)
  - [🚀 Your First Contribution](#-your-first-contribution)
  - [✍️ Guidelines for Adding a New Paper](#️-guidelines-for-adding-a-new-paper)
  - [📥 Pull Request Process](#-pull-request-process)

---

## 📝 How to Contribute

You can contribute to the project in several ways:

* ✍️ **Adding a New Paper**: Share the missing research you find. We always welcome you to contribute your own published papers or pre-prints to our repository through [PR](https://github.com/QuenithAI/Diffusion-Large-Language-Models-Paper-List/pulls) or [Issues](https://github.com/QuenithAI/Diffusion-Large-Language-Models-Paper-List/issues).
* 🗂️ **Adding a New Dataset**: Share benchmark datasets used in the field of video generation.
* 🛠️ **Fixing Errors**: Correct typos, formatting issues, or broken links.
* 💡 **Suggesting Enhancements**: Propose improvements, such as new paper categories, via [Issues](https://github.com/QuenithAI/Diffusion-Large-Language-Models-Paper-List/issues).

## 🚀 Your First Contribution

If you're new to contributing, please follow the standard GitHub workflow:

1.  **Fork** this repository to your personal account.
2.  Create a new feature branch from the `main` branch. Please use a descriptive branch name, for example:
    ```bash
    # Example: Add a paper named MotionDirector
    git checkout -b feature/add-motiondirector-paper
    ```
3.  Make your changes on your new branch (e.g., add a paper or dataset entry).
4.  Commit your changes. Please use a clear commit message to describe your work:
    ```bash
    # Example: Add a new dataset
    git commit -m "feat: Add OpenVid-1M Dataset"
    ```
5.  Push your branch to your forked repository:
    ```bash
    git push origin feature/add-motiondirector-paper
    ```
6.  Create a Pull Request from your forked repository to the `main` branch of this repository.

## ✍️ Guidelines for Adding a New Paper

This is the most common type of contribution. To ensure consistency, please follow these steps carefully:

1.  **Find the Correct Location**
    * First, identify the main category the paper belongs to (e.g., `Text-to-Video`, `Image-to-Video`).
    * Then, find the section for its publication year.
    * Finally, place it in the `✅ Published Papers` or `💡 Pre-Print Papers` list.

2.  **Use the Standard Format Template**
    * Please copy the template below and replace the placeholder information. This ensures all entries have a consistent style.

    **General Template:**
    ```markdown
    - [DreamOn: Diffusion Language Models For Code Infilling Beyond Fixed-Size Canvas](https://hkunlp.github.io/blog/2025/dreamon/) [![GitHub Stars](https://img.shields.io/github/stars/DreamLM/DreamOn?style=social)](https://github.com/DreamLM/DreamOn)   [![Project Page](https://img.shields.io/badge/Project-Page-blue?logo=website)](https://hkunlp.github.io/blog/2025/dreamon/) [![Huggingface Face](https://img.shields.io/badge/Hugging-Face-orange?logo=website)](https://huggingface.co/Dream-org/DreamOn-v0-7B)
    ```
    * If the paper does not have a GitHub repository or a project page, simply **delete** the corresponding line.
    * If the paper was published at a conference but doesn't have an ArXiv link, you can use the `Paper` badge. Please refer to existing examples in `README.md`.

3.  **Verify Information**
    * Before submitting, please double-check that all links are valid and point to the correct destination.
    * Confirm that the paper title, authors, conference, and year details are accurate.

## 📥 Pull Request Process

When you submit a Pull Request, please keep the following in mind:

* Provide a clear title for your PR, e.g., `feat: Add 3 new papers from CVPR 2025`.
* Briefly describe the changes you've made in the description.
* After submission, the maintainers will review your contribution as soon as possible. Thank you for your patience!