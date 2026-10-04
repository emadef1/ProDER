# ProDER: A Continual Learning Approach for Fault Classification and Localization in Evolving Smart Grids
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/ProDER/tree/main">
    <img src="Figures/logo.png" alt="Logo" width="500" height="500">
  </a>

  <h1 align="center"></h1>

  <p align="center">
    ProDER: A Continual Learning Approach for Fault Classification and Localization in Evolving Smart Grids
    <br />
    <a href="???"><strong>Paper Revised in Neural Computing and Applictions»</strong></a>
    <br />
    <br />
    <!-- <a href="https://www.dei.unipd.it/persona/1373bd29c9ef0140e39d53ec9add14d2">Emad Efatinasab</a>
    ·
    <a href="https://scholar.google.com/citations?user=VG_xT0YAAAAJ&hl=en">Nahal Azadi</a>
    .
    <a href="https://www.unipd.it/contatti/davide.dallepezze">Davide Dalle Pezze</a>
    ·
    <a href="https://www.unipd.it/contatti/gianantonio.susto">Gian Antonio Susto</a>
    .
    <a href="https://www.ncl.ac.uk/computing/people/profile/mujeebahmed.html">Chuadhry Mujeeb Ahmed</a>
    .
    <a href="https://www.dei.unipd.it/persona/95DDDDA0C518D43822ADC0338BD38073">Mirco Rampazzo</a> -->
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

>Data-driven fault-diagnosis models for smart grids are usually trained once on a fixed dataset, whereas in operation new fault types appear and monitoring is extended to new grid zones. Retraining from scratch on all accumulated data is costly, while naively updating the model on new data causes catastrophic forgetting.
To address this problem, we formulate fault-type classification and fault-zone localization as continual learning (CL) problems and design four evaluation scenarios on the IEEE 13-node test feeder, three class-incremental and one domain-incremental. We then propose Prototype-based Dark Experience Replay (ProDER), which extends DER++ with prototype attraction and prototype-level repulsion losses that stabilize the feature space, temperature-scaled logit distillation, and a prototype-aware replay memory that retains both core and boundary samples of each class.
ProDER achieves the highest accuracy among the tested CL methods in all scenarios, with an average accuracy of 58.2\%, 6.6 points above the strongest competing method (DPDMR, 51.6\%) and only 3.2 points below joint training (61.4\%). Per scenario, it improves over the strongest competitor by 4.2 to 7.4 points and closes the gap to joint training to as little as 1.0 point in fault-type classification, while matching it in fault-zone localization. Moreover, it remains the best method when the replay buffer is substantially reduced. These results show that prototype-guided replay is an effective, memory-bounded way to keep fault-diagnosis models up to date as the grid evolves, while validation on field measurements remains a necessary next step.

<p align="right"><a href="#top">(back to top)</a></p>
<div id="usage"></div>


