# Overview of Mission Atlantic Coding Resources

## Introduction

MISSION ATLANTIC is a Horizon 2020 project that will improve our understanding of Atlantic Ocean ecosystems and drivers of change that impact marine biodiversity and ocean resources, through the development of the Integrated Ecosystems Assessments. 

An Integrated Ecosystem Assessment (IEA) is a framework for implementing ecosystem based management, used to organise scientific findings and inform decision-making. It involves an iterative process of combined environmental and socioeconomic data to provide a comprehensive view of the entire system, as well as the participation of stakeholders to identify relevant management objectives. An IEA involves a five-step process:

1. **Scope** of key management objectives, human activities and the ecosystem components affected by them.
2. **Indicators** development to assess the status, drivers and resilience of the ecosystem.
3. **Risk analyses** that involve the present impacts and future changes.
4. **Scenario testing** under various scenarios of climate change, resource exploitation and social development using end-to-end ecosystem models.
5. **Refine** to achieve desired outcomes, by reflecting the needs and trade-offs.

This repository (readme) file provides an overview of Mission Atlantic resources that are currently stored in this **or other repositories**. Instead of forking the full repository (and being quickly outdated), we can provide a link to other repositories.

### Coding resources and tools



- [**R Data retrieval from OBIS & GBIF**](https://github.com/missionatlantic/obis_gbif_tutorial) 

  A short tutorial to download biodiversity data from [OBIS](https://obis.org/) and [GBIF](https://www.gbif.org/). The tutorial downloads occurrence data for multiple species.
  
  
- [**Standardisation of LOKI data from Ecotaxa into Darwin Core**](https://github.com/missionatlantic/Plankton_IEAPM_Brazil) 

  A short tutorial to standardize LOKI data exported from Ecotaxa into Darwin Core (https://dwc.tdwg.org/).
  
  
- [**GAM-NICHE**](https://gam-niche.azti.es/)

   A tool to build species distribution models (SDMs) under the ecological niche theory framework, using Shape-Constrained Generalized Additive Models (SC-GAMs). It includes a short R tutorial, code and an [online book](https://fundacion-azti.github.io/gam-niche/).
Cite the book as:

  <p><img src="https://gam-niche.azti.es/wp-content/uploads/2023/05/logo_gam_niche_web.jpg" width="150" align="right"></p>

    > <h6>Valle, M., Citores, L., Ibaibarriaga, L., Chust, C. (2023) GAM-NICHE: Shape-Constrained GAMs to build Species Distribution Models under the ecological niche theory. AZTI. https://doi.org/10.57762/fzpy-6w51<h6>
    
    
- [**Pan-Atlantic 3D distribution model incorporating water column for commercial fish.**](https://github.com/missionatlantic/3D_SDMs_AtlanticFish)

   Repository for code and generated data for " Pan-Atlantic 3D distribution model incorporating water column for commercial fish " by Mireia Valle, Eduardo Ramirez-Romero, Leire Ibaibarriaga, Leire Citores, Jose A. Fernandes-Salvador, and Guillem Chust, published in Ecological Modelling journal (2024):

    > <h6>Valle, M., E. Ramírez-Romero, L. Ibaibarriaga, L. Citores, J. A. Fernandes-Salvador, and G. Chust. 2024. Pan-Atlantic 3D distribution model incorporating water column for commercial fish. Ecological Modelling 490:110632. https://doi.org/10.1016/j.ecolmodel.2024.110632<h6>
    
  
- [**Plankton Lifeform Extraction Tool (PLET)**](https://www.dassh.ac.uk/lifeforms/)

  The Plankton Lifeform Extraction Tool brings together disparate European plankton datasets into a central database from which it extracts abundance time series of plankton functional groups, called “lifeforms”, according to shared biological traits. This tool has been designed to make complex plankton datasets accessible and meaningful for policy, public interest, and scientific discovery.
  
  > <h6>Ostle, C., Paxman, K., Graves, C.A., Arnold, M., Artigas, F., Atkinson, A., Aubert, A., Baptie, M., Bear, B., Bedford, J. and Best, M., 2021. The Plankton Lifeform Extraction Tool: a digital tool to increase the discoverability and usability of plankton time-series data. Earth System Science Data Discussions, 2021, pp.1-73.https://doi.org/10.5194/essd-13-5617-2021<h6>
 
 - [**geomorph_deep**](https://github.com/BrandonHobley/geomorph_deep)

    A coding resource used to run Convolutional neural networks for segmenting seabed morphological classes https://github.com/BrandonHobley/geomorph_deep.
  
  
 - [**Broad-scale benthic habitat classification of the South-Atlantic**](https://github.com/DeepSeaCRU/South-Atlantic-Benthic-Habitat-Classification). 

   The code and files contained in this repository support replication of a broad-scale benthic habitat classification of the South Atlantic produced by McQuaid et al. (2023). We used statistical clustering algorithms to classify broad-scale (10km2) environmental data into distinct habitat classes, which reflect variation in physical conditions and we assume support distinct biological communities. Cite classification as:

   > <h6>McQuaid K. A. Bridges A. E. H., Howell K. L., Gandra T. B. R., de Souza V., Currie J. C., Hogg O. T., Pearman T. R. R., Bell J. B. B., Atkinson L. J., Baum D., Bonetti J., Carranza A., Defeo O., Furey T., Gasalla M. A., Golding N, Hampton S. L., Horta S., Jones D. O. B., Lombard A. T., Manca E., Marin Y., Martin S., Mortensen P., Passdore C., Piechaud N., Sink K. J. & Yool A. 2023. Broad-scale benthic habitat classification of the South Atlantic. Progress in Oceanography. DOI: https://doi.org/10.1016/j.pocean.2023.103016.<h6>
  

- The R scripts to generate timeseries plots in the Norwegian Case Study: https://github.com/ices-eg/WGINOR (more specifically [here](https://github.com/ices-eg/WGINOR/blob/8b4277a9c4fd035837f8945bdebbda6410fb94eb/TAF_ATAC/utilities.R#L58) )


- [**INDperform**](https://saskiaotto.github.io/INDperform)
  <p><img src="https://github.com/saskiaotto/INDperform/raw/master/man/figures/logo.png" align="right" height="100">

  Finding suitable ecological state indicators is challenging and cumbersome in stochastic and complex ecological systems. [INDperform](https://github.com/saskiaotto/INDperform) is an R package for validating the performance of ecological state indicators and assessing the ecological status based on a suite of indicators. The performance evaluation addresses the sensitivity and robustness of indicators. 
  
  > <h6>Otto, S.A., Kadin, M., Casini, M., Torres, M.A., Blenckner, T. (2018): A quantitative framework for selecting and validating food web indicators. Ecological Indicators, 84: 619-631, doi: https://doi.org/10.1016/j.ecolind.2017.05.045<h6>


- [**Ecorisk**](https://github.com/missionatlantic/ecorisk)

  The ecorisk package will be published under [this repository](https://github.com/HeleneGutte/ecorisk) soon. The ecorisk R package is designed to perform and analyse (ecosystem) risk assessments.
  
  

- [**Mission Atlantic RISK analysis**](https://github.com/missionatlantic/MissionAtlantic-RISK-Analysis). 

  Script for performing the Mission Atlantic RISK Analysis. Adapted from the ODEMM ('Options for Delivering Ecosystem-Based Marine Management') approach. Further details in:
  
  > <h6>Pedreschi, D., Niiranen, S., Skern-Mauritzen, M. and Reid, D.G., 2023. Operationalising ODEMM risk assessment for Integrated Ecosystem Assessment scoping: Complexity vs. manageability. Frontiers in Marine Science, 9, p.1037878. https://doi.org/10.3389/fmars.2022.1037878<h6>


- [**SS-DBEM**](https://doi.org/10.5281/zenodo.7548113)

  The size-spectrum species-based Dynamic Bioclimate Envelope ([**SS-DBEM**](https://doi.org/10.5281/zenodo.7548113)) (Version 1) that was used in a WP3 - related paper: https://doi.org/10.5281/zenodo.7548113. Cite as:

  > <h6>Fernandes-Salvador, Jose Antonio, & Cheung, William W. L. (2023). Code of size-spectrum species-based Dynamic Bioclimate Envelope Model (SS-DBEM) (Version 1). Zenodo. https://doi.org/10.5281/zenodo.7548113<h6>
    
    <p><img src="https://www.marineresourcemodelling.maths.strath.ac.uk/strathe2e/logo.svg" align="right" height="110"> 
    
- [**StrathE2E**](https://www.marineresourcemodelling.maths.strath.ac.uk/strathe2e/index.html)

  A marine end-to-end ecosystem model and R package. The aim is to represent the entire interconnected marine ecosystem (from physics and chemistry, to whales and fisheries in continental shelf regions) by exploring 'what if' experiments and explore uncertainty. View the [application](https://outreach.mathstat.strath.ac.uk/apps/StrathE2EApp/),
the [website](https://www.marineresourcemodelling.maths.strath.ac.uk/strathe2e/index.html) or the latest [publication](https://doi.org/10.1111/2041-210X.13510).


  
  
- [**IEAtools**](https://github.com/missionatlantic/IEAtools)

  An R Package that provides supporting functions for conducting Integrated Ecosystem Assessments (IEA), developed in the framework of Mission Atlantic. The package includes methods for data exploration and assessment of the current ecosystem status. [Forked repository in Mission Atlantic](https://github.com/missionatlantic/IEAtools). For latest version, check the [original repository](https://github.com/saskiaotto/IEAtools).
  


---
<img src="https://d33wubrfki0l68.cloudfront.net/3c7a986788206cd92394530e349a3a7c1ac17036/bcbea/logo.png" alt="drawing" width="250"/>

<table>
  <tr>
<td><img src="https://d33wubrfki0l68.cloudfront.net/8a5238b8d18dd86c0b02e452f791716943f9b30d/58bd9/eu-flag.png" alt="drawing" width="200" style="vertical-align:middle"/></td>
    <td> This project has received funding from the European Union's Horizon 2020 research and innovation programme under Grant Agreement No 862428 (MISSION ATLANTIC). This output reflects only the author's view and the Research Executive Agency (REA) cannot be held responsible for any use that may be made of the information contained therein.</td>
      </tr>
      </table>
      
