---
layout: archive
title: "Past projects"
permalink: /past-projects/
author_profile: true
redirect_from:
  - /past
  - /previous
---

{% include base_path %}
{% include toc %}

Flowering time in pea: a systems biology approach from the genetic network to the field
======
Pea (_Pisum sativum_) is a leguminous crop grown for human and animal consumption, whose cultivated areas are declining in Europe, particularly because of insufficient productivity. Inra has been seeking to develop a high performance winter pea, which would be characterized by a more stable and higher yield than currently grown spring and winter pea. The date of flowering is at the heart of this strategy with flower initiation is a primordial phase of development after which the plant is sensitive to environmental conditions, especially frost. The preferred approach is the manipulation of the flowering date using the different alleles known for the key flowering genes. A predictive model of the flower initiation date based on the genotype and environmental conditions, can be used to describe the ideal genotype for winter pea that would meet the needs of breeders.

<img src='/bwenden/images/Ideal-winter-pea.png' />

My thesis work aimed at developing an integrative tool combining the range of data available at different scales in the form of a mathematical model of the flowering date in pea.

<img src='/bwenden/images/Model-flowering-time.png' />

Integrated study of the circadian clock in _Arabidopsis thaliana_
======
While at the Centre for Synthetic and Systems Biology (University of Edinburgh, Scotland), I studied the circadian clock in _Arabidopsis thaliana_ through three approaches:
* **circadian clock analysis under limited light conditions**: one of the main obstacles to understanding the functioning of the circadian clock is the complexity of its interactions with environmental signals and in particular with light. In order to simplify the analysis, the components of the clock were studied under two simplified systems in Arabidopsis: (i) no light signal and (ii) under a dark red treatment strict, whose signal would be integrated by a single photoreceptor. My role was to complete the dark red data set with luciferase imaging and real-time quantitative PCRs. Our [results article published in _The Plant Journal_](https://enro.github.io/bwenden/publication/2011-Light-inputs-shape%20the-Arabidopsis-circadian-system) highlights that the nature of the light signals profoundly affects the functioning of the circadian clock.
* **study of the behavior of cell oscillators within the leaf**: one of the non-invasive methods for studying clock genes is the imaging follow-up of constructs _clock gene promoters :: Luciferase_. I was asked to replicate and improve a protocol for monitoring the luciferase signal at the level of the individual cell or cell group (picture below), and the project moved quickly towards a comparison of clock behavior between plants subjected to light cycles (12 hours of light, 12 hours of darkness) and plants grown in constant light conditions. A common assumption is that each cell clock is independent of neighboring cells and is therefore characterized by a random phase in non-synchronizing conditions. Using new Matlab image analysis scripts for data analysis (quantification of synchronization, characterization of expression patterns), as well as Simile simulation software (Simulistics), we were able to show that there is a characteristic, not random, pattern of expression for luciferase fused to clock gene promoters for untrained plants ([see publication in _PNAS_](https://bwenden.github.io/bwenden/publication/2012-Spontaneous-spatiotemporal-waves-of-gene-expression-from-biological-clocks-in-the-leaf)).

<img src="/bwenden/images/Arabidopsis-luciferase-construction.png" />

* **development of a growth model for _Arabidopsis thaliana_**: another goal has been to develop an architectural development model that can serve as a platform for analytic and visual integration of models at different scales that we have (schema below). The platform had to include a widespread programming language, model flexibility and graphic output. The GreenLab mathematical model is based on development equations for each organ and the flexibility of the language makes it suitable for any type of plant. We contacted Philippe de Refye (CIRAD, Montpellier) to set up a collaboration to adapt the latest version of GreenLab to our Arabidopsis mutants and use it as an integration platform. I made phenotypic measurements (number of leaves, fresh and dry weight, leaf area) on different mutants of the clock which made the parametrization of the model possible. The GreenLab model for Arabidopsis is developed under Matlab, which will make it easy to use as an integration platform for other models ([see publication in _PNAS_](https://bwenden.github.io/bwenden/publication/2014-Multiscale-digital-Arabidopsis-predicts-individual-organ-and-whole-organism-growth)).

<img src="/bwenden/images/Models-integration.png" />
