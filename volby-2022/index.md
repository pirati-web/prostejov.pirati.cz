---
layout: communal-elections
title: Odvaha změnit Prostějov
heroBgImg: img/articles/2022/Pv-silueta-bez-textu2.jpg
campaignGroupUid: volby-2022
campaignCategoryUid: kraj2022
candidateListUid: kraj2022
hideCandidateSocialProfiles: true
# customizeHeader: true
---
{% assign candidates = site.candidatelists | where: "uid", page.candidateListUid | first %}
<!-- {% capture mainContent %}
  <h1 class="head-alt-lg md:head-alt-xl text-center">Komunální volby 2022</h1>
{% endcapture %} -->

<!-- {% capture subContent %}
  <h2 class="head-alt-base md:head-alt-md mt-2 text-center">Šance <strong>změnit budoucnost</strong></h2>
{% endcapture %} -->

<!-- {% include elections-header.html img=page.img bgImg=page.heroBgImg mainContent=mainContent subContent=subContent candidateListNumber=candidates.number %} -->

<h2 class="head-alt-base md:head-alt-md mt-2">Komunální volby 2022</h2>
<div class="mt-4 md:mt-8 space-y-4">
  {% include buttons/icon.html icon="ico--chevron-right" href="/volby-2020/kodex-zastupitele-2022.pdf" cta="Kodex kandidáta" class="btn--blue-300 btn--hoveractive btn--fullwidth md:btn--autowidth text-lg" %}
</div>
