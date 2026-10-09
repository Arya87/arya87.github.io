# Yao-Hui Li's personal homepage

Target URL: [https://yhli.github.io/](https://yhli.github.io/).

This site uses plain HTML and CSS and is adapted from [Nicklas Hansen's template](https://github.com/nicklashansen/nicklashansen.github.io).

## Contact

- Email: lyh19970807@163.com
- GitHub: [Arya87](https://github.com/Arya87)
- Google Scholar: [Yao-Hui Li](https://scholar.google.com/citations?user=tochFCMAAAAJ&hl=en)

## Local preview

Open `index.html` in a browser. The profile photo is `files/me.jpg`; its path is configured in `style.css`. No build step is required.

The local directory name does not determine the published URL. Upload the directory's contents at the repository root. `.nojekyll` marks the site as plain static files; `.gitignore` excludes the unused legacy template license file `files/mjkey.txt`.

Use Git rather than the browser upload form: `files/SLOPE.gif` is about 43.82 MiB, above GitHub's 25 MiB browser upload limit and below its 100 MiB Git file limit. See the [GitHub upload documentation](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## Publish to GitHub Pages

1. To use the requested URL `https://yhli.github.io/`, publish from the `yhli.github.io` repository owned by the `yhli` user or organization. This requires access to that account or organization. The contact profile is `Arya87`; its default user-site URL would be `https://arya87.github.io/`. Site metadata currently retains the requested `yhli.github.io` URL.
2. Upload the contents of this directory so that `index.html`, `style.css`, `files/`, and `bibtex/` are at the repository root. Do not upload them inside an extra `nicklashansen.github.io-master/` folder.
3. In the repository's **Settings → Pages**, select **Deploy from a branch**, the branch containing these files (for example `main`), and **/(root)**, then save.
4. Leave **Custom domain** empty. A `CNAME` file is not needed for `https://yhli.github.io/`.
5. Once deployment completes, open [https://yhli.github.io/](https://yhli.github.io/).

## Publications

The publication list uses the six BibTeX files in `bibtex/` and the matching images in `files/`. Entries are sorted by year, and Yao-Hui Li's name is bold in each author list. Buttons use `paper / code / bibtex`; entries without a code URL show `paper / bibtex`.

| Paper | Year | Venue | Highlighted | Image | BibTeX |
| --- | --- | --- | --- | --- | --- |
| SLOPE | 2026 | NeurIPS | Yes | `files/SLOPE.gif` | `bibtex/SLOPE.txt` |
| WISDOM | 2026 | ICLR | No | `files/WISDOM.png` | `bibtex/WISDOM.txt` |
| MFSC | 2025 | ICML | Yes | `files/MFSC.png` | `bibtex/MFSC.txt` |
| RevBis | 2025 | arXiv preprint | No | `files/RevBis.png` | `bibtex/RevBis.txt` |
| RMPC | 2025 | Applied Soft Computing | Yes | `files/RMPC.png` | `bibtex/RMPC.txt` |
| HI-FER | 2024 | Knowledge-Based Systems | Yes | `files/HI-FER.jpg` | `bibtex/HI-FER.txt` |

Paper and code links are taken from the supplied BibTeX records and additional links provided by Yao-Hui Li. SLOPE's NeurIPS 2026 venue information is supplied by the author; its code URL is pending. The biography describes doctoral studies at Beijing Institute of Technology, master's studies at Hebei University, a research visit to Heriot-Watt University, and interests in deep reinforcement learning, robot learning, and embodied intelligence.

See the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) for publishing details and [default site URL rules](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages).
