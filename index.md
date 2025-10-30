---
header:
  overlay_image: unsplash-gallery-image-2.jpg
---

I am a member of technical staff at Microsoft Research. I work on language models (especially the [Phi](https://arxiv.org/pdf/2412.08905) series of language models) and diffusion models theory. 

Before, my research was mostly focused on sampling, optimization and proximal methods. [Here](https://arxiv.org/abs/2304.05398.pdf) is a paper at the intersection of these topics. 

[CV]({{site.baseurl}}{% link CV_Adil_Salim.pdf %})

<!---

in the [Machine Learning Foundations group](https://www.microsoft.com/en-us/research/group/mlog/) at Microsoft Research (Redmond, USA). I currently study diffusion models and large language models.

Previously, I was a Google Research Fellow at the [Simons Institute](https://simons.berkeley.edu/programs/gmos2021), UC Berkeley, USA.

I did my Ph.D at Telecom Paris and Paris--Saclay University, France, under the supervision of [Pascal Bianchi](https://bianchi.wp.imt.fr/) and [Walid Hachem](http://www-syscom.univ-mlv.fr/~whachem/), where I studied optimization. Then, I did a postdoc at KAUST, Saudi Arabia, hosted by [Peter Richtárik](https://richtarik.org/), where I studied sampling (as optimization).  

I received the Masters degrees in 2015 from ENSAE Paris, where I studied statistics, and from Paris--Saclay University, where I studied probability theory. 

--->

## News

- I will talk about diffusion models at [BIRS, Canada](https://www.birs.ca/events/2025/5-day-workshops/25w5430) and [IMS, Singapore](https://ims.nus.edu.sg/events/efficient-sampling-algorithms-complex-models/). Thanks for the invitations!

- I am in Senegal for [MLSS 2025](https://mlss-senegal.github.io/). The energy is awesome!!!

- We released [phi-4](https://arxiv.org/pdf/2412.08905).

- I am a workshop chair at [NeurIPS 2024](https://blog.neurips.cc/2024/08/02/announcing-the-neurips-2024-workshops/).

- [Anna Korba](https://akorba.github.io/) and I have presented a tutorial on Sampling as Optimization at ICML 2022. Here are our [slides]({{site.baseurl}}{% link Research/tuto_icml.pdf %}). You can watch the [video here](https://icml.cc/virtual/2022/tutorial/18437).

## Some papers

### LLMs

- Adil Salim, [Accelerating mathematical research with language models: A case study of an interaction with GPT-5-Pro on a convex analysis problem]({{site.baseurl}}{% link Research/case_study.pdf %}) October 2025.

- Marah Abdin *et al.*, "[Phi-4 Technical Report](https://arxiv.org/pdf/2412.08905)", December 2024.

- Marah Abdin *et al.*, "[Phi-3 Technical Report](https://arxiv.org/pdf/2404.14219)", April 2024.

- Suriya Gunasekar, Yi Zhang *et al.*, "[Textbooks Are All You Need](https://arxiv.org/pdf/2306.11644.pdf)", June 2023.

### Diffusion models and sampling

- Sitan Chen, Sinho Chewi, Holden Lee, Yuanzhi Li, Jianfeng Lu and Adil Salim, "[The probability flow ODE is provably fast](https://arxiv.org/pdf/2305.11798.pdf)", _NeurIPS 2023_.


- Sitan Chen, Sinho Chewi, Jerry Li, Yuanzhi Li, Adil Salim and Anru R. Zhang, "[Sampling is as easy as learning the score: theory for
diffusion models with minimal data assumptions](https://arxiv.org/pdf/2209.11215.pdf)", **Notable top 5% paper** @ _ICLR 2023_, Kigali, Rwanda.

- Adil Salim, Lukang Sun, Peter Richtárik, "[A Convergence Theory for SVGD in the Population Limit under Talagrand’s Inequality T1](https://arxiv.org/pdf/2106.03076.pdf)", _ICML 2022_.


- Anna Korba, Adil Salim, Michael Arbel, Giulia Luise and Arthur Gretton, "[A Non-Asymptotic Analysis for Stein Variational Gradient Descent](https://arxiv.org/abs/2006.09797)", _NeurIPS 2020_. 

### Proximal methods in optimization and sampling

- Michael Diao, Krishnakumar Balasubramanian, Sinho Chewi, Adil Salim, "[Forward-Backward Gaussian Variational Inference
via JKO in the Bures–Wasserstein Space](https://arxiv.org/abs/2304.05398.pdf)", _ICML 2023_.


- Yongxin Chen, Sinho Chewi, Adil Salim, Andre Wibisono, "[Improved analysis for a proximal algorithm for sampling](https://arxiv.org/abs/2202.06386.pdf)", _COLT 2022_.


- Adil Salim, Laurent Condat, Dmitry Kovalev and Peter Richtárik, "[An Optimal Algorithm for Strongly Convex Minimization under Affine Constraints](https://arxiv.org/abs/2102.11079)", _AISTATS 2022_.


- Adil Salim and Peter Richtárik, "[Primal Dual Interpretation of the Proximal Stochastic Gradient Langevin Algorithm](https://arxiv.org/abs/2006.09270)", _NeurIPS 2020_.



- Dmitry Kovalev, Adil Salim and Peter Richtárik, "[Optimal and Practical Algorithms for Smooth and Strongly Convex Decentralized Optimization](https://arxiv.org/abs/2006.11773)", _NeurIPS 2020_.


- Adil Salim, Anna Korba and Giulia Luise, "[The Wasserstein Proximal Gradient Algorithm](https://arxiv.org/abs/2002.03035)", _NeurIPS 2020_. 





<!---

### [Sampling and optimal transport](http://www2.stat.duke.edu/~sayan/ambrosio.pdf)

- Sitan Chen, Sinho Chewi, Jerry Li, Yuanzhi Li, Adil Salim and Anru R. Zhang, "[Sampling is as easy as learning the score: theory for
diffusion models with minimal data assumptions]({{site.baseurl}}{% link Research/score22.pdf %})", **Notable top 5% paper** @ _ICLR 2023_.

- Yongxin Chen, Sinho Chewi, Adil Salim, Andre Wibisono, "[Improved analysis for a proximal algorithm for sampling](https://arxiv.org/abs/2202.06386.pdf)", _COLT 2022_.

- Adil Salim, Lukang Sun, Peter Richtárik, "[A Convergence Theory for SVGD in the Population Limit under Talagrand’s Inequality T1](https://arxiv.org/pdf/2106.03076.pdf)", _ICML 2022_.


- Anna Korba, Adil Salim, Michael Arbel, Giulia Luise and Arthur Gretton, "[A Non-Asymptotic Analysis for Stein Variational Gradient Descent](https://arxiv.org/abs/2006.09797)", _NeurIPS 2020_. 

- Adil Salim and Peter Richtárik, "[Primal Dual Interpretation of the Proximal Stochastic Gradient Langevin Algorithm](https://arxiv.org/abs/2006.09270)", _NeurIPS 2020_. 

- Adil Salim, Anna Korba and Giulia Luise, "[The Wasserstein Proximal Gradient Algorithm](https://arxiv.org/abs/2002.03035)", _NeurIPS 2020_. 

- Adil Salim, Dmitry Kovalev and Peter Richtárik, "[Stochastic Proximal Langevin Algorithm: Potential Splitting and Nonasymptotic Rates]({{site.baseurl}}{% link Research/langevin19.pdf %})", **Spotlight** @ _NeurIPS 2019_, Vancouver, Canada.

- Michael Arbel, Anna Korba, Adil Salim and Arthur Gretton, "[Maximum Mean Discrepancy Gradient Flow](https://arxiv.org/abs/1906.04370)", _NeurIPS 2019_, Vancouver, Canada.


### [Optimization and monotone operators](https://www.sciencedirect.com/bookseries/north-holland-mathematics-studies/vol/5)



- Michael Diao, Krishnakumar Balasubramanian, Sinho Chewi, Adil Salim, "[Forward-Backward Gaussian Variational Inference
via JKO in the Bures–Wasserstein Space](https://arxiv.org/abs/2304.05398.pdf)", _ICML 2023_.

- Sinho Chewi, Sébastien Bubeck and Adil Salim, "[On the complexity of finding stationary points of smooth functions in one dimension](https://arxiv.org/pdf/2209.07513.pdf)", **Best student paper award** @ _ALT 2023_. 

- Adil Salim, Laurent Condat, Dmitry Kovalev and Peter Richtárik, "[An Optimal Algorithm for Strongly Convex Minimization under Affine Constraints](https://arxiv.org/abs/2102.11079)", _AISTATS 2022_.


- Dmitry Kovalev, Adil Salim and Peter Richtárik, "[Optimal and Practical Algorithms for Smooth and Strongly Convex Decentralized Optimization](https://arxiv.org/abs/2006.11773)", _NeurIPS 2020_.


- Adil Salim, [A Strong Law of Large Numbers for Random Monotone Operators](https://arxiv.org/abs/1910.04405), October 2019. 

- Pascal Bianchi, Walid Hachem and Adil Salim, [A Fully Stochastic Primal-Dual Algorithm]({{site.baseurl}}{% link Research/pridu19.pdf %}), _Optimization Letters_, June 2020. 

- Pascal Bianchi, Walid Hachem, and Adil Salim, [Constant Step Stochastic Approximations Involving Differential Inclusions: Stability, Long-Run Convergence and Applications]({{site.baseurl}}{% link Research/revised_arxiv_dicst.pdf %}), _Stochastics_, May 2018. 

- Adil Salim, Pascal Bianchi, and Walid Hachem, [Snake: a Stochastic Proximal Gradient Algorithm for Regularized Problems over Large Graphs]({{site.baseurl}}{% link Research/snake18.pdf %}), _Transaction on Automatic Control_, March 2018.

- Pascal Bianchi, Walid Hachem, and Adil Salim, [A constant step Forward-Backward algorithm involving random maximal monotone operators]({{site.baseurl}}{% link Research/joca1813_revised.pdf %}), _Journal of Convex Analysis_, March 2018.

--->
