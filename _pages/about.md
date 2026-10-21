---
permalink: /
title: "Quentin Bonassies, Ph.D"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a young hydrology researcher with a background in water resources engineering, hydrodynamic modeling, hydrological modeling, data assimilation, and remote sensing. I completed my <i>Ph.D in hydrology and continental surfaces</i> at <b>[CERFACS](https://www.cerfacs.fr/)</b> in Toulouse, France, in April 2026, through a collaboration with <b>[CNES](https://www.cnes.fr/)</b> and <b>[CLS](https://www.cls.fr/)</b>.

My doctoral research focused on improving flood monitoring and prediction through the assimilation of satellite observations into hydrological and hydraulic models. In particular, I investigated the potential of the <b>[Surface Water and Ocean Topography](https://swot.jpl.nasa.gov/)</b> (SWOT) mission to improve our understanding of river dynamics and flood events, with applications to flood forecasting and reanalysis. I also explored innovative data assimilation techniques, implementing the Chan-Vese segmentation method within an Extended Kalman Filter for the assimilation of flood extent images.

During my Ph.D, I spent two months at <b>NASA's [Jet Propulsion Laboratory (JPL)](https://www.jpl.nasa.gov/)</b> in Pasadena, California, working on hydrological modeling and data assimilation using the RAPID model over the Garonne basin in France.

Before my doctoral studies, I graduated from <b>[INP-ENSAT](https://www.ensat.fr/fr/index.html)</b> in 2021 with a specialization in water resources and hydrology, and worked for 1.5 years as a hydraulic engineer at <b>[Artelia](https://www.arteliagroup.com/fr/)</b> in Grenoble, France. There, I conducted hydrodynamic modeling studies of rivers, coastal areas, and marine environments using the [OpenTelemac](https://opentelemac.org/fr) modeling suite, notably for environmental impact assessments and hydraulic infrastructure design.

My research interests lie at the intersection of satellite remote sensing, hydrological and hydraulic modeling, and data assimilation. I am particularly interested in leveraging Earth observation data to improve our understanding and prediction of floods at regional and global scales.

Having completed my PhD, I am currently seeking postdoctoral opportunities and research collaborations in these fields.

For more information, please explore my research and publications or get in touch at <a href="mailto:qbonassies@gmail.com">qbonassies@gmail.com</a>.


## Featured publication

{% assign featured = site.posts
  | where: "doi", "https://doi.org/10.1016/j.rse.2025.115101"
  | first %}

{% if featured %}
<div class="publication-preview">

  <div class="publication-preview-image">
    <img src="https://quentinbns.github.io/images/graphical_abstract/bonassies_etal_2026a.jpg"
         alt="SWOT Pixel Cloud data for flood extent extraction">
  </div>

  <div class="publication-preview-text">

    <h3>
      <a href="{{ featured.url | relative_url }}">
        {{ featured.title }}
      </a>
    </h3>

    <p><em>{{ featured.venue }}</em>, {{ featured.year }}.</p>

    <p>{{ featured.excerpt }}</p>

    <p>
      <a href="{{ featured.doi }}">DOI</a> ·
      <a href="{{ featured.paperurl }}">PDF</a> ·
      <a href="{{ featured.bibtexurl }}">BibTeX</a>
    </p>

  </div>
</div>
{% endif %}

