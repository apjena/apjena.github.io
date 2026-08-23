---
layout: page
title: Incubator 
author: apjena
toc: true
entries_layout: grid
author_profile: true
hide: true
permalink: /:pages/
header:
  overlay_image: assets/img/header/headerbanner.jpg
bootstrap: true
---
## Contents
{:.no_toc}
* This will become a table of contents (this text will be scrapped).
{:toc}
 

# Observations so far
* pagination works with `layout: home` only in `index.html` not in `index.md` or any other file.
* $$katex$$ support in kramdown only supports `$$ math $$` not single dollar as in case of many md based note takers! Inline and display modes are detected automatically. 
* `site.portfolio` is identified as a liquid variable by jekyll when _config.yml defines a collections by that name. See [apjfolio]({{site.baseurl}}/apjfolio/) for steps.
* Posts in _posts folder without file name convention, even if, it has layout defined by yaml, is not jekylled.
* `bootstrap: true` is to be enabled on the used page, not in config.

# And then,
* ipynb parsing and possibilities in academician theme.
* a1 theme to be looked. Not suitably required to be used.
* To see: Linking in markdown note taking apps to work in theme pages folder: seems not possible randomly, The whole folder perhaps has to be uploaded so that jekyll creates all the links!!!
* Bootstrap including JQuerry and Popper js, still dropdown menu not working! So much overloading for nothing.
    * Gemini: Correct Order for these three libraries: jQuery, Popper.js, Bootstrap JS.
    * Loading in `_includes/default/head.liquid` ... And Works..

