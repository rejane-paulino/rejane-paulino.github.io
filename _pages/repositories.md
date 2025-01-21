---
layout: archive
title: ""
permalink: /repositories/
author_profile: true
redirect_from:
  - /repositories
---

## GitHub Repositories

## [S2/3Aqua (Sentinel-2/3 Synthetic Aquatic Reflectance Bands)](https://github.com/rejane-paulino/s23aqua)<img src="/images/s23aqua.svg" width="250" align="right" />

The S2/3Aqua is a proto-algorithm that integrates spatial and spectral domains from the Sentinel-2 MSI and Sentinel-3 OLCI images using multivariate regressor models. The S2/3Aqua combines these two sensors to create a new set of synthetic multi-band products that preserve each sensor’s unique characteristics. Here, eight synthetic eight spectral bands (from visible to red-edge domains) at 10-m spatial resolution are generated, making the S2/3Aqua product suitable for addressing the challenges relating to inland waters, such as mapping of potentially harmful algal blooms and enhanced estimative of chlorophyll-a and suspended matter. This proto-algorithm contains three main steps: (1) creation of spatially degraded 10-m Sentinel-2 MSI images using a Point Spread Function; (2) selection of spectral samples across Sentinel-2/3 images using cluster-based sampling approach; and (3) generation of 10-m eight synthetic spectral bands from multivariate regressor models.























[//]: # (* **L-CONNECT &#40;river-Lake CONNECTivity&#41;**)

[//]: # (<div style="text-align: center;">)

[//]: # (  <img src='/images/lconnect.png' width='150' height='auto' alt='AWP Inland Water Image' />)

[//]: # (</div>)

[//]: # (L-CONNECT framework combines machine learning algorithms and spectral similarity features to predict water surface connectivity between floodplain lakes and their main river. The assumption is that the spectral similarity between river and lake waters is a good proxy for hydrological connectivity. This methodology applies when the main river drives the changes in the optical water properties &#40;i.e., flux of high sediment load waters&#41; of its flooding lakes. Here, hydrological connectivity means the dynamic flow interactions between large rivers during the flooding season and their floodplain lakes, which occurs by channelized and diffuse overbank flows, and affects surface water connectivity.)

[//]: # ([Link]&#40;https://github.com/rejane-paulino/lconnect&#41;)

[//]: # ()
[//]: # (Highlights of the research can be accessed [Here]&#40;https://arcg.is/10i0zX1&#41;.)

[//]: # ()
[//]: # (* **&#40;AWP - Inland Water&#41; Adaptative Window by Proportion applied to Inland Water**)

[//]: # (<div style="text-align: center;">)

[//]: # (  <img src='/images/awpinlandwater.png' width='150' height='auto' alt='AWP Inland Water Image' />)

[//]: # (</div>)

[//]: # (AWP-Inland Water is a proto-algorithm that has been developed to address the reduction of adjacency effect on satellite-imagery applied to small waterbodies. The key principle behind AWP-Inland Water lies in its ability to adapt window-ranges according to local conditions across the waterbodies. For more details about this proto-algorithm, we recommend referring to the comprehensive study conduced by Paulino et al. &#40;2022&#41;.)

[//]: # ([Link]&#40;https://github.com/rejane-paulino/awp-inlandwater&#41;)
