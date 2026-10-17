# PRISM · ICML 2026

Project homepage for **PRISM: Learning Realistic Depth via Physics-Grounded Noise Disentanglement with Semantic-Geometric Collaboration**.

Website: https://shawnleung-sii.github.io/prism-icml2026/

This repository contains the static project website, paper PDF and publication figures. Research code is coming soon.

The page presents physics-grounded depth simulation for embodied manipulation, with in-domain and cross-camera evaluation, component/backbone/supervision ablations, five appendix scene galleries (Figures 10–14), real/simulation environments (Figure 9), and six task rollouts (Figures 15–20). Figures use consistent captions and display inline without a lightbox. The authors report ongoing work on cross-sensor generalization and temporal noise consistency; research code will be released in the future.

## Editing and hosting

Edit `index.html` to update content, styles and interactions. Figures are in `images/`. No build step or external runtime dependency is required. GitHub Pages serves this directory directly; `.nojekyll` keeps the site static.

Tables 1–4 and 15–17 are displayed as high-resolution crops from the supplied paper PDF, preserving every original method, metric and annotation. The five scene galleries retain all eight columns of the original figures. The compact cover appears beside the ICML logo without an additional caption.

The presentation was developed using the [paper2html workflow](https://github.com/QuZhan51496/paper2anything/tree/main/paper2html), with custom interactive galleries. All research figures and reported results come from the authors’ supplied paper.
The official ICML logo is sourced from the [ICML press resources](https://icml.cc/Conferences/2026/Press) ([original SVG](https://icml.cc/media/Press/ICML-logo.svg)).

The project cover (`images/PRISM-cover.png`) is an AI-assisted conceptual illustration of noise disentanglement, separate from the original paper figures. It also supplies the social sharing preview.


## October 18 update

Compact conference / cover / institution header. The author-supplied Sim2Real pipeline replaces the prior figure. Main-content images load lazily; the cover is a 56 KB WebP. Text is left aligned, with wider method descriptions; all result tables remain original PDF crops.

Institution logo sources (official websites):
- Fudan: https://www.fudan.edu.cn/_upload/tpl/00/06/6/template6/images/logo.png
- Shanghai Innovation Institute: https://www.sii.edu.cn/_upload/tpl/00/09/9/template9/images/logo.svg
- Zhejiang University: https://www.zju.edu.cn/_upload/article/images/c3/98/1fb1d281492eb477a098ef7a2901/6d8d432f-56ac-47eb-b22d-a23b103aed01.png
- Shanghai Jiao Tong University: https://vi.sjtu.edu.cn/img/base/Logo.png
- Ant Group: https://www.antgroup.com/en/news-media/media-library


## Title, horizontal institution marks and arXiv entry

The page displays the exact paper title as its single main heading. `series` is omitted from both the visible and downloadable BibTeX. The arXiv entry is marked “coming soon” and temporarily links to https://arxiv.org/; replace that URL in the resource link once the paper has an identifier.

Horizontal logo sources:
- Zhejiang University official site: https://www.zju.edu.cn/_upload/site/1/logo.png (official white artwork displayed in university blue through CSS).
- Shanghai Jiao Tong University official VI download: https://vi.sjtu.edu.cn/index.php/downloads/attachments/137
- arXiv official white wordmark: https://info.arxiv.org/assets/arxiv-logo-one-color-white.svg


## Continuous captions and corrected Zhejiang mark

The Zhejiang header resource also contained a site-search label. `logo-zju-clean.svg` restricts its viewport to the official emblem and bilingual university name; no search text is displayed. Captions now flow directly after their highlighted titles. Balanced line wrapping and concise descriptions avoid isolated one- or two-word lines in static and interactive captions.


## Equal-width captions

Figure wrappers now set one shared width for images and captions, including the smaller original tables. Captions and section introductions use natural full-width wrapping rather than balanced lines. The first author's homepage link is removed, and limitations / future work are presented in one paragraph.