# Typical Jekyll Dir str:
* `_includes/`: Contains reusable snippets of code or content (e.g., a site's navigation bar or a footer) that can be embedded into layouts or pages using Liquid's include tag.
* `_layouts/`: Houses the HTML "shells" or templates that define the look and feel of your pages and posts. Content is injected into these layouts using the `content` within double braces `\{\{` Liquid tag.
* `_posts/`: This is where your blog posts live. Files must follow the strict YYYY-MM-DD-title.md naming convention to be processed correctly.
* `_sass/`: Contains your Sass/SCSS files, which are compiled into a single main CSS file for styling your site.
* `_data/`: Allows you to store extra site data in YAML, JSON, or CSV formats. This is useful for structured content like navigation links or lists of projects.
* `_site/`: This directory is where Jekyll outputs the final, generated static HTML files. This folder is generated automatically and should not be edited manually.
* `assets/`: A standard location for static assets such as images, compiled CSS, JavaScript files, and fonts. Subfolders (css/, images/) help keep things organized.
* `index.md (or index.html)`: The main homepage for your site, located at the root directory.
* `_config.yml`: The main configuration file for your entire Jekyll site, where you can define site-wide variables, plugins, and settings.
* `Gemfile and Gemfile.lock`: These files manage the Ruby gems (including the jekyll gem and any plugins) required to build your site.
* Excepting the system files and folders listed above, Jekyll ignores any other file or folder starting with an underscore. Jekyll works by treating everything else as static content or pages to be rendered into the _site directory.

# Test waves
<hl class="load"> 
<span>P</span><span>U</span><span>L</span><span>S</span><span>E</span><span>-</span>
<span>W</span><span>A</span><span>V</span><span>E</span><span>S</span> 
</hl>

<svg width="2rem" height="2rem" viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg">
<path d="M17 13.5v6H5v-12h6m3-3h6v6m0-6-9 9" class="icon_svg-stroke" stroke="#999" stroke-width="1.5" fill="none" fill-rule="evenodd" stroke-linecap="round" stroke-linejoin="round"></path>
</svg> 

# expand collapse
<details>
  <summary>* Energy Stored in an Inductor</summary>
  The energy \(U\) stored in an inductor is given by $$U=\frac{1}{2}LI^{2}$$. $$U=\frac{1}{2}\times 0.5\times (2)^{2}=\mathbf{1.0}\text{\ J}$$
</details>

<details>
  <summary>* Lorentz Force Laws</summary>
  The Lorentz Force is the total force \(\mathbf{F}\) exerted on a charge \(q\) moving with velocity \(\mathbf{v}\) in the presence of an electric field \(\mathbf{E}\) and a magnetic field \(\mathbf{B}\):\(\mathbf{F}=q(\mathbf{E}+\mathbf{v}\times \mathbf{B})\) 
   * Electric Component ($q\mathbf{E}$): The force acts in the direction of the electric field.
   * Magnetic Component ($q\mathbf{v}\times \mathbf{B}$): The force is perpendicular to both the velocity and the magnetic field. 
</details>


# SVG INKSCAPE EXPORTED IMAGE

<svg
   width="646"
   height="220"
   viewBox="0 0 646 220"
   version="1.1"
   id="svg1"
   xmlns:xlink="http://www.w3.org/1999/xlink"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:svg="http://www.w3.org/2000/svg">
  <defs
     id="defs1">
    <linearGradient
       id="linearGradient6">
      <stop
         style="stop-color:#8ee971;stop-opacity:1;"
         offset="0.26029661"
         id="stop7" />
      <stop
         style="stop-color:#3cb7c7;stop-opacity:0;"
         offset="0.86558992"
         id="stop8" />
    </linearGradient>
    <linearGradient
       xlink:href="#linearGradient6"
       id="linearGradient8"
       x1="342.24005"
       y1="-56.361618"
       x2="228.38586"
       y2="211.86205"
       gradientUnits="userSpaceOnUse"
       gradientTransform="translate(-40.087245,1.7317835)" />
    <filter
       style="color-interpolation-filters:sRGB"
       id="filter27"
       x="-0.066152453"
       y="-0.29851014"
       width="1.1323049"
       height="1.5970203">
      <feGaussianBlur
         result="result1"
         in="SourceAlpha"
         stdDeviation="2.2"
         id="feGaussianBlur25" />
      <feSpecularLighting
         result="result0"
         specularExponent="18.10000038"
         specularConstant="2"
         surfaceScale="5"
         id="feSpecularLighting25">
        <feDistantLight
           azimuth="225"
           elevation="24"
           id="feDistantLight25" />
      </feSpecularLighting>
      <feComposite
         result="result6"
         operator="in"
         in2="SourceAlpha"
         id="feComposite25" />
      <feMorphology
         radius="5.7"
         operator="dilate"
         id="feMorphology25" />
      <feGaussianBlur
         result="result11"
         stdDeviation="5.7"
         id="feGaussianBlur26" />
      <feDiffuseLighting
         surfaceScale="5"
         result="result3"
         diffuseConstant="2"
         in="result1"
         id="feDiffuseLighting26">
        <feDistantLight
           elevation="25"
           azimuth="225"
           id="feDistantLight26" />
      </feDiffuseLighting>
      <feBlend
         result="result7"
         mode="multiply"
         in="result3"
         in2="SourceGraphic"
         id="feBlend26" />
      <feComposite
         in="result7"
         operator="in"
         in2="SourceAlpha"
         result="result91"
         id="feComposite26" />
      <feBlend
         result="result9"
         mode="lighten"
         in="result6"
         in2="result91"
         id="feBlend27" />
      <feComposite
         in="result11"
         in2="result9"
         id="feComposite27" />
    </filter>
  </defs>
  <g
     id="layer1">
    <ellipse
       style="fill:#800000;stroke-width:7.30268"
       id="path1"
       cx="203.35175"
       cy="97.528412"
       rx="144.53308"
       ry="71.889496" />
    <text
       xml:space="preserve"
       style="font-style:normal;font-variant:normal;font-weight:bold;font-stretch:normal;font-size:110.737px;line-height:1.25;font-family:MnSymbol;-inkscape-font-specification:'MnSymbol, Bold';font-variant-ligatures:normal;font-variant-caps:normal;font-variant-numeric:normal;font-variant-east-asian:normal;letter-spacing:0px;word-spacing:0px;fill:url(#linearGradient8);stroke-width:1.48309;filter:url(#filter27)"
       x="95.20623"
       y="116.62867"
       id="text3"
       transform="scale(0.87785183,1.1391444)"><tspan
         id="tspan3"
         x="95.20623"
         y="116.62867"
         style="font-style:normal;font-variant:normal;font-weight:bold;font-stretch:normal;font-size:110.737px;font-family:MnSymbol;-inkscape-font-specification:'MnSymbol, Bold';font-variant-ligatures:normal;font-variant-caps:normal;font-variant-numeric:normal;font-variant-east-asian:normal;fill:url(#linearGradient8);fill-opacity:1;stroke-width:1.48309">Sem 1</tspan></text>
  </g>
</svg>

# Draw.io 
* Shares with Google drive saving.
* supports latex math text.
* export as png and svg as well.

<svg xmlns="http://www.w3.org/2000/svg" style="background: transparent; background-color: transparent; color-scheme: light dark;" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="177" height="184" viewBox="0 0 177 184" content="&lt;mxfile host=&quot;app.diagrams.net&quot; agent=&quot;Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Mobile Safari/537.36&quot; version=&quot;29.2.9&quot;&gt;&#10;  &lt;diagram name=&quot;Page-1&quot; id=&quot;UAEc0V2rn7aUDqocQkrh&quot;&gt;&#10;    &lt;mxGraphModel dx=&quot;349&quot; dy=&quot;579&quot; grid=&quot;1&quot; gridSize=&quot;10&quot; guides=&quot;1&quot; tooltips=&quot;1&quot; connect=&quot;1&quot; arrows=&quot;1&quot; fold=&quot;1&quot; page=&quot;1&quot; pageScale=&quot;1&quot; pageWidth=&quot;827&quot; pageHeight=&quot;1169&quot; math=&quot;1&quot; shadow=&quot;1&quot;&gt;&#10;      &lt;root&gt;&#10;        &lt;mxCell id=&quot;0&quot; /&gt;&#10;        &lt;mxCell id=&quot;1&quot; parent=&quot;0&quot; /&gt;&#10;        &lt;mxCell id=&quot;bW0hXZcPCp1QmvZUGkxE-1&quot; edge=&quot;1&quot; parent=&quot;1&quot; style=&quot;edgeStyle=none;orthogonalLoop=1;jettySize=auto;html=1;rounded=0;fontSize=12;startSize=8;endSize=8;curved=1;&quot; value=&quot;&quot;&gt;&#10;          &lt;mxGeometry relative=&quot;1&quot; width=&quot;120&quot; as=&quot;geometry&quot;&gt;&#10;            &lt;Array as=&quot;points&quot; /&gt;&#10;            &lt;mxPoint x=&quot;190&quot; y=&quot;300&quot; as=&quot;sourcePoint&quot; /&gt;&#10;            &lt;mxPoint x=&quot;350&quot; y=&quot;300&quot; as=&quot;targetPoint&quot; /&gt;&#10;          &lt;/mxGeometry&gt;&#10;        &lt;/mxCell&gt;&#10;        &lt;mxCell id=&quot;bW0hXZcPCp1QmvZUGkxE-2&quot; parent=&quot;1&quot; style=&quot;shape=stencil(lVhJchsxDHyNrigS4Hp2nH+4ynKsimO5ZDnL74OJQknAzLTKNy0NEDua3Mjd+/PD23bD4f142H/f/to9Hp838mXDvHt93h52R/20kfuN3D3tD9tvh/3H6+Pp+9vDhJw+/dj/nDT8PskFEp6EOPw5/dA7cfz3y9cT/mX3avAhWHyjWBBeisUXyn0dH6l0i08keR2fKDr7I8W2jq9D28C3SqECeyKxPaAxsQCBTNlGqFZi4EHs1JsVYBJgkvpckhEolXICAt0noTA1XhcQjaqNUm6wKqRRtydkgWlOQk2MQOoUgEmpUbFRSgk6rQaIjVIKFIFJuVK1pSeFAkicBjHYE4RhlIrqi0aAz14tC3SqtpY4U0LVLRRsWJlhlKqaZJ3WcqzA6aqZtqURK0XgdIuUrdMxjR5fFhAq1QqoD8DppjFxJoVRXcsChapNXIdRbVr8Fq+lglzWGFmXy6iURXwPfmTgCPV54VEG/naNqKu70d/L+EJsMxAoIf2FWnH4iPzVcZUd/v9WWcZr/L3+gOzR+IvDo77UlZe8v6hpFN+Sw3dQPzHMtmYcJ64d4ByI8ADFF9f2oyXW8DE5PNoHGlDXwzpnwNLXBDePv1EQMXxGf/EJY9jwPfsVq/FB+rNfNowLVPGz/KIGzmPGXhUQwpcxYq8KFDdw8foZ5VdZkdd/o8GCb7AbDVzZ4SPS3+f2JGR/9wM94HrW/nIrZhy4im8Of0O/y68yOhSf7lk4wwXzaXz1JFbwPFEOa/EZ96/uH0cwKSF7NHyWdVTIeHVBuoGrEx7EXxew06+MoICG0UuAOIGIT8h+AkWBLamsht2IyGMrLwsEP9NjgyxCrxnVJkG7ANGImmZTTgYRWRaInlJPeQYm6b3EUTk+b6plARl1fC5UgVQl9zFor0g7Ku2cPXdKcVwhlwX0BusuHhkub/3bsRu92nR0hQ3e6ZzGvl2+bWXPL3OH/Snqos3DFGh0YyyekZYGGQWf2+Xc0TJI5DInqoOyngUa3AnaXy4P2lIRDVW/A7XJO1j6xZNkpdlIf/Ih0qmJliz766VOZTRi2Cf5QmvX8DYDE8tDKaOWPR4+O/gqVXyG+DzDo5sle5I/0WzEqv2Tw2Wrr70s+VsiZi2zaXehASv4MMfDp7TaZgEC+oNfshPtBwUUxg6+wiMW9fmnwFt4/XB5d3zavbycni2v//fvlPrT6Y1T7v8C);lineShape=1;strokeColor=default;&quot; value=&quot;&quot; vertex=&quot;1&quot;&gt;&#10;          &lt;mxGeometry height=&quot;165.0042857906352&quot; width=&quot;117.90016115290564&quot; x=&quot;211.42811275612726&quot; y=&quot;133.01361851267177&quot; as=&quot;geometry&quot; /&gt;&#10;        &lt;/mxCell&gt;&#10;        &lt;mxCell id=&quot;NuoqfZQtzU8JyVqfvaJU-1&quot; parent=&quot;1&quot; style=&quot;shape=stencil(lVnJchQ7EPyauVZIKq1n4P0HERg8gbEJ48fy96SYUDMqdefgm61RSqo9q/qkb77dv/96dwru28vz0+e7H+cPL/cnfXsK4fx4f/d8fsFfJ3130jcfn57vPj0//f/44fL/1/d9Z//ry9P3fsLPCy5Ijh0U3K/LgpPi/yz8d9n+cH682q4S/LTdD/zu9iipTNtVlGzPojptT5LT8fYied5eJOnx9iZ+FrUN/O52D024WVYvhQGCBANQiY0AVHKYAVGaIwD8XGdAFk/M5RcV+SqBqBTmd7PFsBKIDHCgOHtEXwkEECWbG7CSCSBLNYAijmgpVHGzWrESCnFqJ3E2HFYSEVrh9bMdsFKIDBqkmUDACgNECXkGYIWoVZMkI0OSyITOUtIMyMPh9wGInzYDGrVD9PZJWHHkSVFtMoqBqjUmKQYQxZMQjUXaLDSOSEStCd4/WxpHuEoAwcZ0rFKILyXE9CwD7mRZIxXROeJwpycxnZrU2Q5JpRJADqKz0CkNh98HJJs18MjCEn2WNLt3qiO17QPqEHEAMrTEZGgjV2+AII4VE/jmrNbMs3cJI/VugDgUvQ9QmzWgBlZsSxI/Gw5qSERLJduIK0hkxA6ljgjeAEESe1Ib522AKJFEXPWWMeCRmWipqjhzAxIPyRoAmKJYHb9hibgaaEzXJG2WAXeyklVRsmb3xhGeAapNZLVIZVwGIponNWkMEEa4bOzHUxma2lSJIxqJh5ZsFW28ZLU2qMgGyNRbATAB1DgTAMBYGgAWQB0w17hWh/8eAWq0gMqFNiGKFSV5CefZJ7VRuY8AugAY12jFOl8HMC0V8cECWOZrW8hfASKzdB6ec6VW6t5ZnFqA3gAsrsHoT39StgDGvbvQc1HsKwxQbKrsd5LMB4B1vjwsc+QasS4AdkOzhR0Axu67e2cLoIkMnrPEtBLn887ZmtXqzSzgLSBzIUzX1DbuewTwxQJYb9kfsARE477RZr1e6eEIoWuQsqjOg2tfAWiyfDUgLlJXStdRcerifo35q19qUBoOuV94m9UrHknZxsKY8MhAUhkqf53TMe5kFQL0xEQE7mRUF2TEaAn8g1XquqgVj4yMAPkxlrgiQPQGN7L1FcVidugczxDRNvjHPqCMqrkBCh1FgUxXQ0QTjVEQ2zAbrhN4xu/DcoOnzWX/ec7f6FqoDOhGTVNTeCdXRwuzARK9AeepeVIUJYbDeXXps1ilzotas6d2yIu3ovVLxA742Qwq0FyypgbNquGVKdO5A9phYwes3JgKmGFL4pPQ5CyJS57WrFjt8DHx+hDTMgrhaSbqaFY3AE/G0Vu2gTtZr9gnTAagtCHQbAkQ7mTkQZNtm6LjY7Vo00wfejGADkfYAOCVbA7nba+ovAtSZ6dkkIqFaGiLDLzGrQPUPq1kU+NsOwjlo/IARzBC83FO//BghsB1MP59gLfxgDuZHXyzHURQmip9tmM13MlqnIcvzTLgzsjG/WEhfbwb9X58ANkA2yTigEzboZeHL7HZiZ0M9k8crADtfENRNtxc2rgx7Ny3smRTS2j/s6gn0scvgRZoW+xsExBoAna2AfVDmKPtRpPDm/71dEec2dnxqqPx6yxLcCOejxTpzHZGmZ1lzI4WV29nBbzweduh3tr+qscEyz02ynawPS6KJJp55dfam9vxx98Pwx/PDw+X78rXv9sPyVi6fITWd78B);lineShape=1;strokeColor=default;&quot; value=&quot;&quot; vertex=&quot;1&quot;&gt;&#10;          &lt;mxGeometry height=&quot;149.6378576615524&quot; width=&quot;145.69163531932543&quot; x=&quot;208.95884250076642&quot; y=&quot;147.99385965554598&quot; as=&quot;geometry&quot; /&gt;&#10;        &lt;/mxCell&gt;&#10;        &lt;mxCell id=&quot;NuoqfZQtzU8JyVqfvaJU-3&quot; parent=&quot;1&quot; style=&quot;text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=16;&quot; value=&quot;Light cone&quot; vertex=&quot;1&quot;&gt;&#10;          &lt;mxGeometry height=&quot;30&quot; width=&quot;60&quot; x=&quot;240.38&quot; y=&quot;240&quot; as=&quot;geometry&quot; /&gt;&#10;        &lt;/mxCell&gt;&#10;        &lt;mxCell id=&quot;NuoqfZQtzU8JyVqfvaJU-4&quot; parent=&quot;1&quot; style=&quot;text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=16;&quot; value=&quot;$$\alpha$$&quot; vertex=&quot;1&quot;&gt;&#10;          &lt;mxGeometry height=&quot;60&quot; width=&quot;60&quot; x=&quot;230&quot; y=&quot;147.99&quot; as=&quot;geometry&quot; /&gt;&#10;        &lt;/mxCell&gt;&#10;      &lt;/root&gt;&#10;    &lt;/mxGraphModel&gt;&#10;  &lt;/diagram&gt;&#10;&lt;/mxfile&gt;&#10;"><defs><style xmlns="http://www.w3.org/1999/xhtml" id="MJX-SVG-styles">&#xa;mjx-container[overflow="scroll"][display] {&#xa;  overflow: auto clip;&#xa;  min-width: initial !important;&#xa;}&#xa;&#xa;mjx-container[overflow="truncate"][display] {&#xa;  overflow: hidden clip;&#xa;  min-width: initial !important;&#xa;}&#xa;&#xa;mjx-container[display] {&#xa;  display: block;&#xa;  text-align: center;&#xa;  justify-content: center;&#xa;  margin: .7em 0;&#xa;  padding: .3em 2px;&#xa;}&#xa;&#xa;mjx-container[display][width="full"] {&#xa;  display: flex;&#xa;}&#xa;&#xa;mjx-container[justify="left"] {&#xa;  text-align: left;&#xa;  justify-content: left;&#xa;}&#xa;&#xa;mjx-container[justify="right"] {&#xa;  text-align: right;&#xa;  justify-content: right;&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] {&#xa;  direction: ltr;&#xa;  white-space: nowrap;&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] &gt; svg {&#xa;  overflow: visible;&#xa;  min-height: 1px;&#xa;  min-width: 1px;&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] &gt; svg a {&#xa;  fill: blue;&#xa;  stroke: blue;&#xa;}&#xa;&#xa;rect[data-sre-highlighter-added]:has(+ .mjx-selected), rect[data-sre-highlighter-bbox].mjx-selected {&#xa;  stroke: black;&#xa;  stroke-width: 80px;&#xa;}&#xa;&#xa;@media (prefers-color-scheme: dark) {&#xa;  rect[data-sre-highlighter-added]:has(+ .mjx-selected), rect[data-sre-highlighter-bbox].mjx-selected {&#xa;    stroke: #C8C8C8;&#xa;  }&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] mjx-break {&#xa;  white-space: normal;&#xa;  line-height: 0;&#xa;  clip-path: rect(0 0 0 0);&#xa;  font-family: MJX-ZERO ! important;&#xa;}&#xa;&#xa;mjx-break[size="0"] {&#xa;  letter-spacing: -0.999em;&#xa;}&#xa;&#xa;mjx-break[size="1"] {&#xa;  letter-spacing: -0.889em;&#xa;}&#xa;&#xa;mjx-break[size="2"] {&#xa;  letter-spacing: -0.833em;&#xa;}&#xa;&#xa;mjx-break[size="3"] {&#xa;  letter-spacing: -0.778em;&#xa;}&#xa;&#xa;mjx-break[size="4"] {&#xa;  letter-spacing: -0.722em;&#xa;}&#xa;&#xa;mjx-break[size="5"] {&#xa;  letter-spacing: -0.667em;&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] mjx-break[newline]::before {&#xa;  white-space: pre;&#xa;  content: "\A";&#xa;}&#xa;&#xa;mjx-break[newline] + svg[width="0.054ex"] {&#xa;  margin-right: -1px;&#xa;}&#xa;&#xa;mjx-break[prebreak] {&#xa;  letter-spacing: -.999em;&#xa;}&#xa;&#xa;@font-face /* zero */ {&#xa;  font-family: MJX-ZERO;&#xa;  src: url(data:application/x-font-woff;charset=utf-8;base64,T1RUTwAJAIAAAwAQQ0ZGIGnFMZkAAARQAAAAlE9TLzJpUWOBAAABAAAAAGBjbWFwAAwAUwAABAQAAAAsaGVhZCFRvpAAAACcAAAANmhoZWEC8AD9AAAA1AAAACRobXR4A+gAAAAABOQAAAAIbWF4cAACUAAAAAD4AAAABm5hbWVNb8+2AAABYAAAAqNwb3N0AAMAAAAABDAAAAAgAAEAAAABAABVWOu4Xw889QADA+gAAAAA3ym+2AAAAADfKb7YAAAAAAPoAAAAAAADAAIAAAAAAAAAAQAAAu79EgAAA+gAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAIAAFAAAAIAAAADA+gB9AAFAAACigK7AAAAjAKKArsAAAHfADEBAgAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAABYWFhYAEAAIAAgAu79EgAAAu4C7gAAAAEAAAAAAXcAAAAgACAAAAAAACIBngABAAAAAAAAAAEAQQABAAAAAAABAAsAAAABAAAAAAACAAcAIQABAAAAAAADABUAxgABAAAAAAAEABMANgABAAAAAAAFAAsApQABAAAAAAAGABIAbwABAAAAAAAHAAEAQQABAAAAAAAIAAEAQQABAAAAAAAJAAEAQQABAAAAAAAKAAEAQQABAAAAAAALAAEAQQABAAAAAAAMAAEAQQABAAAAAAANAAEAQQABAAAAAAAOAAEAQQABAAAAAAAQAAsAAAABAAAAAAARAAcAIQADAAEECQAAAAIAXwADAAEECQABABYACwADAAEECQACAA4AKAADAAEECQADACoA2wADAAEECQAEACYASQADAAEECQAFABYAsAADAAEECQAGACQAgQADAAEECQAHAAIAXwADAAEECQAIAAIAXwADAAEECQAJAAIAXwADAAEECQAKAAIAXwADAAEECQALAAIAXwADAAEECQAMAAIAXwADAAEECQANAAIAXwADAAEECQAOAAIAXwADAAEECQAQABYACwADAAEECQARAA4AKG1qeC1sbS16ZXJvAG0AagB4AC0AbABtAC0AegBlAHIAb1JlZ3VsYXIAUgBlAGcAdQBsAGEAcm1qeC1sbS16ZXJvIFJlZ3VsYXIAbQBqAHgALQBsAG0ALQB6AGUAcgBvACAAUgBlAGcAdQBsAGEAcm1qeC1sbS16ZXJvUmVndWxhcgBtAGoAeAAtAGwAbQAtAHoAZQByAG8AUgBlAGcAdQBsAGEAclZlcnNpb24gMC4xAFYAZQByAHMAaQBvAG4AIAAwAC4AMSA6bWp4LWxtLXplcm8gUmVndWxhcgAgADoAbQBqAHgALQBsAG0ALQB6AGUAcgBvACAAUgBlAGcAdQBsAGEAcgAAAAABAAMAAQAAAAwABAAgAAAABAAEAAEAAAAg//8AAAAg////4QABAAAAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAEAQABAQETbWp4LWxtLXplcm9SZWd1bGFyAAEBASf4GwD4HAL4HQP4HgSLi/mC+nwFHQAAAIYPHQAAAIkRix0AAACUEgAFAQEMHyoxNlZlcnNpb24gMC4xbWp4LWxtLXplcm8gUmVndWxhcm1qeC1sbS16ZXJvUmVndWxhcnNwYWNlAAAAAYsAAgEBAwaLDvp8DgAAAAAD6AAA) format("woff");&#xa;}&#xa;&#xa;g[data-mml-node="merror"] &gt; g {&#xa;  fill: red;&#xa;  stroke: red;&#xa;}&#xa;&#xa;g[data-mml-node="merror"] &gt; rect[data-background] {&#xa;  fill: yellow;&#xa;  stroke: none;&#xa;}&#xa;&#xa;g[data-mml-node="mtable"] &gt; line[data-line], svg[data-table] &gt; g &gt; line[data-line] {&#xa;  stroke-width: 70px;&#xa;  fill: none;&#xa;}&#xa;&#xa;g[data-mml-node="mtable"] &gt; rect[data-frame], svg[data-table] &gt; g &gt; rect[data-frame] {&#xa;  stroke-width: 70px;&#xa;  fill: none;&#xa;}&#xa;&#xa;g[data-mml-node="mtable"] &gt; .mjx-dashed, svg[data-table] &gt; g &gt; .mjx-dashed {&#xa;  stroke-dasharray: 140;&#xa;}&#xa;&#xa;g[data-mml-node="mtable"] &gt; .mjx-dotted, svg[data-table] &gt; g &gt; .mjx-dotted {&#xa;  stroke-linecap: round;&#xa;  stroke-dasharray: 0,140;&#xa;}&#xa;&#xa;g[data-mml-node="mtable"] &gt; g &gt; svg {&#xa;  overflow: visible;&#xa;}&#xa;&#xa;[jax="SVG"] mjx-tool {&#xa;  display: inline-block;&#xa;  position: relative;&#xa;  width: 0;&#xa;  height: 0;&#xa;}&#xa;&#xa;[jax="SVG"] mjx-tool &gt; mjx-tip {&#xa;  position: absolute;&#xa;  top: 0;&#xa;  left: 0;&#xa;}&#xa;&#xa;mjx-tool &gt; mjx-tip {&#xa;  display: inline-block;&#xa;  line-height: 0;&#xa;  padding: .2em;&#xa;  border: 1px solid #888;&#xa;  background-color: #F8F8F8;&#xa;  color: black;&#xa;  box-shadow: 2px 2px 5px #AAAAAA;&#xa;}&#xa;&#xa;g[data-mml-node="maction"][data-toggle] {&#xa;  cursor: pointer;&#xa;}&#xa;&#xa;mjx-status {&#xa;  display: block;&#xa;  position: fixed;&#xa;  left: 1em;&#xa;  bottom: 1em;&#xa;  min-width: 25%;&#xa;  padding: .2em .4em;&#xa;  border: 1px solid #888;&#xa;  font-size: 90%;&#xa;  background-color: #F8F8F8;&#xa;  color: black;&#xa;}&#xa;&#xa;g[data-mjx-collapsed] {&#xa;  fill: #55F;&#xa;}&#xa;&#xa;@media (prefers-color-scheme: dark) /* svg maction */ {&#xa;  mjx-tool &gt; mjx-tip {&#xa;    background-color: #303030;&#xa;      color: #E0E0E0;&#xa;      box-shadow: 2px 2px 5px #000;&#xa;  }&#xa;  mjx-status {&#xa;    background-color: #303030;&#xa;      color: #E0E0E0;&#xa;  }&#xa;  g[data-mjx-collapsed] {&#xa;    fill: #88F;&#xa;  }&#xa;}&#xa;&#xa;foreignObject[data-mjx-xml] {&#xa;  font-family: initial;&#xa;  line-height: normal;&#xa;  overflow: visible;&#xa;}&#xa;&#xa;foreignObject[data-mjx-html] {&#xa;  overflow: visible;&#xa;}&#xa;&#xa;mjx-measure-xml {&#xa;  position: absolute;&#xa;  left: 0;&#xa;  top: 0;&#xa;  display: inline-block;&#xa;  line-height: normal;&#xa;  white-space: normal;&#xa;}&#xa;&#xa;mjx-html {&#xa;  display: inline-block;&#xa;  line-height: normal;&#xa;  text-align: initial;&#xa;  white-space: initial;&#xa;}&#xa;&#xa;mjx-html-holder {&#xa;  display: block;&#xa;  position: absolute;&#xa;  top: 0;&#xa;  left: 0;&#xa;  bottom: 0;&#xa;  right: 0;&#xa;}&#xa;&#xa;mjx-container[jax="SVG"] path[data-c], mjx-container[jax="SVG"] use[data-c] {&#xa;  stroke-width: 3;&#xa;}&#xa;</style></defs><g style="filter: drop-shadow(light-dark(rgba(61, 69, 116, 0.4), rgba(168, 175, 216, 0.4)) 3px 3px 1.7px);"><g data-cell-id="0"><g data-cell-id="1"><g data-cell-id="bW0hXZcPCp1QmvZUGkxE-1"><g transform="translate(0.5,0.5)"><path d="M 0 167 Q 0 167 152.13 167" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke" style="stroke: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));"/><path d="M 158.88 167 L 149.88 171.5 L 152.13 167 L 149.88 162.5 Z" fill="#000000" stroke="#000000" stroke-miterlimit="10" pointer-events="all" style="fill: light-dark(rgb(0, 0, 0), rgb(255, 255, 255)); stroke: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));"/></g></g><g data-cell-id="bW0hXZcPCp1QmvZUGkxE-2"><g transform="translate(0.5,0.5)"><path d="M 21.81 163.71 L 21.43 161.98 L 21.85 159.39 L 23.42 155.7 L 26.29 150.46 L 30.09 143.68 L 34.66 135.7 L 39.7 127.48 L 44.98 119.43 L 50.48 111.46 L 56.04 103.67 L 61.69 96.06 L 67.36 88.44 L 73.1 80.9 L 78.82 73.51 L 84.32 66.33 L 89.56 59.5 L 94.57 53.16 L 99.25 47.34 L 103.6 42.06 L 107.53 37.21 L 111.14 32.6 L 114.51 28.25 L 117.53 24.25 L 120.08 20.77 L 122.17 17.88 L 123.69 15.66 L 125.46 12.74 L 126.25 9.98 L 128.13 7.75 L 129.94 5.84 L 131.79 3.56 L 134.93 0.72 L 135.63 0.24 L 136.44 0.01 L 137.28 0.06 L 138.07 0.36 L 138.7 0.9 L 139.14 1.63 L 139.33 2.44 L 139.25 3.28 L 138.89 4.06 L 138.31 4.67 L 137.57 5.06 L 136.75 5.19 L 135.91 5.06 L 135.17 4.68 L 134.59 4.07 L 134.23 3.31 L 134.14 2.47 L 134.32 1.65 L 134.74 0.92 L 135.38 0.38 L 136.16 0.06 L 137.01 0.01 L 137.82 0.23 L 138.51 0.71 L 139.02 1.37 L 139.29 2.18 L 139.3 3.02 L 139.03 3.81 L 138.53 4.49 L 138.53 4.49 L 136.05 6.58 L 134.05 8.49 L 131.74 10.59 L 129.77 12.17 L 128.53 14.73 L 126.23 17.59 L 124.46 19.68 L 122.2 22.37 L 119.52 25.77 L 116.49 29.78 L 113.11 34.15 L 109.48 38.79 L 105.54 43.64 L 101.21 48.9 L 96.54 54.71 L 91.57 61.03 L 86.32 67.86 L 80.83 75.04 L 75.13 82.43 L 69.43 89.96 L 63.77 97.6 L 58.18 105.19 L 52.67 112.96 L 47.27 120.91 L 42.1 128.93 L 37.2 137.13 L 32.81 145.15 L 29.22 151.98 L 26.73 157.13 L 24.72 161.59 L 24.86 163.25 L 24.87 163.62 L 24.79 163.98 L 24.62 164.31 L 24.39 164.61 L 24.09 164.82 L 23.74 164.97 L 23.37 165.02 L 23.01 164.98 L 22.65 164.87 L 22.35 164.65 L 22.09 164.39 L 21.91 164.06 L 21.81 163.71 L 21.81 163.71" fill="#000000" stroke="#000000" stroke-miterlimit="10" pointer-events="all" style="fill: light-dark(rgb(0, 0, 0), rgb(255, 255, 255)); stroke: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));"/></g></g><g data-cell-id="NuoqfZQtzU8JyVqfvaJU-1"><g transform="translate(0.5,0.5)"><path d="M 22.81 16.06 L 23.64 17.45 L 25.62 19.99 L 28.18 23.45 L 30.08 26.26 L 32.28 29.4 L 34.55 32.55 L 36.73 35.18 L 38.8 37.29 L 40.78 39.1 L 44.64 42.3 L 48.2 45.36 L 51.61 48.54 L 54.9 51.89 L 58.11 55.4 L 59.78 57.3 L 63.25 60.77 L 65.11 62.52 L 66.99 64.31 L 68.87 66.2 L 70.68 68.07 L 72.5 69.91 L 76.06 73.35 L 79.42 76.45 L 82.54 78.98 L 85.6 81.03 L 88.82 83.11 L 92.21 85.44 L 95.62 88 L 99 90.55 L 102.45 93.03 L 106.08 95.57 L 109.84 98.31 L 113.76 101.39 L 115.93 103.25 L 118.25 105.45 L 120.55 107.84 L 122.41 110 L 124.02 111.96 L 126.3 114.82 L 128.37 117.62 L 130.41 120.55 L 132.6 123.5 L 134.84 126.37 L 137.28 129.62 L 139.94 133.46 L 141.31 135.6 L 142.71 137.82 L 144.12 140.18 L 145.51 142.43 L 148.25 146.42 L 150.97 149.56 L 153.65 152.15 L 155.84 154.14 L 157.95 155.98 L 163.56 159.45 L 164.18 160.14 L 164.56 161.01 L 164.64 161.95 L 164.42 162.87 L 163.92 163.66 L 163.18 164.26 L 162.3 164.57 L 161.36 164.6 L 160.45 164.33 L 159.7 163.79 L 159.14 163.03 L 158.87 162.13 L 158.88 161.19 L 159.2 160.31 L 159.8 159.56 L 160.59 159.05 L 161.5 158.83 L 162.44 158.9 L 163.3 159.27 L 164.01 159.89 L 164.48 160.71 L 164.65 161.64 L 164.52 162.57 L 164.11 163.42 L 163.44 164.08 L 162.61 164.5 L 161.68 164.63 L 160.75 164.45 L 159.93 164 L 159.93 164 L 156.78 161.83 L 154.26 160.1 L 152.12 157.99 L 150.02 155.91 L 147.17 153.02 L 144.09 149.4 L 142.62 147.35 L 141.15 145.16 L 139.69 142.9 L 138.28 140.67 L 136.87 138.53 L 134.2 134.63 L 131.65 131.17 L 129.41 128.16 L 127.19 125.13 L 125.04 122.01 L 123.19 119.2 L 121.28 116.52 L 118.74 113.22 L 117.07 111.3 L 114.87 109.16 L 112.62 107.22 L 110.56 105.52 L 106.65 102.55 L 102.99 99.93 L 99.42 97.41 L 95.81 94.81 L 92.37 92.24 L 89.18 89.81 L 85.9 87.49 L 82.64 85.28 L 79.39 82.97 L 76.04 80.15 L 72.63 76.91 L 70.84 75.18 L 69 73.38 L 67.15 71.51 L 65.38 69.67 L 63.6 67.91 L 61.72 66.13 L 59.78 64.3 L 57.92 62.47 L 56.05 60.56 L 52.86 56.94 L 49.85 53.56 L 46.68 50.37 L 43.44 47.26 L 39.89 44.02 L 37.84 42.24 L 35.76 40.22 L 33.54 37.89 L 31.17 35.12 L 28.72 32.04 L 26.29 28.93 L 22.88 24.15 L 21.19 21.65 L 19.89 19.45 L 19.21 17.99 L 19.02 17.52 L 18.96 17.04 L 19.02 16.55 L 19.18 16.09 L 19.45 15.68 L 19.83 15.35 L 20.26 15.11 L 20.74 14.99 L 21.23 14.99 L 21.71 15.11 L 22.15 15.34 L 22.51 15.65 L 22.81 16.06 L 22.81 16.06" fill="#000000" stroke="#000000" stroke-miterlimit="10" pointer-events="all" style="fill: light-dark(rgb(0, 0, 0), rgb(255, 255, 255)); stroke: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));"/></g></g><g data-cell-id="NuoqfZQtzU8JyVqfvaJU-3"><g transform="translate(0.5,0.5)"><rect x="50.38" y="107" width="60" height="30" fill="none" stroke="none" pointer-events="all"/></g><g><g><switch><foreignObject style="overflow: visible; text-align: left;" pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 58px; height: 1px; padding-top: 122px; margin-left: 51px;"><div style="box-sizing: border-box; font-size: 0; text-align: center; color: #000000; "><div style="display: inline-block; font-size: 16px; font-family: Helvetica; color: light-dark(#000000, #ffffff); line-height: 1.2; pointer-events: all; white-space: normal; word-wrap: normal; ">Light cone</div></div></div></foreignObject><text x="80" y="127" fill="light-dark(#000000, #ffffff)" font-family="Helvetica" font-size="16px" text-anchor="middle">Light c...</text></switch></g></g></g><g data-cell-id="NuoqfZQtzU8JyVqfvaJU-4"><g transform="translate(0.5,0.5)"><rect x="40" y="14.99" width="60" height="60" fill="none" stroke="none" pointer-events="all"/></g><g><g><switch><foreignObject style="overflow: visible; text-align: left;" pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 58px; height: 1px; padding-top: 45px; margin-left: 41px;"><div style="box-sizing: border-box; font-size: 0; text-align: center; color: #000000; "><div style="display: inline-block; font-size: 16px; font-family: Helvetica; color: light-dark(#000000, #ffffff); line-height: 1.2; pointer-events: all; white-space: normal; word-wrap: normal; "><mjx-container class="MathJax" jax="SVG" overflow="overflow" display="true"><svg xmlns="http://www.w3.org/2000/svg" width="1.448ex" height="1.025ex" role="img" focusable="false" viewBox="0 -442 640 453" xmlns:xlink="http://www.w3.org/1999/xlink" style="vertical-align: -0.025ex;"><defs><path id="MJX-2-TEX-I-1D6FC" d="M582 393C565 393 565 393 560 374C543 314 516 255 485 208L485 237C484 270 482 284 478 304C457 388 399 442 309 442C301 442 293 441 287 441C164 428 57 316 37 198C35 187 34 171 34 156C34 148 34 140 35 134C48 51 105-11 203-11C314-11 411 70 411 69C411 69 413 65 414 62C427 22 453-10 505-10L512-10C549-10 578 17 591 43C595 51 597 57 597 61C597 68 591 70 577 70C561 70 560 69 557 60C550 42 532 28 514 26C509 26 508 26 505 28C495 37 489 68 487 123L486 147L497 161C543 222 580 296 599 369C602 379 603 383 603 385C603 393 597 393 582 393M121 120C121 147 127 180 141 231C153 277 166 307 183 332C215 377 261 405 304 405C396 405 399 302 401 182C402 144 403 113 403 112C404 111 389 98 375 88C339 61 302 43 266 34C246 29 225 26 208 26C152 26 121 63 121 120Z"/></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="scale(1,-1)"><g data-mml-node="math" data-latex="\alpha"><g data-mml-node="mi" data-latex="\alpha"><use data-c="1D6FC" xlink:href="#MJX-2-TEX-I-1D6FC"/></g></g></g></svg></mjx-container></div></div></div></foreignObject><text x="70" y="50" fill="light-dark(#000000, #ffffff)" font-family="Helvetica" font-size="16px" text-anchor="middle">$$\alph...</text></switch></g></g></g></g></g></g><switch><g requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"/><a transform="translate(0,-5)" xlink:href="https://www.drawio.com/doc/faq/svg-export-text-problems" target="_blank"><text text-anchor="middle" font-size="10px" x="50%" y="100%">Text is not SVG - cannot display</text></a></switch></svg>

# Bootstrap testing.
<div class="container">
<div class="dropdown">
  <button class="btn btn-primary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
    Dropdown
  </button>
  <ul class="dropdown-menu">
    <li><button class="dropdown-item" type="button">Dropdown item</button></li>
    <li><button class="dropdown-item" type="button">Dropdown item</button></li>
    <li><button class="dropdown-item" type="button">Dropdown item</button></li>
  </ul>
</div>
</div>

### test2 

<div class="container">
  <div class="row">
    <!-- This column spans half (6/12) of the row width on medium screens and up -->
    <div class="col-md-6">
      Content goes here.  
    </div>
    <!-- This column also spans half (6/12) of the row width on medium screens and up -->
    <div class="col-md-6">
      More content
    </div>
  </div>
</div>

### test3
<div class="btn-group open">
  <a class="btn btn-primary" href="#"><i class="icon-user"></i> User</a>
  <a class="btn btn-primary dropdown-toggle" data-toggle="dropdown" href="#">
    <span class="icon-caret-down"></span></a>
  <ul class="dropdown-menu">
    <li><a href="#"><i class="icon-fixed-width icon-pencil"></i> Edit</a></li>
    <li><a href="#"><i class="icon-fixed-width icon-trash"></i> Delete</a></li>
    <li><a href="#"><i class="icon-fixed-width icon-ban-circle"></i> Ban</a></li>
    <li class="divider"></li>
    <li><a href="#"><i class="i"></i> Make admin</a></li>
  </ul>
</div>

### test4 Icons:
<a class="btn" href="#">
  <i class="icon-repeat"></i> Reload</a>
<a class="btn btn-success" href="#">
  <i class="icon-shopping-cart icon-large"></i> Checkout</a>
<a class="btn btn-large btn-primary" href="#">
  <i class="icon-comment"></i> Comment</a>
<a class="btn btn-small btn-info" href="#">
  <i class="icon-info-sign"></i> Info</a>
<a class="btn btn-danger" href="#">
  <i class="icon-trash icon-large"></i> Delete</a>
<a class="btn btn-small" href="#">
  <i class="icon-cog"></i> Settings</a>
<a class="btn btn-large btn-danger" href="#">
  <i class="icon-flag icon-2x pull-left"></i> Font Awesome<br>Version 3.2.1</a>
<a class="btn btn-primary" href="#">
  <i class="icon-refresh icon-spin"></i> Synchronizing Content...</a>


### SEE 1
<div class="bootstrap-iso">
  <ul class="nav nav-tabs">
    <li class="nav-item">
      <a class="nav-link active" href="#">Home</a>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button">Settings</a>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="#">Profile</a>
        <a class="dropdown-item" href="#">Security</a>
      </div>
    </li>
  </ul>
</div>

### SEE 2
<div class="bootstrap-iso"> <!-- If using isolation CSS -->
  <div class="dropdown">
    <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Dropdown button 1
    </button>
    <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
      <a class="dropdown-item" href="#">Action11</a>
      <a class="dropdown-item" href="#">Action12</a>
      <a class="dropdown-item" href="#">Action13</a>
      <a class="dropdown-item" href="#">Action14</a>
    </div>
  </div>
<!-- Add margin for visibility if needed -->
    <div style="margin-top: 20px;"></div> 

<div class="dropdown">
        <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown button 2
        </button>
        <div class="dropdown-menu" aria-labelledby="dropdownMenuButton2">
            <a class="dropdown-item" href="#">Action21</a>
            <a class="dropdown-item" href="#">Action22</a>
            <a class="dropdown-item" href="#">Action23</a>
            <a class="dropdown-item" href="#">Action24</a>
        </div>
    </div>

</div>

## HTML canvas drawings:
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
Your browser does not support the HTML canvas element.
</canvas>

<script>
const canvas = document.getElementById("myCanvas"); // Step 1: Find the canvas element
const ctx = canvas.getContext("2d");              // Step 2: Create a 2D drawing object
ctx.fillStyle = "#FF0000";                        // Step 3: Set drawing style
ctx.fillRect(10, 10, 150, 75);                    // Step 3: Draw a filled rectangle
</script>

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
  Sorry, your browser does not support inline SVG.
</svg>

## Implementation of bootstrap for grouping sems in bscphy page.

* `collections` offered by jekyll does not support sub-folder sub-grouping.
* Out of many workarounds, the following one is convenient:
  - Every page will be inside bscphys collection folder.
  - A new yaml variable **group** is introduced for use. (semester1, semester2, etc.)
  - By bootstrap cards, these groups will be separated by liquid coding. _Thanks Google AI_.

{% comment %} bootstrap works ok.
### Bootstrapping
<!-- Page Content -->
<div class="container">

   <div class="row"> 
    {% assign groupnames = site.bscphys | group_by: 'group' %}
    {% for group in groupnames %}

   <div class="col-lg-6 mb-5 h-100"> <div class="card h-100">
   <a href="#"><img class="card-img-top" src="/assets/img/bscphys/{{ group.name }}.jpg" 
            alt="{{ group.name }}"></a>
    <div class="card-body">
    <div class="card-img-overlay">
    <h4 class="card-title"> <a href="#">{{ group.name | capitalize }}</a> </h4>
    <p class="card-text">    
                <div class="list-group">
                {% for item in group.items %}
        <a class="list-group-item bg-transparent border-0" href="{{ item.url | relative_url }}"><i class="fa fa-book fa-fw" aria-hidden="true"></i>&nbsp; {{ item.title }} - {{ item.subtitle }} </a>
                {% endfor %}
                </div>
<!--    <a href="#" class="btn btn-primary">Go somewhere</a>
<a href="#" class="card-link">Card link</a>
    <a href="#" class="card-link">Another link</a> -->
    </p>
    </div>
    </div>
    </div>
    </div>

    {% endfor %}
</div>
    <!-- /.row -->
</div>
<!-- /.container -->
{% endcomment %}
{% comment %}
## This is generated by basic liquid.(working ok)
{% assign groupnames = site.bscphys | group_by: 'group' %}
{% for group in groupnames %}
### This is {{ group.name }}
<ul> 
{% for item in group.items %}
<li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
{% endfor %}
{% endcomment %}

-----

### pure css dropdown google
<div class="dropdown">
  <button class="dropbtn">Dropdown</button>
  <div class="dropdown-content">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
</div>

--------

    <div class="form-group">
        <label for="semSelect">Choose Semester:</label>
        <select id="semSelect" onchange="updatePapers()">
            <option value="">-- Select Semester --</option>
            <option value="semall">GE, Minor or MDC</option>
            <option value="sem1">Semester 1</option>
            <option value="sem2">Semester 2</option>
            <option value="sem3">Semester 3</option>
            <option value="sem4">Semester 4</option>
            <option value="sem5">Semester 5</option>
            <option value="sem6">Semester 6</option>
        </select>
    </div>

    <div class="form-group">
        <label for="paperSelect">Choose Paper:</label>
        <select id="paperSelect" disabled>
            <option value="">-- Select Semester First --</option>
        </select>
    </div>

    <button onclick="viewQuestions()">View Questions</button>

    <script>
        // Define paper options for each class
        const semData = {
            "sem1": ["Paper 1 (Mathematical Physics-I: Calculus &amp; Vectors)",
                     "Paper 1 Practical",
                     "Paper 2 (Mechanics)", 
                     "Paper 2 Practical"
                    ],
            "sem2": ["Paper 3 (Electricity and Magnetism)", 
                     "Paper 3 Practical",
                     "Paper 4 (Mathematical Physics-II: Fourier Series, Polynomials, PDE)", 
                     "Paper 4 Practical"
                    ],
            "sem3": ["Paper 5 (Waves and Optics)",
                     "Paper 5 Practical", 
                     "Paper 6 (Mathematical Physics-III: Complex Analysis, Integral transforms, Laplace T.)",
                     "Paper 6 Practical",
                     "Paper 7 (Thermal Physics)",
                     "Paper 7 Practical"
                    ]
        };

        function updatePapers() {
            const semDropdown = document.getElementById("semSelect");
            const paperDropdown = document.getElementById("paperSelect");
            const selectedSem = semDropdown.value;

            // Clear existing options
            paperDropdown.innerHTML = '<option value="">-- Select Paper --</option>';

            if (selectedSem && semData[selectedSem]) {
                paperDropdown.disabled = false;
                
                // Add new options based on selection
                semData[selectedSem].forEach( paper => {
                    let option = document.createElement("option");
                    option.value = paper.toLowerCase().replace(/\s+/g, '-');
                    option.textContent = paper;
                    paperDropdown.appendChild(option);
                });
            } else {
                paperDropdown.disabled = true;
                paperDropdown.innerHTML = '<option value="">-- Select Semester First --</option>';
            }
        }

        function viewQuestions() {
            const sem = document.getElementById("semSelect").value;
            const pap = document.getElementById("paperSelect").value;

            if (sem && pap) {
                alert(`You selected Semester: ${sem.replace('sem', '')} and Paper: ${pap.replace(/-/g, ' ').replace(/\b\w/g, c => c.toUpperCase())}. You would typically navigate to a page like "${sem}-${pap}.html" here.`);
            } else {
                alert("Please select both Semester and Paper!");
            }
        }
</script>

