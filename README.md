# Understanding Drivers of Climate Extremes Using Regime-specific Causal Graphs
The goal of this tutorial is to show how we can use methods from constraint-based causal discovery to uncover the causal relationships that are present in different moisture regimes. In doing that, we aim to improve our general understanding of the dynamics of extreme events, with application to understanding drivers of soil-moisture under different, more extreme, regimes.

Authors:
*   Oana-Iuliana Popescu, [1], oana.iuliana.popescu@gmail.com
*   Wiebke Günther, [1], [2], wiebke.guenther@dlr.de
*   Raed Hamed, [3], raed.hamed@vu.nl
*   Martin Rabel, [1], martin.rabel@dlr.de 
*   Dim Coumou, [3], d.coumou@vu.nl
*   Jakob Runge, [2], [1], Jakob.Runge@dlr.de 

[1] German Aerospace Center (DLR), Institute of Data Science, 07745 Jena, Germany\
[2] Technische Universität Berlin, 10623 Berlin, Germany\
[3] Institute for Environmental Studies, Vrije Universiteit Amsterdam, Amsterdam, Netherlands

We thank the XAIDA Project and Martin Hirschi and Dominik Schumacher for making the soil moisture dataset publicly available at https://xaida.eu/reports-datasets/.

Originally presented at ICLR 2024

## Access this tutorial

We recommend executing this notebook in a Colab environment to gain access to GPUs and to manage all necessary dependencies. <a target="_blank" href="https://colab.research.google.com/github/climatechange-ai-tutorials/climate-extremes-regime/blob/main/understanding_regimes.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Estimated time to execute end-to-end: 20 minutes 

## Contribute to this tutorial

Please refer to these [GitHub instructions](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) to open a pull request via the "fork and pull request" workflow. 

Pull requests will be reviewed by members of the Climate Change AI Tutorials team for relevance, accuracy, and conciseness.

## Climate Change AI Tutorials
Check out the [tutorials page](https://www.climatechange.ai/tutorials?) on our website for a full list of tutorials demonstrating how AI can be used to tackle problems related to climate change.

## License
The code for RPCMCI (rpcmc.py) was adapted from Tigramite (original authors: Elena Saggioro, Sagar Simha, Matthias Bruhns, Jakob Runge).
We included functionality for missing data and made parallelization optional (Authors: Oana Popescu, Wiebke Günther).
This adapted code for RPCMCI is published under the GNU General Public License v3.0.

The tutorial notebook is published under MIT license.

## Cite

### Plain Text
Popescu, O. & Günther, W. & Hamed, R. & Rabel, M. & Coumou, D. and Runge, J. (2024). Understanding Drivers of Climate Extremes Using Regime-specific Causal Graphs [Tutorial]. In International Conference on Learning Representations. Climate Change AI.

### BibTeX

```
@misc{popescu2024understanding,
  title={Understanding Drivers of Climate Extremes Using Regime-specific Causal Graphs},
  author={Popescu, Oana-Iuliana and Günther, Wiebke and Hamed, Raed and Rabel, Martin and Coumou, Dim and Runge, Jakob},
  year={2024},
  organization={Climate Change AI},
  type={Tutorial},
  doi={},
  booktitle={International Conference on Learning Representations},
  howpublished={\url{https://github.com/climatechange-ai-tutorials/climate-extremes-regime}}
}
```
