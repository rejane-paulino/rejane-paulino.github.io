---
layout: archive
title: ""
permalink: /repositories/
author_profile: true
redirect_from:
  - /repositories
---

## GitHub Repositories

<script src="https://cdn.jsdelivr.net/npm/showdown/dist/showdown.min.js"></script>
<div id="repo-readme"></div>

<script>
  const username = "rejane-paulino";
  const repository = "repository";

  // Initialize Showdown converter
  const converter = new showdown.Converter();

  // Fetch README from GitHub API
  fetch(`https://api.github.com/repos/${rejane-paulino}/${aerocscan}/readme`, {
    headers: { Accept: "application/vnd.github.v3.raw" }
  })
    .then(response => response.text())
    .then(data => {
      // Convert Markdown to HTML
      const htmlContent = converter.makeHtml(data);
      document.getElementById("repo-readme").innerHTML = htmlContent;
    })
    .catch(err => console.error("Error fetching README:", err));
</script>



























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
