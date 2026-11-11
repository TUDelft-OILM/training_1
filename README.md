# Open interactive learning material template for Jupyterbook 1 and TeachBooks

> This repository reuses CC BY 4.0 licensed content from https://github.com/TeachBooks/template.

The template allows you to start your own open interactive learning material (OILM). It includes:

- A skeletal structure for using JupyerBook v1 / TeachBooks in `book/`
- Include the core functionalities as defined by the OILM project team in `requirements.txt` and included in `book/_config.yml`
- An opinionated list of configuration options in `book/_config.yml`.
- A script which builds your OILM on TU Delft GitLab upon every commit in `.gitlab-ci.yml`. Options can be set in Settings → CI/CD → Variables.
- A file containing the recommended license CC BY 4.0 (`LICENSE.md`)
- A citation file `CITATION.cff`

It doesn't provide full documentation on the functionalities, neither does it include examples. Please reach out to us for more information about that.

## How to get started

How to use the template is demonstrated in the steps below.

1. To get started making your open interactive learning material create a gitlab repository and copy all the files of this repository to it. For an English version, make use of the [`main` branch](https://gitlab.tudelft.nl/oicm/template_1/-/tree/main). For a Dutch version, make use of the [`main_NL` branch](https://gitlab.tudelft.nl/oicm/template_1/-/tree/main_NL).

2. To checkout the built OILM, go the result of the pipeline `Build` - `Artifacts`. It includes `book-<branch-name>.zip` with the resulting built OILM, a report on the complete build log and a summary report of the build log.

## Contribute

This template reused CC BY 4.0 licensed content from https://github.com/TeachBooks/template. If you'd like to contribute, you can create a fork and open a pull request on the [GitHub repository](https://github.com/TeachBooks/template) or this [TU-Delft OILM specific repository](https://gitlab.tudelft.nl/oicm/template_1).

##  Contact:

For questions about this template, please contact (Education Support of the TU Delft library](mailto:educationsupport-lib@tudelft.nl)

"Remove all of the above after you've taken this template and followed the instructions. The following lines are a template for your own README"

# "Open interactive learning material title"

"description of open interactive learning material's content"

## Authors / editors

"List authors / editors"

### Acknowledgements

"Add acknowledgements"

## Contact

"Add contact information for the authors / editors"

## Publishing status

"peer reviewed / used in class / currently in use in class / under development"

This book is part of the collection of Open Interactive Learning Materials from TU Delft Library | Delft University of Technology, The Netherlands.

## Reuse content

Feel free to reuse this content or contribute to it. Please give appropriate credit, provide a link to the license, and indicate if changes were made ([CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/))

To recreate this OILM, you have multiple options:

- On your own computer: clone this repository, install the required packages (`pip install -r requirements.txt`) and build the book (`teachbooks build book`). The website is stored locally in `book/_build/index.html`.
- In TU Delft GitLab: fork this repository and let the pipeline run to build the OILM
- On Github: upload this repo to a GitHub repo and include the [TeachBooks Deploy Book Workflow](https://github.com/TeachBooks/deploy-book-workflow) to build the OILM.
