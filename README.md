# DiaMetrics

DiaMetrics is a web-based educational resource for exploring important concepts regarding binary classification (and its evaluation), which is important in many different fields such as psychodiagnostics (e.g. in determining cut-off values for tests), machine learning or medical testing.

[![DOI](https://zenodo.org/badge/704707725.svg)](https://doi.org/10.5281/zenodo.10267587)

## Installation & Usage

No installation is necessary. [Open DiaMetrics directly](https://lrosenplaenter.github.io/DiaMetrics/). Alternatively: Simply download and open index.html in your browser or store all files on your web server.

If you actually publish DiaMetrics elsewhere (e.g. on your website, in another project, etc.), I would be happy to be [notified](https://orcid.org/0009-0001-4961-2281)!

The tutorial can easily be deactivated in index.js by setting the show_tutorial_var variable (ln 9) to false.
The data displayed in example 2 is defined by data.js, and not generated pseudo-randomly (as in examples 1 & 3).

## Versions

There are two other versions of DiaMetrics:

- **DiaMetrics_DE** ([web](https://lrosenplaenter.github.io/DiaMetrics_DE/) | [repository](https://github.com/lrosenplaenter/DiaMetrics_DE)) is the German version of DiaMetrics.
- **DiaMetrics_lite** ([web](https://lrosenplaenter.github.io/DiaMetrics_lite/) | [repository](https://github.com/lrosenplaenter/DiaMetrics_lite)) is a reduced version of DiaMetrics that can be used, for example, in presentations or to engange with an audience.

## Contributing

If you have found any bug or typo (or anything else that doesn't seem right) in DiaMetrics, I would be happy to [be notified directly](https://orcid.org/0009-0001-4961-2281). You can also open an issue on github.

Note: Issues and pull requests are not actively monitored on a regular basis.

## Authors, citation and acknowledgments

DiaMetrics was developed by Leon Rosenplänter for teaching at the [Department of Psychological Diagnostics (Prof. Dr. Martin Kersting)](https://www.uni-giessen.de/de/fbz/fb06/psychologie/abt/p-diagnostik), [Justus-Liebig-University Giessen](https://www.uni-giessen.de), Germany. Many thanks to S. Bender and D. Bonarius for their essential feedback and corrections, greatly improving this project.

Please quote DiaMetrics as follows: See [*CITATION.md*](https://github.com/lrosenplaenter/DiaMetrics/blob/main/CITATION.cff)

DiaMetrics uses [Bootstrap](https://getbootstrap.com/) v5.3.1 for the design of the website and some visual functions. 

DiaMetrics uses [Chart.js](https://www.chartjs.org) v4.4.0 to display the scatter plots.

DiaMetrics uses the [dragdata plugin for Chart.js](https://github.com/chrispahm/chartjs-plugin-dragdata) v2.2.3 to make the separator draggable.

## License

Copyright (c) 2023 - 2025 Leon Rosenplänter. DiaMetrics is available under the [MIT](https://choosealicense.com/licenses/mit/) license. The full text of the license can be found in the [*LICENSE.md*](https://github.com/lrosenplaenter/DiaMetrics/blob/main/LICENSE.md) file.