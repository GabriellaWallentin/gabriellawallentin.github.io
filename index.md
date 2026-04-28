---
layout: default
title: ""
---

<div style="display: flex; align-items: center; gap: 15px; margin-bottom: 2rem;">
  <img src="Wallentin.jpeg" alt="Dr Gabriella Wallentin" style="width: 60px; height: 60px; border-radius: 50%; object-fit: cover;">
  <h1 style="margin: 0;">Dr Gabriella Wallentin</h1>
</div>

Welcome to my page! 
I am a postdoctoral researcher in the group of Prof. Dr Corinna Hoose. I finished my PhD on the topic of Arctic multilayer clouds in 2024 and have since continued working at KIT for a postdoctoral position within the [CleanCloud](https://projects.au.dk/cleancloud/cleancloud-project) project. My current topic is on ice nucleating particles (INPs) and their global distribution and importance for cloud ice formation on weather and climate scales.

Here you can find information on me and my projects. Please don't hesitate to [contact me](gabriella.wallentin[at]kit.edu). 
 You can also find me on [LinkedIn](https://www.linkedin.com/in/gabriella-wallentin1994/) or [ORCiD](https://orcid.org/0000-0002-7240-0498) 

<!--
<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.grid-card {
  background: #f5f5f5;
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s, box-shadow 0.2s;
}

.grid-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 12px rgba(0,0,0,0.2);
}

.grid-card a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  display: block;
}
</style>

<div class="grid-container">
  <div class="grid-card">
    <a href="/about/">About Me</a>
  </div>

  <div class="grid-card">
    <a href="/subpage2/">Subpage 2</a>
    <p>Short description of subpage 2</p>
  </div>

</div>
-->


# Research Interest

