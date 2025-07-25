# GEO Fundamentals: Optimization Strategies for Web Content in the Age of AI Search

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
│   ├── case2-name-gsc-index-ranking.png
│   ├── case3-tsaihaojui-chatgpt.png
│   ├── case3-tsaihaojui-google.png
│   └── case3-tsaihaojui-perplexity.png

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

## 🧪 July 2025 Update: Full Validation of GEO Three-Layer Model

We have now completed comprehensive validation for all three semantic layers of the GEO framework:

- ✅ **Layer 1: Semantic Anchoring**  
  Confirmed across all experiments. Clear topic titles, introductory summaries, and consistent page structure significantly improve citation inclusion.

- ✅ **Layer 3: Pragmatic Recomposition**  
  Most reliably triggered in natural language Q&A. Modular paragraphs, list formatting, and FAQ blocks consistently appeared in LLM-generated citations (especially in ChatGPT and Perplexity runs).

- ✅ **Layer 2: Context Triggering**  
  Newly validated via a cross-domain, paraphrase-rich simulation (see Section 6.5). When users queried with synonyms, taxonomic categories, or domain-specific rare terms, semantically expanded content continued to appear among top citations.  
  Key metrics:
  - Average 2.6 / 5 retrieved paragraphs matched Layer-2-enhanced content  
  - Top-5 citation overlap across query variants exceeded 60%  
  - Kendall’s Tau for result rankings ranged from 0.6 to 0.8, indicating robust citation stability  
  - Embedding-space distance had minimal effect on citation recall

These findings confirm that **semantic expansion and diversity (Layer 2)** play an independent role in citation selection—beyond mere keyword matching or format structure.

🧠 The full methods and metrics are documented in:
- `sections/4-method.tex`  
- `sections/5-metrics.tex`  
- `sections/6.5-layer2-validation.tex`  
- Visualizations: `figures/layer2-topk-overlap.png`, `layer2-kendall-tau.png`, `layer2-hit-rate.png`

> These results strengthen the theoretical grounding of GEO and offer practical guidance for multi-layer optimization under generative search engines.


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

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16422336.svg)](https://doi.org/10.5281/zenodo.16422336)


