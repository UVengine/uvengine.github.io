---
title: 
feature_text:
feature_image: "assets/uvengine_label_fondo.png"
excerpt: "UVengine is a universal variability resolution engine for [UVL](https://universal-variability-language.github.io/) with [Jinja templates](https://jinja.palletsprojects.com/en/stable/)."
---

*UVengine* is a universal variability resolution engine for [UVL](https://universal-variability-language.github.io/) models and text-based artifacts with [Jinja templates](https://jinja.palletsprojects.com/en/stable/).

{% include button.html text="Try it online 🏷️" link="webapp/" color="#11b786" %} {% include button.html text="View it on GitHub" icon="github" link="https://github.com/UVengine/uvengine" color="#555555" %}

### Overview

Inputs and outputs of UVengine.

<img src="assets/uvengine_overview.png" alt="UVengine overview"/>

### Features

- A variability resolution engine for [UVL](https://universal-variability-language.github.io/) models.
- Support all [language level extensions of UVL](https://doi.org/10.1016/j.jss.2024.112326).
- Feature traceability between UVL models and implementation artifacts.
- Language independence for any text-based artifacts using [Jinja templates](https://jinja.palletsprojects.com/en/stable/).
- Composition and annotation-based mechanisms to implement variability at different degrees of granularity.
- Easy integration with existing tools of the [UVL ecosystem]() such as [UVLS](https://marketplace.visualstudio.com/items?itemName=caradhras.uvls-code) and [flamapy](https://www.flamapy.org/).


### Publications using the UVengine approach

- José Miguel Horcas, Mercedes Amor, Lidia Fuentes. *The Kubernetes variability model*. 19th International Working Conference on Variability Modelling of Software-Intensive Systems (VaMoS). 2025. DOI: <a href="https://doi.org/10.1145/3715340.3715440">https://doi.org/10.1145/3715340.3715440</a>
<button type="button" onclick="copyBibTeX(bibtexEntry4)">Copy BibTex 🗎</button>

- David Romero Organvidez, José Miguel Horcas, José A. Galindo, David Benavides. *Data visualization guidance using a software product line approach*. Journal of Systems and Software (JSS). 2024. DOI: <a href="https://doi.org/10.1016/j.jss.2024.112029">https://doi.org/10.1016/j.jss.2024.112029</a>
<button type="button" onclick="copyBibTeX(bibtexEntry3)">Copy BibTex 🗎</button>

- David Romero Organvidez, David Benavides, José Miguel Horcas, María Teresa Gómez López. *Variability in data transformation: towards data migration product lines*. 18th International Working Conference on Variability Modelling of Software-Intensive Systems (VaMoS). 2024. DOI: <a href="https://doi.org/10.1145/3634713.3634724">https://doi.org/10.1145/3634713.3634724</a>
<button type="button" onclick="copyBibTeX(bibtexEntry2)">Copy BibTex 🗎</button>

- José Miguel Horcas, José A. Galindo, David Benavides. *Variability in data visualization: a software product line approach*. 26th ACM International Systems and Software Product Line Conference (SPLC). 2022. DOI: <a href="https://doi.org/10.1145/3546932.3546993">https://doi.org/10.1145/3546932.3546993</a>
<button type="button" onclick="copyBibTeX(bibtexEntry1)">Copy BibTex 🗎</button>


### Entities involved

<a href="https://www.uma.es/"><img src="assets/uma.svg" alt="Universidad de Málaga" width="200"/></a>

<script>
 // Store the BibTeX entry in a JavaScript variable
  {% raw %}
  const bibtexEntry3 = `
@article{RomeroOrganvidez2024_DataVisualizationSPL,
  author       = {David Romero{-}Organvidez and Jos{\'{e}} Miguel Horcas and Jos{\'{e}} A. Galindo and David Benavides},
  title        = {Data visualization guidance using a software product line approach},
  journal      = {J. Syst. Softw.},
  volume       = {213},
  pages        = {112029},
  year         = {2024},
  url          = {https://doi.org/10.1016/j.jss.2024.112029},
  doi          = {10.1016/J.JSS.2024.112029},
  timestamp    = {Tue, 18 Jun 2024 01:00:00 +0200},
  biburl       = {https://dblp.org/rec/journals/jss/RomeroOrganvidezHGB24.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}

    {% raw %}
  const bibtexEntry4 = `
@inproceedings{Horcas2025_KubernetesFM,
  author       = {Jos{\'{e}} Miguel Horcas and
                  Mercedes Amor Pinilla and
                  Lidia Fuentes},
  title        = {The Kubernetes variability model: Synthesizing variability from the
                  K8s {API} Documentation: {A} case study},
  booktitle    = {19th International Working Conference on Variability
                  Modelling of Software-Intensive Systems ({VaMoS})},
  address      = {Rennes, France},
  month        = {Feb},
  pages        = {58--67},
  publisher    = {{ACM}},
  year         = {2025},
  url          = {https://doi.org/10.1145/3715340.3715440},
  doi          = {10.1145/3715340.3715440},
  timestamp    = {Fri, 30 May 2025 11:26:47 +0200},
  biburl       = {https://dblp.org/rec/conf/vamos/HorcasPF25.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}

    {% raw %}
  const bibtexEntry2 = `
@inproceedings{RomeroOrganvidez2024_DataTransformationVariability,
  author       = {David Romero{-}Organvidez and David Benavides and Jos{\'{e}} Miguel Horcas and Mar{\'{\i}}a Teresa G{\'{o}}mez{-}L{\'{o}}pez},
  title        = {Variability in data transformation: towards data migration product lines},
  booktitle    = {18th International Working Conference on Variability Modelling of Software-Intensive Systems ({VaMoS})},
  year         = {2024},
  url          = {https://doi.org/10.1145/3634713.3634724},
  doi          = {10.1145/3634713.3634724},
  timestamp    = {Fri, 26 Jan 2024 00:00:00 +0100},
  biburl       = {https://dblp.org/rec/conf/vamos/Romero-Organvidez24.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}

    {% raw %}
  const bibtexEntry1 = `
@inproceedings{Horcas2022_DataVisualizationVariability,
  author       = {Jos{\'{e}} Miguel Horcas and Jos{\'{e}} A. Galindo and David Benavides},
  title        = {Variability in data visualization: a software product line approach},
   booktitle    = {26th {ACM} International Systems and Software Product Line Conference ({SPLC})},
  pages        = {55--66},
  publisher    = {{ACM}},
   volume    = {A},
  year         = {2022},
    address   = {Graz, Austria},
  month     = sep,
  url          = {https://doi.org/10.1145/3546932.3546993},
  doi          = {10.1145/3546932.3546993},
  timestamp    = {Mon, 26 Jun 2023 20:46:40 +0200},
  biburl       = {https://dblp.org/rec/conf/splc/HorcasG022.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}

  function copyBibTeX(bibtexEntry) {
      // Create a temporary textarea to hold the BibTeX entry
      const tempTextarea = document.createElement("textarea");
      tempTextarea.value = bibtexEntry;
      document.body.appendChild(tempTextarea);

      // Select and copy the text
      tempTextarea.select();
      document.execCommand("copy");

      // Remove the temporary textarea
      document.body.removeChild(tempTextarea);
  }
</script>