## Primary Ice Production
Ice nucleating particles (INPs) are essential for cloud ice formation, as they lower the energy barrier for the phase change from liquid to solid. In our work, we focus on improving the representation of this process, the immersion freezing of cloud droplets when INPs are present, in global models. Models intended for global simulations have to simplify parameterisations, as they become expensive to run. However, these simplifications are often at the expense of accuracy. The current immersion freezing parameterisation in the ICON-XPP (the climate model for ICON), is homogeneously defined across the globe with no allowance for regional variations in the presence of these aerosols that can act as INPs. To remedy this, in this work, we have developed an immersion freezing parameterisation driven by observed immersion-mode INPs and machine learning. An EGU abstract can be found [here](https://meetingorganizer.copernicus.org/EGU26/EGU26-12119.html). Stay tuned for the manuscript soon to be submitted!  

## Secondary Ice Production
Secondary ice production (SIP) is a hot topic within the cloud microphysics community. Observational evidence points to the occurrence of a multiplication mechanism of cloud ice, through collision and freezing processes within mixed-phase clouds. In our group, we have built up a great code base in the [ICON](https://www.icon-model.org/) model, where we can study four SIP processes, namely rime-splintering, ice-ice collision, rain drop freezing and shattering, and sublimation break-up. The first three processes have now been studied in Germany [Sullivan et al. 2018](https://acp.copernicus.org/articles/18/16461/2018/), [Han et al. 2024](https://journals.ametsoc.org/view/journals/atsc/81/5/JAS-D-23-0156.1.xml), and in the Arctic [Wallentin et al. 2025](https://acp.copernicus.org/articles/25/6607/2025/). Current work includes the evaluation of the implemented SIP in deep convective clouds over the US and Pacific [Waman et al.](https://doi.org/10.5194/egusphere-2025-6129), over Corsica (Verma, in preparation) and in Finland, where the focus is on capturing the observed rain drop freezing and shattering mechanism with ICON [Meusel et al. EGU Abstract](https://meetingorganizer.copernicus.org/EGU26/EGU26-8054.html). 


## Arctic Multilayer Clouds
Multilayer clouds (MLCs) are vertically stacked cloud layers, which may interact through microphysics and radiation. These cloud systems are often found in the Arctic region, and this project goes into a detailed modelling study to establish 1) how our weather prediction model ICOsahedral Nonhydrostatic model, [ICON](https://www.icon-model.org/) performs in the Arctic, 2) whether we can accurately model a 3-day case study of multilayer clouds and how they react to perturbations in primary and secondary ice production, 3) how widely MLCs occur across the Arctic region, 4) what their modelled and observed characteristics are from a macrophysical perspective, and 5) their microphysical and radiative interactions.

Interested in multilayer clouds and how we can model them? These publications go into detail on the microphysical, macrophysical, and thermodynamic requirements to accurately model these clouds.
How does the numerical weather prediction model ICON perform in the high Arctic? And can we model the multilayer cloud occurrence? 

* On the radiative and microphysical interactions of MLCs, stay tuned for our next paper! For a preview, have a look at our EGU 2025 Abstract [The Microphysical and Radiative Interactions of Arctic Multilayer Clouds](https://meetingorganizer.copernicus.org/EGU25/EGU25-15714.html)

* This study explores a month of simulations in the high Arctic following the MOSAiC campaign. We find a high occurrence of MLCs across the Arctic region, develop an ice nucleating particle (INP) parameterisation for Arctic autumn, and evaluate the ICON model in this extreme region. Wallentin et al 2026, [The Prevalence of Arctic Multilayer Clouds and their Observed and Modelled Characteristics](https://acp.copernicus.org/articles/26/3069/2026/)
 ![MLC Occurrence](/assets/img/Occurrence_spatial_1e-09.png)
  
* Case studies can be beneficial for a closer look at how the microphysics interacts, here is a 2-day case study that looks at the primary and secondary ice production in a multilayer cloud system
  Wallentin et al. 2025 [Sensitivities of simulated mixed-phase Arctic multilayer clouds to primary and secondary ice processes](https://acp.copernicus.org/articles/25/6607/2025/)
  ![Cloud Scene](/assets/img/MLC_paper1.png)

  For a more detailed analysis of these clouds, have a look at my PhD thesis!
* PhD Thesis: Wallentin 2025 [The Microphysical and Radiative Interactions of Arctic Multilayer Clouds](https://publikationen.bibliothek.kit.edu/1000179667)




# Publications
**First-author Papers**
  * Wallentin et al. (to be submitted) "A Data-driven Approach to Modelling a Global Distribution of Ice Nucleating Particles", [EGU 2026 Abstract](https://meetingorganizer.copernicus.org/EGU26/EGU26-12119.html)

  * Wallentin et al. (to be submitted) "The Impacts of the Seeder-Feeder Mechanism and Radiative Interactions in Arctic Mixed-phase Multilayer Clouds", Journal of Geophysical Research, Atmospheres [EGU 2025 Abstract](https://meetingorganizer.copernicus.org/EGU25/EGU25-15714.html)

  * Wallentin et al. "The prevalence of Arctic multilayer clouds and their observed and modelled characteristics", Atmos. Chem. Phys., 26, 3069–3089, https://doi.org/10.5194/acp-26-3069-2026, 2026. 

  * Wallentin et al. "Sensitivities of simulated mixed-phase Arctic multilayer clouds to primary and secondary ice processes". Atmospheric Chemistry and Physics, 25 (13), 6607–6631. doi:10.5194/acp-25-6607-2025, 2025.

  **Supervised work**
  * Verma, B., **Wallentin G.**, Barthlott, C., Hoose, C.: _Impacts of Cloud Condensation Nuclei on Orographic Secondary Ice Production over Corsica_, Atmospheric Chemistry and Physics [in preparation]
    
  * Dürlich, V., **Wallentin, G.**,  Oertel, A., Tesche, M., Achtert, P., Seelig, T., Hoose, C.: _The Thermodynamic Stability and Sources of Arctic Multilayer Clouds during MOSAiC_, [in preparation]

  **Co-authorship**
  * Waman, D., Meusel, J., Keshtgar, B., **Wallentin, G.**, Barthlott, C., Patade, S., Shete, S., Prabhakaran, T., Fievet, R., Finney, D., Blyth, A., and Hoose, C.: _Impacts of Secondary Ice Production on the Microphysics and Dynamics of Deep Convective Clouds in Different Environments_, EGUsphere [preprint], https://doi.org/10.5194/egusphere-2025-6129, 2026. 

  * Achtert, P., Seelig, T., **Wallentin, G.**, Ickes, L., Shupe, M. D., Hoose, C., and Tesche, M.: _Occurrence of seeding multi-layer clouds in the Arctic from ground-based observations_, Atmospheric Chemistry and Physics, 26, 3049–3068, https://doi.org/10.5194/acp-26-3049-2026, 2026. 


# Datasets
For fair and reproducible science, our data and scripts for producing plots and post-processing are available here:

Interested in applying our multilayer cloud algorithm to your model data? Find it [here](https://zenodo.org/records/15829738)

* [Model Data for "The Prevalence of Arctic Multilayer Clouds and their Observed and Modelled Characteristics"](https://zenodo.org/records/15829738)
* [Research data for "Sensitivities of Simulated Mixed-phase Arctic Multilayer Clouds to Primary and Secondary Ice Processes"](https://publikationen.bibliothek.kit.edu/1000180885)
* [Research Data for the PhD Thesis "The Microphysical and Radiative Interactions of Arctic Multilayer Clouds"](https://publikationen.bibliothek.kit.edu/1000180884)
  
