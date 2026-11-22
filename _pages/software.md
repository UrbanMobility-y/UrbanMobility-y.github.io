---
permalink: /software/
title: "Software & Data"
author_profile: true
---

<style>
.sd-note{font-size:.9em;color:#555}
.sd-card{display:flex;gap:1.4em;align-items:flex-start;border:1px solid #e1e4e8;border-radius:4px;padding:1.1em 1.2em;margin:1em 0 2em}
.sd-card img{width:300px;flex:0 0 300px;border:1px solid #eee}
.sd-card h3{margin:0 0 .4em}
.sd-card p{margin:.3em 0;font-size:.92em;line-height:1.55}
.sd-meta{color:#666;font-size:.85em!important}
.sd-btn{display:inline-block;font-size:.72em;padding:.05em .6em;margin:.3em .35em 0 0;border:1px solid #c8ccd0;border-radius:3px;color:#333;text-decoration:none}
.sd-btn:hover{background:#f3f4f6;text-decoration:none}
table.sd-tab{width:100%;border-collapse:collapse;font-size:.88em;display:table}
table.sd-tab th{text-align:left;border-bottom:2px solid #d0d7de;padding:.45em .5em;background:none}
table.sd-tab td{border-bottom:1px solid #e5e5e5;padding:.55em .5em;vertical-align:top;line-height:1.5}
table.sd-tab td.s{width:52%}
.sd-j{color:#666}
ul.sd-list li{font-size:.92em;line-height:1.55;margin-bottom:.6em}
@media (max-width:700px){.sd-card{flex-direction:column}.sd-card img{width:100%;flex-basis:auto}}
</style>

<p class="sd-note">Code is released under the MIT License and data under CC BY 4.0, unless stated otherwise.</p>

<h2 id="software">Software</h2>

<div class="sd-card">
<a href="https://github.com/UrbanMobility-y/WalkGeoAI"><img src="/images/research/2026_ceus_walkgeoai.jpg" alt="WalkGeoAI workflow and outputs" loading="lazy"></a>
<div>
<h3>WalkGeoAI</h3>
<p>Open-source software that estimates within-city relative pedestrian activity on every street segment from seven global open datasets. A pretrained gated graph convolutional network completes the road network without local labels or retraining.</p>
<p class="sd-meta">Release v1.0.1 · Python · pretrained model and outputs for 20 cities on six continents</p>
<a class="sd-btn" href="https://github.com/UrbanMobility-y/WalkGeoAI">GitHub</a><a class="sd-btn" href="https://doi.org/10.5281/zenodo.24030782">Zenodo</a><a class="sd-btn" href="/publications/">Paper</a>
</div>
</div>

<h2 id="code-and-data">Code and data for publications</h2>

<table class="sd-tab">
<thead><tr><th>Study</th><th>Code</th><th>Data</th></tr></thead>
<tbody>
<tr><td class="s">Experienced walkability and the paradox of urban density in Chinese cities. <span class="sd-j"><em>Nature Communications</em> (accepted)</span></td>
<td><a href="https://github.com/UrbanMobility-y/Walkability">Walkability</a></td>
<td><a href="https://doi.org/10.5281/zenodo.17965001">Source data (Zenodo)</a></td></tr>
<tr><td class="s">WalkGeoAI: Open-source software for estimating street-level relative pedestrian activity using global geospatial data. <span class="sd-j"><em>Computers, Environment and Urban Systems</em> (accepted)</span></td>
<td><a href="https://github.com/UrbanMobility-y/WalkGeoAI">WalkGeoAI</a></td>
<td><a href="https://doi.org/10.5281/zenodo.24030782">Model and 20-city outputs (Zenodo)</a></td></tr>
<tr><td class="s"><a href="https://doi.org/10.1140/epjds/s13688-026-00697-4">Multi-layered segregation in urban transportation systems.</a> <span class="sd-j"><em>EPJ Data Science</em> (2026)</span></td>
<td><a href="https://github.com/UrbanMobility-y/multimodal-segregation">multimodal-segregation</a></td>
<td><a href="https://github.com/UrbanMobility-y/multimodal-segregation/tree/main/Source%20data">Source data (GitHub)</a></td></tr>
<tr><td class="s"><a href="https://doi.org/10.1016/j.compenvurbsys.2026.102480">A computational framework for measuring dynamic vehicular exposure and equity in the 15-min city.</a> <span class="sd-j"><em>Computers, Environment and Urban Systems</em> (2026)</span></td>
<td><a href="https://github.com/UrbanMobility-y/dve">dve</a></td>
<td>—</td></tr>
</tbody>
</table>

<h2 id="datasets">Datasets</h2>

<ul class="sd-list">
<li><strong>Yang Y</strong>, Liu E, Jia B, Cheng S, Manley E (2026). Source data for “Experienced walkability and the paradox of urban density in Chinese cities”. <em>Zenodo</em>. <a href="https://doi.org/10.5281/zenodo.17965001">doi.org/10.5281/zenodo.17965001</a></li>
<li><strong>Yang Y</strong>, He D, Gu Y, He H, Huang W (2026). WalkGeoAI: software, pretrained model and street-level outputs for 20 cities (v1.0.1). <em>Zenodo</em>. <a href="https://doi.org/10.5281/zenodo.24030782">doi.org/10.5281/zenodo.24030782</a></li>
<li>Gao L, Song D, <strong>Yang Y</strong>, Xu C, Yang X (2022). District/county-level population census GIS datasets in China (1953–2010). <em>Science Data Bank</em>. <a href="https://doi.org/10.11922/sciencedb.j00001.00273">doi.org/10.11922/sciencedb.j00001.00273</a></li>
</ul>
