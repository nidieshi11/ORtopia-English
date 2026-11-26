# ORtopia English

A Utopia for AI-Native Operations Research.

[Open the website](https://nidieshi11.github.io/ORtopia-English/) · [Dataset](https://nidieshi11.github.io/ORtopia-English/dataset/) · [Simulation](https://nidieshi11.github.io/ORtopia-English/simulation/)

## Explore the collection

The [subject directory](https://nidieshi11.github.io/ORtopia-English/dataset/#/domains) groups 206 research problems into 14 application areas. Each problem brings together a scene illustration, mathematical model, problem statement and citation. The [paper library](https://nidieshi11.github.io/ORtopia-English/dataset/#/library) groups the articles by journal series. Paper titles open the corresponding problem pages.

The [simulation directory](https://nidieshi11.github.io/ORtopia-English/simulation/) opens the interactive replays. The medium-scale collection contains 181 instances with at least 10,000 decision variables and 10,000 constraints each. The other 25 problems have their own dedicated simulations.

GitHub links inside Dataset point to the associated [ORtopia-bench](https://github.com/nidieshi11/ORtopia-bench) source. Access to that separate repository is restricted to authorized accounts.

## Run locally

From the repository root, run `python -m http.server 8000` and open [localhost:8000](http://localhost:8000/). The site consists of static files. GitHub Pages publishes from the root of the main branch.

## License

The original website and simulation code in this repository is available under the [MIT License](LICENSE). The license applies to that software. Papers, third-party figures and research materials retain their respective rights. Bundled KaTeX code and fonts carry their own [license](dataset/vendor/katex/LICENSE).
