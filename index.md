---
title: "🪐 GeoJupyter 🌐"
subtitle: |
  _Exploring more approachable geospatial data workflows as an open community_
authors:
  # TODO: Should make this more reusable for different presenters.
  # For this first pass, I'll be giving the presentation, so... it's how it is right now
  # :)
  - name: "Matt Fisher"
    orcid: "0000-0003-3260-5445"
    affiliation:
      - name: "Schmidt DSE, UC Berkeley"
format:
  revealjs:
    from: "markdown+emoji"
    theme: "white"
    css: "assets/css/slides.css"
    footer: "[Home](/) | [Source](https://github.com/SchmidtDSE/geojupyter-pitch) | [geojupyter.org](https://geojupyter.org)"
    auto-stretch: true
    slide-number: true
---

## :wave: Hi, I'm Matt! GitHub: `@mfisher87` {.smaller}

:::evenly-spaced
:computer: Research Software Engineer ([RSE](https://us-rse.org/))

:people_holding_hands: Community Engagement Manager

:snowflake: Previously at [National Snow & Ice Data Center (NSIDC)](https://nsidc.org)

:open_hands: Open source maintainer & contributor:
[jupytergis](https://github.com/geojupyter/jupytergis),
[jupyter-xarray-tiler](https://github.com/geojupyter/jupytergis),
[earthaccess](https://github.com/nsidc/earthaccess),
[conda-forge](https://conda-forge.org/) feedstocks,
more!

:open_hands: :open_book: :brain:
:seedling: :notes: :drum: :musical_keyboard: :dog:
:::

# :earth_asia: GeoJupyter community overview

:link: [geojupyter.org](https://geojupyter.org/)


## GeoJupyter community overview {.smaller}

:::::::::columns
::::::{.column width="48%"}
![GeoJupyter is **not** software; it’s a **community** which will build many things together!](/assets/images/venn-diagram.svg)
::::::

::::::{.column width="4%"}
::::::

::::::{.column width="48%"}

:::elevator-pitch
<br />
<br />

<hr />
GeoJupyter is an open and community-owned effort to
[reimagine geospatial interactive computing experiences _within the Jupyter architecture_]{.jupyter-orange}
to enable more people to confidently engage with geospatial data.
<hr />

<br />
<br />

Many players!!!
:::
::::::
:::::::::


## GeoJupyter community overview {.smaller}

### Geospatial data practice for the modern era

**Geospatial data is everywhere and matters for everyone! 🚚🚢🗺️🧪🌏**

:::evenly-spaced
:handshake: Real-time collaboration (like Google Docs)

:recycle: Reproducibility (by default!)

:leaves: Accessibility (transition to new ways of working, including reproducibility)

:cloud: Cloud-native (computing, data formats)

:robot: AI :scream: :boom: (risks & opportunities)

<br />
<br />
:::

## GeoJupyter community overview {.smaller}

### Open, participatory development

:::evenly-spaced
:revolving_hearts: User-centered & user-led

:hugs: Welcoming (like Jupyter)

:flashlight: Exploring: finding & opening hidden doors

:japanese_castle: Data & computational sovereignty

<br />
<br />
:::


## GeoJupyter community overview {.smaller}

### Partners :scientist: :teacher: :technologist:

* Maryam Hosseini - urban systems, computer vision, & open source
* Clancy Wilmott - Critical Cartography, Geovisualisation and Design
* Char Tomlinson - Earth science, GIS, vertical & volumetric landscapes
* Sarah Chasins & Parker Zeigler - cartography, CS, & open source
* Nancy Thomas & Iryna Dronova - Berkeley Geospatial Innovation Facility
* Carl Boettiger - Geospatial, AI, & education
* Benny Szeghy & Esha Potharaju - GeoJupyter interns
* Qiusheng Wu - Geospatial, AI, & education
* Friends & neighbors: BIDS, MyST, JupyterHub, earthaccess, QuantStack, DevSeed, Pangeo,
  2i2c, Clark University, Stanford, Simula, CNES, ESA


# :building_construction: Projects in the GeoJupyter community


## JupyterGIS

![A screenshot of JupyterGIS](/assets/images/jupytergis-screenshot.jpg)


## Jupyter Xarray Tiler

![A diagram of `jupyter-xarray-tiler`](/assets/images/jupyter-xarray-tiler-diagram.svg)


---

![Animation of an Xarray-computed layer with `jupytergis-tiler`](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*LoISLf6L4GKZZgl2a9jlew.gif)


## Experiment: reproducible viz -> Notebook workflows

![Reproducible workflow from viz-land to Notebook-land (:clap: Benny & Esha!)](assets/images/reproducible-viz-to-notebook-workflow.gif)


## [Future](https://github.com/geojupyter/initiatives/issues?q=sort%3Aupdated-desc%20is%3Aissue%20is%3Aopen%20label%3A%22type%3A%20initiative%22)

:::evenly-spaced
:open_book: **"Scrollytelling"**

:robot: GeoAI :thinking:

:mountain: Reproducible "geoprocessing" (following lessons learned from interns' exploration)

:art: Web symbology editing component

:teacher: Example datasets for education
:::


# :thought_balloon: Discussions &<br />:boom: Demos

## :boom: :thought_balloon: JupyterGIS

:::evenly-spaced
```bash
uv run --with jupyterlab --with jupytergis jupyter lab
```

Or, even cooler...

[:bulb: Launch from our docs with JupyterLite](https://jupytergis.readthedocs.io/en/latest/)

<br />
:::


## :thought_balloon: Reproducible viz -> Notebook workflows

![Awesome work by awesome interns](assets/images/reproducible-viz-to-notebook-workflow.gif)


## :boom: :thought_balloon: Roadmapping

:::evenly-spaced
Problem: Hard to track the many things going on and where we're going next

Goal: Roadmapping as a forum, not a static output

[Our "initiatives" GitHub repository](https://github.com/geojupyter/initiatives/)

<br />
:::


## :boom: :thought_balloon: Contributor on-ramps

:::evenly-spaced
Problem: Contributors often ask us where they can get started, it helps to know who to
talk to

Goal: Make it more intuitive for new community members to get started by self-serving
(while building human connection with them)

[Inspiration](https://antennapod.org/contribute/),
[Initiative](https://github.com/geojupyter/initiatives/issues/12),
[GitHub issue](https://github.com/geojupyter/geojupyter.org/issues/127),
[PR](https://github.com/geojupyter/geojupyter.org/pull/134),
[Preview](https://geojupyter--134.org.readthedocs.build/en/134/contribute.html)
:::



## :thought_balloon: Discussion: Funding :money_with_wings:

::::::evenly-spaced
Problem: Too much to do, never enough capacity!

:::{style="font-size: 5em"}
:ear:
:::
::::::


## :thought_balloon: Discussion: Dogfooding :dog:

::::::evenly-spaced
Problem: Want to use GeoJupyter projects internally at DSE, build cross-collaborations

:::{style="font-size: 5em"}
:ear:
:::
::::::


# :tada: Bonus slides

## Presentation timeline

* Community/project overview slides (5 minutes)
* JupyterGIS demo (5 minutes demo + 5 minutes discussion)
* Discussion: Reproducible viz -> Notebook workflows work by interns (5 minutes)
* Roadmapping (5 mins demo + 5 mins discussion)
* Contributor on-ramps (5 mins demo + 5 mins discussion)
* Discussion: Funding (15 minutes)
* Discussion: Dogfooding (5 minutes)
