# Chinmoy Mondol: Academic Portfolio Website

Source code for my personal academic portfolio, live at **[chinmoy-mondol.github.io](https://chinmoy-mondol.github.io)**.

The site brings together my research, publications, teaching, professional experience and education in one place. My research interests are **computer vision**, **multimodal AI** and **agentic AI**, with a focus on efficient perception for real-world systems.

## What's on the site

| Page | Contents |
| --- | --- |
| [About](https://chinmoy-mondol.github.io/) | Research interests and background |
| [Publications](https://chinmoy-mondol.github.io/publications/) | Conference papers and manuscripts in preparation, each with its own page, abstract and DOI |
| [Research & Teaching](https://chinmoy-mondol.github.io/research-teaching/) | Research assistant and teaching assistant roles |
| [Professional Experience](https://chinmoy-mondol.github.io/professional-experience/) | Industry roles in AI/ML quality engineering |
| [Education](https://chinmoy-mondol.github.io/education/) | Degree, honors, thesis and relevant coursework |
| [CV (PDF)](https://chinmoy-mondol.github.io/files/CV_Chinmoy_Mondol.pdf) | Full curriculum vitae |

## Where the content lives

| To update | Edit |
| --- | --- |
| Name, bio, sidebar links | `_config.yml` (`author:` section) |
| Header tabs | `_data/navigation.yml` |
| About, Research & Teaching, Professional Experience, Education | `_pages/*.md` |
| Publications | `_publications/*.md` (one file per paper) |
| CV and other downloads | `files/` |
| Photos | `images/` |

## Running locally

The site is built with [Jekyll](https://jekyllrb.com/) and runs in Docker, so no local Ruby setup is needed:

```bash
docker compose up --build -d
```

Then open <http://localhost:4000>. Content, template and style changes rebuild automatically. After editing `_config.yml`, restart the container with `docker compose restart`.

## Deployment

Pushing to `master` publishes the site through GitHub Pages. The live site usually updates within a few minutes.

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is a fork of the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) © 2016 Michael Rose. Released under the MIT License (see [LICENSE](LICENSE)).

## Contact

- Email: [chinmoy.mondol.research@gmail.com](mailto:chinmoy.mondol.research@gmail.com)
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=4QFKDIcAAAAJ) · [ORCID](https://orcid.org/0009-0002-2313-2439) · [LinkedIn](https://www.linkedin.com/in/chinmoymondol) · [GitHub](https://github.com/chinmoy-mondol)
