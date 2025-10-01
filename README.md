# Tensor Network for Gener Regulatory Networks (TNGRN)
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#attribution">Attribution</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains the code used to infer regulatory relationships between genes using RNA-seq data using tensor networks. The method is described in [arXiv:2509.06891](https://arxiv.org/abs/2509.06891).

The repository is organized as follows:
* _TN_GRN_run.ipnyb_ is a jupyter notebook with the code used for GRN inference. It contains the working example using the database obtained from [NCBI GEO database](https://www.ncbi.nlm.nih.gov/geo/) in the paper.
* _exp_matrix.txt_ is the file containing the data from [NCBI GEO database](https://www.ncbi.nlm.nih.gov/geo/). The juptyer notebook makes use of this file for the analysis.
* _requirements.txt_ is a text file containing the requirements needed for the code to work.

We recommend to create a [virtual environment](https://docs.python.org/3/library/venv.html) and to install the requirements there in order to use the code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact
If you have questions tregarding this repository contact:

* _Olatz Sanz Larrarte_ - osanzl@unav.com
* _Josu Etxezarreta Martinez_ - [@katutxakur](https://x.com/katutxakur) - [@katutxakur.bsky.social](https://bsky.app/profile/katutxakur.bsky.social) - jetxezarreta@unav.es



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ATTRIBUTION -->
## Attribution
Please cite the following article if you use our code or our findings:
```
@article{TNGRN,
    author = {{Sanz Larrarte}, Olatz and {Aizpurua}, Borja and {Dastbasteh}, Reza and {Otxoa}, Ruben M. and {Etxezarreta Martinez}, Josu},
    title = "{Tensor Network based Gene Regulatory Network Inference for Single-Cell Transcriptomic Data}",
    journal = {arXiv},
    pages = {2509.06891},
    archivePrefix = "arXiv",
    primaryClass = "q-bio.MN",
    month = sep,
    year = {2025},
    url ={https://arxiv.org/abs/2509.06891}}
