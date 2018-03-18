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

Flowering time in pea: a systems biology approach from the genetic network to the field
======
Pea (_Pisum sativum_) is a leguminous crop grown for human and animal consumption, whose cultivated areas are declining in Europe, particularly because of insufficient productivity. Inra has been seeking to develop a high performance winter pea, which would be characterized by a more stable and higher yield than currently grown spring and winter pea. The date of flowering is at the heart of this strategy with flower initiation is a primordial phase of development after which the plant is sensitive to environmental conditions, especially frost. The preferred approach is the manipulation of the flowering date using the different alleles known for the key flowering genes. A predictive model of the flower initiation date based on the genotype and environmental conditions, can be used to describe the ideal genotype for winter pea that would meet the needs of breeders.

<img src='https://enro.github.io/bwenden/images/Ideal-winter-pea.png' />

My thesis work aimed at developing an integrative tool combining the range of data available at different scales in the form of a mathematical model of the flowering date in pea.

<img src='https://enro.github.io/bwenden/images/Model-flowering-time.png' />

Integrated study of the circadian clock in _Arabidopsis thaliana_
======
While at the Centre for Synthetic and Systems Biology (University of Edinburgh, Scotland), I studied the circadian clock in _Arabidopsis thaliana_ through three approaches:
* circadian clock analysis under limited light conditions: one of the main obstacles to understanding the functioning of the circadian clock is the complexity of its interactions with environmental signals and in particular with light. In order to simplify the analysis, the components of the clock were studied under two simplified systems in Arabidopsis: (i) no light signal and (ii) under a dark red treatment strict, whose signal would be integrated by a single photoreceptor. My role was to complete the dark red data set with luciferase imaging and real-time quantitative PCRs. Our results article published in _The Plant Journal_ highlights that the nature of the light signals profoundly affects the functioning of the circadian clock.
* study of the behavior of cell oscillators within the leaf: one of the non-invasive methods for studying clock genes is the imaging follow-up of gene promoter constructs of the :: Luciferase clock. I was asked to replicate and improve a protocol for monitoring the luciferase signal at the level of the individual cell or cell group. Throughout 2009, I developed a protocol to obtain this monitoring on 4-5 cycles, under microscope (Figure 6) or in culture cabinet to study up to 24 plants.
The project moved quickly towards a comparison of the behavior of the clocks between plants subjected to cycles of light training (12 hours of light, 12 hours of darkness) and plants not driven, that is to say cultivated in constant light conditions. A common assumption is that each cell clock is independent of neighboring cells and is therefore characterized by a random phase in non-synchronizing conditions. I was able to show that there was a characteristic, not random, pattern of expression for luciferase fused to clock gene promoters for untrained plants.
In order to confirm my observations, I performed many tests and obtained a large number of imaging data for several genes under different conditions. I developed new Matlab image analysis scripts to systematically gather data in space - on the surface of the sheet - and over time. In collaboration with a doctoral student from Ramon Grima's modeling team (CSBE, Edinburgh), I explored new avenues for data analysis (quantification of synchronization, characterization of expression patterns). I also started modeling approaches using Simile simulation software (Simulistics) to test different hypotheses about the mechanisms controlling these expression profiles. An article gathering this data, intended for PNAS, is being written [6].

<img src="/images/Arabidopsis-luciferase-construction.png" />

* 3.4 Development of a growth model for Arabidopsis thaliana
Within the new team, my goal has been to develop an architectural development model that can serve as a platform for analytic and visual integration for models at different scales that we have (Figure 5). The specification therefore included a widespread programming language, model flexibility and graphic output. In the first place, I became interested in the empirical model developed in E. Coen and P. Prusinkiewic (Mundermann et al., 2005) who had the advantage of offering a very realistic graphical output and of which I knew the L-Studio language. However, this architectural model proved too rigid and it was abandoned.
In structure-function models, the 3D representation derives directly from the physiological functioning of the plant. The size of the organs depends on the production and distribution of the biomass. The GreenLab mathematical model is based on development equations for each organ and the flexibility of the language makes it suitable for any type of plant. We contacted Philippe de Refye (CIRAD, Montpellier) to set up a collaboration to adapt the latest version of GreenLab to our Arabidopsis mutants and use it as an integration platform. I made phenotypic measurements (number of leaves, fresh and dry weight, leaf area) on different mutants of the clock which made it possible to begin the parametrization of the model. This new version allows in particular to include the intra-population variability in the simulations and its description will be published in the next six months. The GreenLab model for Arabidopsis is developed under Matlab, which will make it easy to use as an integration platform for other models (Figure 5).
