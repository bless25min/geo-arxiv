# GEO: Generative Engine Optimization (arXiv Draft)

This repository contains the LaTeX source for the arXiv paper:

**GEO Fundamentals: Optimization Strategies for Web Content in the Age of AI Search**

- Author: Tianyou Liao (Independent Researcher)
- Submission domain: cs.IR (Information Retrieval) or cs.CL (Computation and Language)
- Abstract: This paper proposes a semantic framework for improving content visibility in AI-generated search answers. Includes implementation methodology, metrics, and two case studies.

All source files are formatted for direct arXiv submission.

## 📁 Directory Structure

```

geo-arxiv/
├── main.tex
├── references.bib
├── sections/
│   ├── 1-introduction.tex
│   ├── ...
│   └── 9-conclusion.tex
├── figures/
│   ├── case1-soya-chatgpt-run1.png
│   ├── case1-soya-chatgpt-run2.png
│   ├── case1-soya-perplexity-run1.png
│   ├── case1-soya-perplexity-run2.png
│   ├── case2-name-chatgpt-result.png
│   ├── case2-name-perplexity-result.png
│   ├── case2-name-google-serp.png
│   └── case2-name-gsc-index-ranking.png

```

## 📸 Screenshot Evidence (Experimental Validation)

The `figures/` folder includes supplementary screenshots from the two case studies:

- \*\*Case Study 1: SOYA 課程評價\*\*
  - ChatGPT and Perplexity responses before/after GEO optimization
- \*\*Case Study 2: 廖天佑 Name-Based Test\*\*
  - Visibility confirmation via ChatGPT citation, Perplexity snippet inclusion
  - Google Search Console average position report (7/6–7/15)

These figures are referenced in Sections 6 and 7 of the paper and help validate citation performance claims under controlled, zero-login conditions.

> Screenshots are included for reproducibility and verification, but are not part of the arXiv submission package.

## 🔁 Postscript: Reverse Experiment – SEO Without GEO

To further validate the necessity of semantic structuring in GEO, we conducted an additional reverse experiment using a low-competition English name: **Tsai Hao Jui**.

We authored a web article on AI citation optimization using this name, deliberately **omitting** the GEO structuring framework (i.e., no modular paragraphs, no Schema.org, no semantic mesh). Due to the rarity of this name, the page quickly ranked first in SEO for "Tsai Hao Jui".

However, the AI search visibility results tell a different story:

- 🔍 **Google**: ranked #1 on name search ✅
- 🤖 **ChatGPT**: returned no information related to the authored article ❌
- 📘 **Perplexity**: cited only the LinkedIn profile, not the article ❌

These results underscore the core distinction:  
**SEO alone may secure ranking, but GEO is essential for citation.**

### 📎 Screenshots:

- `figures/case3-tsaihaojui-chatgpt.png`
- `figures/case3-tsaihaojui-google.png`
- `figures/case3-tsaihaojui-perplexity.png`

This confirms that content not structured semantically, even when ranked highly, is unlikely to be cited or extracted by generative engines.


---
## 📜 License and Originality

This repository contains original research by **Tianyou Liao**.

First created and published via GitHub on July 16 2025. All LaTeX files, experiments, and results are authored independently.

Licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**.  
See `LICENSE` file for details.

If you wish to reuse or cite this work, please attribute the original author and link to this repository.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16080281.svg)](https://doi.org/10.5281/zenodo.16080281)
