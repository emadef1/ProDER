# ProDER
# ProDER: A Continual Learning Approach for Fault Classification and Localization in Evolving Smart Grids
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/ProDER/tree/main">
    <img src="Figures/SQS_logo_simple.svg" alt="Logo" width="500" height="500">
  </a>

  <h1 align="center"></h1>

  <p align="center">
    ProDER: A Continual Learning Approach for Fault Classification and Localization in Evolving Smart Grids
    <br />
    <a href="???"><strong>Paper Revised in Neural Computing and Applictions»</strong></a>
    <br />
    <br />
    <a href="https://www.dei.unipd.it/persona/1373bd29c9ef0140e39d53ec9add14d2">Emad Efatinasab</a>
    ·
    <a href="https://scholar.google.com/citations?user=VG_xT0YAAAAJ&hl=en">Nahal Azadi</a>
    .
    <a href="https://www.unipd.it/contatti/davide.dallepezze">Davide Dalle Pezze</a>
    ·
    <a href="https://www.unipd.it/contatti/gianantonio.susto">Gian Antonio Susto</a>
    .
    <a href="https://www.ncl.ac.uk/computing/people/profile/mujeebahmed.html">Chuadhry Mujeeb Ahmed</a>
    .
    <a href="https://www.dei.unipd.it/persona/95DDDDA0C518D43822ADC0338BD38073">Mirco Rampazzo</a>
    .
  </p>
</div>

<p align="right"><a href="#top">(back to top)</a></p>
<div id="citation"></div>

## 🗣️ Citation

Please, cite this work when referring to the paper.

```
???

```
<div id="abstract"></div>

## 🧩 Abstract

>As smart grids evolve, fault diagnosis models need to adapt to new fault types and changing operating conditions without being retrained from scratch whenever new data become available. Continual learning offers a suitable framework for this setting, although catastrophic forgetting remains an important challenge, especially when only a limited amount of past data can be stored. In this work, we consider four fault classification and localization scenarios based on class-incremental and domain-incremental learning and propose Prototype-based Dark Experience Replay (ProDER). ProDER extends replay-based continual learning by combining temperature-scaled logit distillation with prototype-based attraction and repulsion losses and a prototype-aware strategy for selecting replay samples. We compare ProDER with several regularization and replay-based continual learning methods using five random seeds. Across the four scenarios, ProDER obtains mean accuracies of 0.461, 0.442, 0.510, and 0.914, respectively, giving accuracy gaps of 0.058, 0.078, 0.010, and $-0.018$ with respect to Joint Training. ProDER also maintains the highest accuracy among the evaluated replay methods when the replay budget is reduced. Overall, the results show that combining prototype-based representation constraints with replay can improve knowledge retention under both class and domain-incremental changes while keeping the replay memory bounded.

<p align="right"><a href="#top">(back to top)</a></p>
<div id="usage"></div>


