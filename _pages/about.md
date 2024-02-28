---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


Guided by Professor [Eric Miller](https://civmin.utoronto.ca/home/about-us/directory/professors/eric-miller/), I am a postdoctoral fellow at the [Mobility Network](https://www.mobilitynetwork.utoronto.ca/), *Department of Civil and Mineral Engineering, University of Toronto*. I earned my Bachelor's in Traffic Engineering from *Beijing Jiaotong University* (北京交通大学) in 2018 and my PhD in Transportation Engineering from *Tongji University* (同济大学) in 2024. Between 2022 and 2023, I also served as a visiting Researcher at the *University of Waterloo*, supervised by Professors [Liping Fu](https://uwaterloo.ca/civil-environmental-engineering/profile/lfu) and [Chris Bachmann](https://uwaterloo.ca/civil-environmental-engineering/profile/c2bachma).

Addressing the formidable challenge of effectively mitigating traffic congestion in metropolitan cities, my doctoral dissertation focuses on leveraging passenger electric vehicles in Shanghai, along with their extensive, continuous trajectories. I introduced a novel methodology to conceptualize and assess the adjustability of vehicle trips, and pioneered differential and targeted strategies for managing vehicle travel demand, grounded in an advanced route choice model. This research was conducted under the supervision of Professors [Xiaohong Chen](https://www.researchgate.net/profile/Xiaohong-Chen-5) and [Quan Yuan](https://www.researchgate.net/profile/Quan-Yuan-40).

My research focuses on creating sustainable, advanced urban transportation systems and communities. It involves **analyzing individual travel behavior**, **modeling travel demand**, and **studying transportation-land use interactions**. I specialize in urban analytics, utilizing GIS, big data, spatial and econometric modeling, machine learning, and **freight and logistics activities are my primary interests**.



# 📖 Educations
- *2022.07 - 2023.12*, Visiting Researcher, University of Waterloo, Canada.
- *2018.09 - 2024.01*, Doctor, Tongji University, China.
- *2018.04 - 2018.06*, Visiting Student, University of Maryland, USA.
- *2016.07 - 2016.08*, Visiting Student, University of California, Berkeley, USA.
- *2014.09 - 2018.06*, Undergraduate, Beijing Jiaotong University, China.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ITSC</div><img src='images/ITSC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-scenario Route Choice Modeling Based on Random Parameters Multinomial Logit Model with Heterogeneity in Means and Variance](https://ieeexplore.ieee.org/document/10422380)

Quan Yuan, Ruixu Pan, **Jihao Deng** (Corresponding Author), Tianhao Li, Xiaohong Chen

- Travel demand management (TDM) strategies have been widely adopted to tackle the persisting traffic congestion in metropolitan areas. To evaluate the effects of TDM strategies, it is imperative to disentangle the dynamics of individual travel behaviors, usually through developing route choice models. Based on long-term trajectory data from passenger vehicles, this study investigates individual route characteristics, travel features, and traveler attributes, to explore route choice behaviors for respectively morning and evening travel during weekdays. By categorizing the choice set of each trip into five alternatives based on different routing strategies, we propose a new route choice model that accounts for route overlap and incorporates random parameter heterogeneity in means and variances. This model demonstrates superior fitting performance compared to Path-Size Multinomial Logit and Mixed Logit models. Furthermore, our findings reveal temporal disparities in route choice behavior, providing valuable insights for the implementation of personalized measures that aim at guiding travelers to change their departure time or modify their route choices.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">International Journal of Digital Earth</div><img src='images/IJDE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Who are on the road? A study on vehicle usage characteristics based on one-week vehicle trajectory data](https://www.tandfonline.com/doi/full/10.1080/17538947.2023.2218117)

**Jihao Deng**, Yiqing Cui, Xiaohong Chen, Chris Bachmann, Quan Yuan

- Understanding the characteristics of passenger vehicle use is the prerequisite for effective urban management. However, it has been challenging in the existing literature due to the lack of continuously observed data on passenger vehicle use. Thanks to the advances in data collection and processing techniques, multi-day vehicle trajectory data generated from volunteered passenger cars provide new opportunities for examining in depth how people travel in regular patterns. In this paper, based on a week's operation data of 6600 passenger cars in Shanghai, we develop a systematic approach for identifying trips and travel purposes, and classify vehicles into four categories using a Gaussian-Mixed-Model. A new method is proposed to identify vehicle travel regularities and we use the Z Test to explore differences in travel time and route choices between four types of vehicles. We find that commercially used vehicles present high travel intensity in temporal and spatial aspects and the use intensity in elevated roads is higher for household-used commuting vehicles than semi-commercially used vehicles. The methodologies and conclusions of this paper may provide not only theoretical support for future urban traffic prediction, but also guidance for employing customized active traffic demand management measures to alleviate traffic congestion. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Public Transportation</div><img src='images/JPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Financial sustainability versus social equity: Design and performance of a hybrid city bus system](https://www.sciencedirect.com/science/article/pii/S1077291X2300005X)

**Jihao Deng**, Peng Chen, Xiaohong Chen, Tianhao Li, Quan Yuan

- Many city bus systems have gone through crises - dropping ridership and unsustained finance - across countries over the past decades. Previous studies revealed that despite the soaring public subsidies on traditional bus services, the quality of bus services was unimproved and the responses to demand changes remained sluggish. A large number of bus users were, consequently, shifted to other transport modes, leading to a steady ridership decline which further worsens transit agencies’ financial condition. To deal with the dilemma, we integrate market-based customized bus services (MCBSs) into the traditional bus systems and propose a hybrid city bus model. Using data from Shanghai, China, we found that the MCBS had effectively responded to changing demand and achieved substantial ridership growth, maintained a healthy financial status, and provided social benefits to the transportation system. The success of MCBSs in Shanghai proves that the public transit system still has great potential and could be demand-responsive and financially sustainable at the same time. In the meantime, MCBSs have significantly helped improve transport equity in suburban areas. The hybrid city bus model can serve as a reference for different cities to reorganize their bus systems and regain the popularity, vitality, and social equity of bus services. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Transportation</div><img src='images/Transportation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taking the same route every day? An empirical investigation of commuting route stability using personal electric vehicle trajectory data](https://link.springer.com/article/10.1007/s11116-023-10377-1)

**Jihao Deng**, Lei Gao, Xiaohong Chen, Quan Yuan

- Traffic congestion has caused great concern among policymakers in large cities around the world. In contrast with constantly increasing transport supply, individual-based active travel demand management (ATDM) has been proposed as a more efficient policy alternative for combating congestion. However, how individuals make routing choices during commuting in response to ATDM incentives is still largely unknown, given the lack of individual travel data. Using a desensitized one-week travel trajectory data set involving 5641 personal electric vehicles, we examine the major influencing factors of commuting route stability during working days and make suggestions on targeting the most responsive commuters. We first filter family-used vehicles by clustering vehicle usage patterns through employing the Gaussian mixture model and interpret drivers’ route choice behaviors during morning peak hours. To look for factors affecting route stability, we develop a generalized additive model and find that route stability is significantly associated with road network density of origins and destinations, departure time, travel duration, commuting distance, reliability of the expressway, and volatility of the congested sections by which the routes passed. The empirical results may contribute to the understanding of individual route choices, and help urban managers develop more refined ATDM policies to alleviate traffic congestion in the future. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Beijing Jiaotong University</div><img src='images/北交大学报.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Integrated design of station sites and network of bus microcirculation system in open communities (开放式小区公交微循环站点与线网综合设计)](https://jdxb.bjtu.edu.cn/EN/10.11860/j.issn.1673-0291.20190071)

**Jihao Deng**, Rui Song, Xiaohong Chen, Tianshi Wang, Baihao Wang

- Bus microcirculation system is an effective solution to the “last mile problem” of urban traffic. Under the current background of building open communities, an integrated design of station site and network is of great significance for passengers, enterprises and society. A model is designed to decide the station sites and network of bus microcirculation system in open communities, where the goal is to minimize total distance of bus driving and passenger walking, and the constraints include the number of stations in demand, station spacing and line length, etc. Genetic algorithm is utilized to solve the model. A community in Beijing is taken as the example, and the results verifies whether the proposed model and algorithm are correct and valid. Finally, the reasonable model parameters and the number of lines are decided after the sensitivity analysis is conducted, which show that planners should take into account the interests of both enterprises and passengers, thus making the optimal decision.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Transport Geography</div><img src='images/JTG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Footprints of goods movements: Spatial heterogeneity of heavy-duty truck activities and its influencing factors in the urban context](https://www.sciencedirect.com/science/article/pii/S0966692323002090)

Zhiwei Yang, Xiaohong Chen, **Jihao Deng**, Tianhao Li, Quan Yuan

- Heavy-duty trucks have caused growing concern due to their negative environmental externalities. Existing studies have not adequately examined the heterogeneity in the spatial distribution of heavy-duty truck activities and identified major influencing factors behind the patterns, thus making effective traffic management difficult. This study extracts heavy-duty truck activities information from long-term trajectory data, and clarifies the mechanism in which heavy-duty truck activities are subject to various industrial, transportation, and land use factors by developing global and local regression models. The results of the Global Ordinary Least Squares and Multiscale Geographically Weighted Regression models indicate that heavy-duty truck activities are driven not only by the location of industrial and freight hubs, but also by the availability of truck service infrastructure such as road networks and parking spaces. Moreover, the way these factors impact on heavy-duty truck activities differ across places. Local authorities therefore should evaluate the dynamic relationship between land use development and heavy-duty truck activities and mitigate the negative impacts of such activities on urban life. Locally tailored traffic management policies on heavy-duty truck will be helpful.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings</div><img src='images/Findings.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Integrating Affordable Housing with Transit: Where are the Transit Deserts?](https://findingspress.org/article/17244-integrating-affordable-housing-with-transit-where-are-the-transit-deserts)

Peng Chen, **Jihao Deng**

- This study analyzed transit deserts in Seattle using spatial principal component analysis. We ranked factors related to transit deserts and incorporated the spatial and temporal features of transit services. We found that transit access was the main factor that contributed to transit deserts. We identified clustered and scattered transit deserts. The clustered ones were in dense areas outside of transit corridors, and the scattered ones were located across low-density areas. These findings imply that transit planning and affordable housing should be integrated, and that micro-transit can fulfill the mobility needs of people living in transit deserts.
</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**



