+++
title = "Reading"
+++

## Technical collectibles from the Internetz

Nassim Taleb & Pasquale Cirrilo: [Tail risk of contagious diseases](https://arxiv.org/abs/2004.08658)

> Applying a modification of Extreme value Theory (thanks to a dual distribution technique by the authors on data over the past 2,500 years, we show that pandemics are extremely fat-tailed in terms of fatalities, with a marked potentially existential risk for humanity.
> Such a macro property should invite the use of Extreme Value Theory (EVT) rather than naive interpolations and expected averages for risk management purposes. An implication is that potential tail risk overrides conclusions on decisions derived from compartmental epidemiological models and similar approaches.

Simon Wood: [Core Statistics](https://www.maths.ed.ac.uk/~swood34/core-statistics-nup.pdf)

> This book is aimed at the numerate reader who has probably taken an introductory statistics and probability course at some stage and would like a brief introduction to the core methods of statistics and how they are applied, not necessarily in the context of standard models

Jennifer Hill: [Bayesian Nonparametric Modeling for Causal Inference](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2010.08162)

> This article proposes a strategy that instead focuses on very flexibly modeling just the response surface using a Bayesian nonparametric modeling procedure, Bayesian Additive Regression Trees (BART). BART has several advantages: it is far simpler to use than many recent competitors, requires less guesswork in model fitting, handles a large number of predictors, yields coherent uncertainty intervals, and fluidly handles continuous treatment variables and missing data for the outcome variable. BART also naturally identifies heterogeneous treatment effects. BART produces more accurate estimates of average treatment effects compared to propensity score matching, propensity-weighted estimators, and regression adjustment in the nonlinear simulation situations examined.

Richard Hahn: [Bayesian regression tree models for causal inference](https://arxiv.org/pdf/1706.09523.pdf)

> This paper presents a novel nonlinear regression model for estimating heterogeneous treatment effects from observational data, geared specifically towards situations with small effect sizes, heterogeneous effects, and strong confounding. Standard nonlinear regression models, which may work quite well for prediction, have two notable weaknesses when used to estimate heterogeneous treatment effects. First, they can yield badly biased estimates of treatment effects when fit to data with strong confounding. The Bayesian causal forest model presented in this paper avoids this problem by directly incorporating an estimate of the propensity function in the specification of the response model, implicitly inducing a covariate-dependent prior on the regression function. Second, standard approaches to response surface modeling do not provide adequate control over the strength of regularization over effect heterogeneity. The Bayesian causal forest model permits treatment effect heterogeneity to be regularized separately from the prognostic effect of control variables, making it possible to informatively "shrink to homogeneity". We illustrate these benefits via the reanalysis of an observational study assessing the causal effects of smoking on medical expenditures as well as extensive simulation studies.

Pennington: [Bayesian model averaging](https://doi.org/10.1007/s11222-017-9767-1)

> We propose an alternative fitting algorithm for BART called BART-BMA, which uses Bayesian model averaging and a greedy search algorithm to obtain a posterior distribution more efficiently than BART for datasets with large p. BART-BMA incorporates elements of both BART and random forests to offer a model-based algorithm which can deal with high-dimensional data. We have found that BART-BMA can be run in a reasonable time on a standard laptop for the “small n large p” scenario which is common in many areas of bioinformatics. We showcase this method using simulated data and data from two real proteomic experiments, one to distinguish between patients with cardiovascular disease and controls and another to classify aggressive from non-aggressive prostate cancer.

Jennifer Starling: [Bayesian methods for complex data structures](https://repositories.lib.utexas.edu/bitstream/handle/2152/85348/STARLING-DISSERTATION-2020.pdf?sequence=1&isAllowed=y)

> This thesis explores novel Bayesian non-parametric regression techniques for
> data with complex structures, developed in response to challenges in women’s health
> and obstetrics. Nearly all pregnancy-related research shares a key statistical issue:
> that most outcomes vary smoothly with gestational age. Models which reflect this
> smoothness aid in interpretability by aligning model choices with clinical knowledge;
> from a statistical perspective, smoothing can reduce variance without inflating bias.
> Existing models tend to smooth over all covariates, or require specification of parametric forms and interactions based on a priori knowledge of maternal and fetal covariates. Current literature does not provide an especially nuanced characterization
> of these functional forms.

Iris Koks: [Latent Dirichlet Allocation](https://repository.tudelft.nl/islandora/object/uuid%3Afaa7cd3f-a946-4685-a36e-d01a15c4159e)

> Topic models can extract the main topics from large data sets such as the review data. One of these is Latent Dirichlet Allocation (LDA). LDA is a hierarchical Bayesian topic model that retrieves topics from text data sets in an unsupervised manner. The method assumes that a topic is assigned to each word in a document (review), and aims to retrieve the topic distribution for each document, and a word distribution for each topic. Using the highest probability words from each topic-word distribution, the content of each topic can be determined, such that the main subjects can be derived. Three methods of inference to obtain the topic and word distributions are considered in this research: Gibbs sampling, Variational methods, and Adam optimization to find the posterior mode. Gibbs sampling and Adam optimization have the best theoretical foundations for their application to LDA. From results on artificial and real data sets, it is concluded that Gibbs sampling has the best performance in terms of robustness and perplexity

Michael Kane: [Stochastic approximation of Polya urn process](http://www.stat.yale.edu/~mjk56/Research/Optimization/OptFinalKane.pdf)

> This paper begins by describing the Polya urn process. Next, distributions
> of ball counts and ball proportions are derived. These derivations should
> provide the reader with an understanding of how urn processes behave.
> After this intuition is developed, a stochastic approximation of the process
> is derived. This way, the relationship between the stochastic results and the
> previously derived results is clear. Finally, a case where the assumptions of
> stochastic approximation may not hold is introduced and an alternative
> solution is described.

Mark Ebden: [Gaussian Processes](https://arxiv.org/abs/1505.02965)

> A gentle introduction to Gaussian processes (GPs). The three parts of the document consider GPs for regression, classification, and dimensionality reduction.

Alessandro Panella: [Nonparametric bayes & Dirichlet proceses](https://www.cs.uic.edu/~apanella/slides/nonparametric_bayes.pdf)

>

Guy Wolf: [Diffusion maps](http://mat6480w.guywolf.org/slides/T12%20-%20Diffusion%20Maps.pdf)

>

Alberto Caron: [Sparse Bayesian Causal Forests](https://arxiv.org/abs/2102.06573)

> This paper develops a sparsity-inducing version of Bayesian Causal Forests, a recently proposed nonparametric causal regression model that employs Bayesian Additive Regression Trees and is specifically designed to estimate heterogeneous treatment effects using observational data. The sparsity-inducing component we introduce is motivated by empirical studies where the number of pre-treatment covariates available is non-negligible, leading to different degrees of sparsity underlying the surfaces of interest in the estimation of individual treatment effects. The extended version presented in this work, which we name Sparse Bayesian Causal Forest, is equipped with an additional pair of priors allowing the model to adjust the weight of each covariate through the corresponding number of splits in the tree ensemble. These priors improve the model's adaptability to sparse settings and allow to perform fully Bayesian variable selection in a framework for treatment effects estimation, and thus to uncover the moderating factors driving heterogeneity. In addition, the method allows prior knowledge about the relevant confounding pre-treatment covariates and the relative magnitude of their impact on the outcome to be incorporated in the model. We illustrate the performance of our method in simulated studies, in comparison to Bayesian Causal Forest and other state-of-the-art models, to demonstrate how it scales up with an increasing number of covariates and how it handles strongly confounded scenarios. Finally, we also provide an example of application using real-world data.

Antonio Ricardo: [Bayesian Regression Tree Ensembles that Adapt to Smoothness and Sparsity](https://arxiv.org/pdf/1707.09461)

> Ensembles of decision trees are a useful tool for obtaining flexible estimates of regression functions. Examples of these methods include gradient-boosted decision trees, random forests and Bayesian classification and regression trees. Two potential shortcomings of tree ensembles are their lack of smoothness and their vulnerability to the curse of dimensionality. We show that these issues can be overcome by instead considering sparsity inducing soft decision trees in which the decisions are treated as probabilistic. We implement this in the context of the Bayesian additive regression trees framework and illustrate its promising performance through testing on benchmark data sets. We provide strong theoretical support for our methodology by showing that the posterior distribution concentrates at the minimax rate (up to a logarithmic factor) for sparse functions and functions with additive structures in the high dimensional regime where the dimensionality of the covariate space is allowed to grow nearly exponentially in the sample size. Our method also adapts to the unknown smoothness and sparsity levels, and can be implemented by making minimal modifications to existing Bayesian additive regression tree algorithms.

Jens Hainmueller: [Kernel Regularized Least Squares: Reducing Misspecification Bias with a Flexible and Interpretable Machine Learning Approach](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2046206)

> We propose the use of Kernel Regularized Least Squares (KRLS) for social science modeling and inference problems. KRLS borrows from machine learning methods designed to solve regression and classification problems without relying on linearity or additivity assumptions. The method constructs a flexible hypothesis space that uses kernels as radial basis functions and finds the best-fitting surface in this space by minimizing a complexity-penalized least squares problem. We argue that the method is well-suited for social science inquiry because it avoids strong parametric assumptions, yet allows interpretation in ways analogous to generalized linear models while also permitting more complex interpretation to examine non-linearities, interactions, and heterogeneous effects. We also extend the method in several directions to make it more effective for social inquiry, by (1) deriving estimators for the pointwise marginal effects and their variances, (2) establishing unbiasedness, consistency, and asymptotic normality of the KRLS estimator under fairly general conditions, (3) proposing a simple automated rule for choosing the kernel bandwidth, and (4) providing companion software. We illustrate the use of the method through simulations and empirical examples.

Igor Braga: [Improving the kernel regularized least squares method for small-sample regression](https://www.sciencedirect.com/science/article/abs/pii/S0925231215003744)

> The kernel regularized least squares (KRLS) method uses the kernel trick to perform non-linear regression estimation. Its performance depends on proper selection of both a kernel function and a regularization parameter. In practice, cross-validation along with the Gaussian RBF kernel have been widely used for carrying out model selection for KRLS. However, when training data is scarce, this combination often leads to poor regression estimation. In order to mitigate this issue, we follow two lines of investigation in this paper. First, we explore a new type of kernel function that is less susceptible to overfitting than the RBF kernel. Then, we consider alternative parameter selection methods that have been shown to perform well for other regression methods. Experiments conducted on real-world datasets show that an additive spline kernel greatly outperforms both the RBF and a previously proposed multiplicative spline kernel. We also find that the parameter selection procedure Finite Prediction Error (FPE) is a competitive alternative to cross-validation when using the additive splines kernel.

António M. Lopes: [Dynamical Analysis of the Dow Jones Index Using Dimensionality Reduction and Visualization](https://www.mdpi.com/1099-4300/23/5/600/html)

> The paper explores the dynamics of multidimensional data generated by a CS. The Dow Jones Industrial Average (DJIA) index is selected as a test-bed. The DJIA time-series is normalized and segmented into several time window vectors. These vectors are treated as objects that characterize the DJIA dynamical behavior. The objects are then compared by means of different distances to generate proper inputs to dimensionality reduction and information visualization algorithms. These computational techniques produce meaningful representations of the original dataset according to the (dis)similarities between the objects. The time is displayed as a parametric variable and the non-locality can be visualized by the corresponding evolution of points and the formation of clusters. The generated portraits reveal a complex nature, which is further analyzed in terms of the emerging patterns.

Mebarka Allaoui: [Considerably Improving Clustering Algorithms Using UMAP Dimensionality Reduction Technique](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7340901/pdf/978-3-030-51935-3_Chapter_34.pdf)

> In this paper, we investigate how to improve the performance of several clustering algorithms using one of the most successful embedding techniques: Uniform Manifold Approximation and Projectionor UMAP. This technique has recently been proposed as a manifold learning technique for dimensionality reduction. It is based on Riemannian geometry and algebraic topology. Our main hypothesis is that UMAP would permit to find the best clusterable embedding manifold, and therefore, we applied it as a preprocessing step before performing clustering.

Qingtao Tang: [Student-t Process Regression with dependent Student-t noise](https://dl.acm.org/doi/pdf/10.3233/978-1-61499-672-9-82)

> Gaussian Process Regression (GPR) is a powerful non-parametric method. However, GPR may perform poorly if the data are contaminated by outliers. To address the issue, we replace the Gaussian process with a Student-t process and introduce dependent Student-t noise in this paper, leading to a Student-t Process Regression with Dependent Student-t noise model (TPRD). Closed form expressions for the marginal likelihood and predictive distribution of TPRD are derived. Besides, TPRD gives a probabilistic interpretation to the Student-t Process Regression with the noise incorporated into its Kernel (TPRK), which is a common approach for the Student-t process regression. Moreover, we analyze the influence of different kernels. If the kernel meets a condition, called β-property here, the maximum marginal likelihood estimation of TPRD’s hyperparameters is independent of the degrees of freedom ν of the Student-t process, which implies that GPR, TPRD and TPRK have exactly the same predictive mean.

Brendan D. Tracey: [Upgrading from Gaussian Processes to Student’s-T Processes](https://arxiv.org/pdf/1801.06147.pdf)

> Gaussian process priors are commonly used in aerospace design for performing Bayesian optimization. Nonetheless, Gaussian processes suffer two significant drawbacks: outliers are a priori assumed unlikely, and the posterior variance conditioned on observed data depends only on the locations of those data, not the associated sample values. Student's-T processes are a generalization of Gaussian processes, founded on the Student's-T distribution instead of the Gaussian distribution. Student's-T processes maintain the primary advantages of Gaussian processes (kernel function, analytic update rule) with additional benefits beyond Gaussian processes. The Student's-T distribution has higher Kurtosis than a Gaussian distribution and so outliers are much more likely, and the posterior variance increases or decreases depending on the variance of observed data sample values. Here, we describe Student's-T processes, and discuss their advantages in the context of aerospace optimization. We show how to construct a Student's-T process using a kernel function and how to update the process given new samples. We provide a clear derivation of optimization-relevant quantities such as expected improvement, and contrast with the related computations for Gaussian processes. Finally, we compare the performance of Student's-T processes against Gaussian process on canonical test problems in Bayesian optimization, and apply the Student's-T process to the optimization of an aerostructural design problem.

David Duvenaud: [Additive Gaussian Processes](https://arxiv.org/pdf/1112.4394.pdf)

> We introduce a Gaussian process model of functions which are additive. An additive function is one which decomposes into a sum of low-dimensional functions, each depending on only a subset of the input variables. Additive GPs generalize both Generalized Additive Models, and the standard GP models which use squared-exponential kernels. Hyperparameter learning in this model can be seen as Bayesian Hierarchical Kernel Learning (HKL). We introduce an expressive but tractable parameterization of the kernel function, which allows efficient evaluation of all input interaction terms, whose number is exponential in the input dimension. The additional structure discoverable by this model results in increased interpretability, as well as state-of-the-art predictive power in regression tasks.

David Duvenaud: [Kernel Cookbook](https://www.cs.toronto.edu/~duvenaud/cookbook/)

Cagatay Yildiz [LEARNING STOCHASTIC DIFFERENTIAL EQUATIONS WITH GAUSSIAN PROCESSES WITHOUT GRADIENT MATCHING](https://arxiv.org/pdf/1807.05748.pdf)

> We introduce a novel paradigm for learning non-parametric drift and diffusion functions for stochastic differential equation (SDE). The proposed model learns to simulate path distributions that match observations with non-uniform time increments and arbitrary sparseness, which is in contrast with gradient matching that does not optimize simulated responses. We formulate sensitivity equations for learning and demonstrate that our general stochastic distribution optimisation leads to robust and efficient learning of SDE systems.

Pable Padila [Pricing American Options Using Transition Probabilities: A Dynamical Systems Approach](https://www.scirp.org/journal/paperinformation.aspx?paperid=60395)

> We give a new way to price American options by using Samuelson’s formula. We first obtain the option price corresponding to a European option at time t, weighing it by the probability that the underlying asset takes the value S at time t. We then use Samuelson’s formula with this factor which is given by the solution of the Fokker-Planck (Kolmogorov) equation for the transition probability density. The main advantage of this approach is that we can systematically introduce the effect of macroeconomic factors. If a macroeconomic framework is given by a dynamical system in the form of a set of ordinary differential equations we only have to solve a partial differential equation for the transition probability density. In this context, we verify, for the sake of consistency, that this formula coincides with the Black-Scholes model and compare several numerical implementations.

Jussi Lindgren [Efficient Markets and Contingent Claims Valuation: An Information Theoretic Approach](https://www.mdpi.com/1099-4300/22/11/1283)

> This research article shows how the pricing of derivative securities can be seen from the context of stochastic optimal control theory and information theory. The financial market is seen as an information processing system, which optimizes an information functional. An optimization problem is constructed, for which the linearized Hamilton–Jacobi–Bellman equation is the Black–Scholes pricing equation for financial derivatives. The model suggests that one can define a reasonable Hamiltonian for the financial market, which results in an optimal transport equation for the market drift. It is shown that in such a framework, which supports Black–Scholes pricing, the market drift obeys a backwards Burgers equation and that the market reaches a thermodynamical equilibrium, which minimizes the free energy and maximizes entropy.

Lisandro Kaunitz, Shenjun Zhong, Javier Kreiner [Beating the bookies with their own numbers - and how the online sports betting market is rigged](https://arxiv.org/abs/1710.02824)

> The online sports gambling industry employs teams of data analysts to build forecast models that turn the odds at sports games in their favour. While several betting strategies have been proposed to beat bookmakers, from expert prediction models and arbitrage strategies to odds bias exploitation, their returns have been inconsistent and it remains to be shown that a betting strategy can outperform the online sports betting market. We designed a strategy to beat football bookmakers with their own numbers. Instead of building a forecasting model to compete with bookmakers predictions, we exploited the probability information implicit in the odds publicly available in the marketplace to find bets with mispriced odds. Our strategy proved profitable in a 10-year historical simulation using closing odds, a 6-month historical simulation using minute to minute odds, and a 5-month period during which we staked real money with the bookmakers (we made code, data and models publicly available). Our results demonstrate that the football betting market is inefficient - bookmakers can be consistently beaten across thousands of games in both simulated environments and real-life betting. We provide a detailed description of our betting experience to illustrate how the sports gambling industry compensates these market inefficiencies with discriminatory practices against successful clients.

Tianqi Chen, Emily B. Fox, Carlos Guestrin [Stochastic Gradient Hamiltonian Monte Carlo](https://arxiv.org/abs/1402.4102)

> Hamiltonian Monte Carlo (HMC) sampling methods provide a mechanism for defining distant proposals with high acceptance probabilities in a Metropolis-Hastings framework, enabling more efficient exploration of the state space than standard random-walk proposals. The popularity of such methods has grown significantly in recent years. However, a limitation of HMC methods is the required gradient computation for simulation of the Hamiltonian dynamical system-such computation is infeasible in problems involving a large sample size or streaming data. Instead, we must rely on a noisy gradient estimate computed from a subset of the data. In this paper, we explore the properties of such a stochastic gradient HMC approach. Surprisingly, the natural implementation of the stochastic approximation can be arbitrarily bad. To address this problem we introduce a variant that uses second-order Langevin dynamics with a friction term that counteracts the effects of the noisy gradient, maintaining the desired target distribution as the invariant distribution. Results on simulated data validate our theory. We also provide an application of our methods to a classification task using neural networks and to online Bayesian matrix factorization.

John Felllingham:[Accounting as an information science](https://cpb-us-w2.wpmucdn.com/u.osu.edu/dist/5/39171/files/2016/10/acctg-info-science-revision-7-30-17-10zo2pn.pdf)

> The paper is a modest attempt at a positive answer to the question about
> accounting being an information science. The main result is that accounting
> numbers are a statement about how much information the reporting entity has
> access to. We do not analyze the communication of the details of the information
> available to the reporting entity; the entity conveys a measure of the amount
> of information they hold, not the information itself. The metric for amount of
> information is Shannon entropyó a function of probabilities (Shannon 1948).
> Shannonís entropy concept has ampliÖed the importance of information, as it
> can be treated as a commodity to be accumulated, modiÖed, and transferred;
> a commodity as important as energy or mass for descriptive content. Some
> other sciences are routinely referred to as "information sciences," physics, for
> example, where quantum information is a central idea. Biology, as well, studies
> the information content of the genetic code. The title of the paper questions
> whether accounting is properly included as a similar and complementary scientiÖc inquiry.

Ulf Aslak:[Scales of human mobility](https://www.nature.com/articles/s41586-020-2909-1)

Esteban Moro:[Resilience patterns in labor markets](https://www.nature.com/articles/s41467-021-22086-3.pdf)

> In this paper, we model labor market resilience with an ecologically-inspired job network constructed from the similarity of occupations’ skill requirements. This framework reveals that the economic resilience of cities is universally and uniquely determined by the connectivity within a city’s job network. US cities with greater job connectivity experienced lower unemployment during the Great Recession. Further, cities that increase their job connectivity see increasing wage bills, and workers of embedded occupations enjoy higher wages than their peers elsewhere. Finally, we show how job connectivity may clarify the augmenting and deleterious impact of automation in US cities. Policies that promote labor connectivity may grow labor markets and promote economic resilience.

Andrew Gordon Wilson: [Deep Kernel Learning](https://arxiv.org/abs/1511.02222)

> We introduce scalable deep kernels, which combine the structural properties of deep learning architectures with the non-parametric flexibility of kernel methods. Specifically, we transform the inputs of a spectral mixture base kernel with a deep architecture, using local kernel interpolation, inducing points, and structure exploiting (Kronecker and Toeplitz) algebra for a scalable kernel representation. These closed-form kernels can be used as drop-in replacements for standard kernels, with benefits in expressive power and scalability. We jointly learn the properties of these kernels through the marginal likelihood of a Gaussian process. Inference and learning cost O(n) for n training points, and predictions cost O(1) per test point. On a large and diverse collection of applications, including a dataset with 2 million examples, we show improved performance over scalable Gaussian processes with flexible kernel learning models, and stand-alone deep architectures.

Roger Farmer:[Self-Fulfilling Prophecies, Quasi Non-Ergodicity & Wealth Inequality](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3753978)

> We construct a model where people trade assets contingent on an observable signal that reflects public opinion. The agents in our model are replaced occasionally and each person updates beliefs in response to observed outcomes. We show that the distribution of the observed signal is described by a quasi non-ergodic process and that people continue to disagree with each other forever. Our model generates large wealth inequalities that arise from the multiplicative nature of wealth dynamics which makes successful bold bets highly profitable. The flip side of this statement is that unsuccessful bold bets are ruinous and lead the person who makes such bets into poverty. People who agree with the market belief have a low expected subjective gain from trading. People who disagree may either become spectacularly rich, or spectacularly poor.

Gunduz Caginalp: [Fat tails arise endogenously in asset prices from supply/demand, with or without jump processes](https://arxiv.org/abs/2011.08275)

> We show that the quotient of Levy processes of jump-diffusion type has a fat-tailed distribution. An application is to price theory in economics. We show that fat tails arise endogenously from modeling of price change based on an excess demand analysis resulting in a quotient of arbitrarily correlated demand and supply whether or not jump discontinuities are present. The assumption is that supply and demand are described by drift terms, Brownian (i.e., Gaussian) and compound Poisson jump processes. If P−1dP/dt (the relative price change in an interval dt) is given by a suitable function of relative excess demand, $\left( \mathcal{D}% -\mathcal{S}\right) /\mathcal{S}$ (where D and S are demand and supply), then the distribution has tail behavior F(x)∼x−ζ for a power ζ that depends on the function G in P−1dP/dt=G(D/S). For G(x)∼|x|1/q one has ζ=q. The empirical data for assets typically yields a value, ζ=~3, or ζ∈[3,5] for some markets.
> The discrepancy between the empirical result and theory never arises if one models price dynamics using basic economics methodology, i.e., generalized Walrasian adjustment, rather than the usual starting point for classical finance which assumes a normal distribution of price changes. The function G is deterministic, and can be calibrated with a smaller data set. The results establish a simple link between the decay exponent of the density function and the price adjustment function, a feature that can improve methodology for risk assessment.
> The mathematical results can be applied to other problems involving the relative difference or quotient of Levy processes of jump-diffusion type.

Juan MR Parrondo: [Continuous time markov chains](https://3709847b-381c-4df6-b3c2-ae934f357bfd.filesusr.com/ugd/c7de9f_fdb940fff0aa4f2f82bf0b62b124317a.pdf)

> 1.Probability distributions and
> densities.
> 2.Relevant distributions.
> 3.Change of variable.
> 4.Stochastic processes.
> 5.The Markov property.
> 6.Markov finite chains.
> 7.Evolution equation.
> 8.Transient and stationary regimes.
> 9.A simple example

Thomas Seyfried:[Cancer as a metabolic disease](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3941741/)

> Emerging evidence indicates that cancer is primarily a metabolic disease involving disturbances in energy production through respiration and fermentation. The genomic instability observed in tumor cells and all other recognized hallmarks of cancer are considered downstream epiphenomena of the initial disturbance of cellular energy metabolism. The disturbances in tumor cell energy metabolism can be linked to abnormalities in the structure and function of the mitochondria. When viewed as a mitochondrial metabolic disease, the evolutionary theory of Lamarck can better explain cancer progression than can the evolutionary theory of Darwin. Cancer growth and progression can be managed following a whole body transition from fermentable metabolites, primarily glucose and glutamine, to respiratory metabolites, primarily ketone bodies. As each individual is a unique metabolic entity, personalization of metabolic therapy as a broad-based cancer treatment strategy will require fine-tuning to match the therapy to an individual’s unique physiology.

Kshitiz [Evolution of placental invasion and cancer metastasis are causally linked](https://www.nature.com/articles/s41559-019-1046-4)

> Among mammals, placental invasion is correlated with vulnerability to malignancy. Animals with more invasive placentation (for example, humans) are more vulnerable to malignancy. To explain this correlation, we propose the hypothesis of ‘Evolved Levels of Invasibility’ proposing that the evolution of invasibility of stromal tissue affects both placental and cancer invasion. We provide evidence for this using an in vitro model. We find that bovine endometrial and skin fibroblasts are more resistant to invasion than are their human counterparts. Gene expression profiling identified genes with high expression in human but not in bovine fibroblasts. Knocking down a subset of them in human fibroblasts leads to stronger resistance to cancer cell invasion. Identifying the evolutionary determinants of stromal invasibility can provide important insights to develop rational antimetastatic therapeutics.

Brian Arthur: [Foundations of complexity economics](https://www.nature.com/articles/s42254-020-00273-3)

> Conventional, neoclassical economics assumes perfectly rational agents (firms, consumers, investors) who face well-defined problems and arrive at optimal behaviour consistent with — in equilibrium with — the overall outcome caused by this behaviour. This rational, equilibrium system produces an elegant economics, but is restrictive and often unrealistic. Complexity economics relaxes these assumptions. It assumes that agents differ, that they have imperfect information about other agents and must, therefore, try to make sense of the situation they face. Agents explore, react and constantly change their actions and strategies in response to the outcome they mutually create. The resulting outcome may not be in equilibrium and may display patterns and emergent phenomena not visible to equilibrium analysis. The economy becomes something not given and existing but constantly forming from a developing set of actions, strategies and beliefs — something not mechanistic, static, timeless and perfect but organic, always creating itself, alive and full of messy vitality.

Jesse Perla, Thomas J. Sargent and John Stachurski: [Quantitative Economics with Julia](https://julia.quantecon.org/)

> This website presents a set of lectures on quantitative economic modeling, designed and written by Jesse Perla, Thomas J. Sargent and John Stachurski. The language instruction is Julia.

Umberto Picchini : [Approximate Bayesian Computing](https://www.maths.lu.se/fileadmin/maths/forskning_research/InferPartObsProcess/abc_slides.pdf)

> In this lecture we consider the case where it is not possible to pursue
> exact inference for model parameters θ, nor it is possible to
> approximate the likelihood function of θ within a given computational
> budget and available time

David Salazar's blog : [Bayesian Instrumental Variable Regression](https://david-salazar.github.io/2020/06/03/bayesian-instrumental-variable-regression/)

> Hi! My name is David Salazar an I am dilettant’n my way into understanding Machine Learning and Data Science in general.

Eric K Zhang : [Statistics 210: Probability I](https://www.ekzhang.com/assets/pdf/Stat_210_Notes.pdf)

> These are notes for Harvard’s Statistics 210, a graduate-level probability class providing foundational material for statistics PhD students, as taught by Joe Blitzstein1 in Fall 2020. It has a history as a long-running statistics requirement at Harvard. We will focus on probability topics applicable to statistics, with a lesser focus on measure theory

Ying Nian Wu : [A Note on Probability Theory](http://www.stat.ucla.edu/~ywu/STATS200AProbability.pdf)

> Notes for STAT200A

Pablo Caceres : [Introduction to Linear Algebra for Applied Machine Learning with Python](https://pabloinsente.github.io/intro-linear-algebra)

> This document contains introductory level linear algebra notes for applied machine learning. It is meant as a reference rather than a comprehensive review. If you ever get confused by matrix multiplication, don’t remember what was the L2 norm, or the conditions for linear independence, this can serve as a quick reference. It also a good introduction for people that don’t need a deep understanding of linear algebra, but still want to learn about the fundamentals to read about machine learning or to use pre-packaged machine learning solutions. Further, it is a good source for people that learned linear algebra a while ago and need a refresher

Magnus Wiktorsson:[Valuation of derivative assets](https://canvas.education.lu.se/courses/7379)

> Course goals
> To provide a thorough understanding and insight in the economical and mathematical considerations which underly the valuation of derivatives on financial markets. To provide knowledge about and ability to handle, the models and mathematical tools that are used in financial mathematics. To give a thorough overview concerning the most important types of financial contracts used on the stock- and the interest rate markets and moreover to provide a solid base for understanding contracts that have not been explicitely treated in the course

John Bullinaria:[Data Structures and Algorithms](https://www.cs.bham.ac.uk/~jxb/dsa.html)

> This module will introduce the principal fundamental data structures and algorithms used in computer science. Data structures will be formulated to represent information in such a way that it can be conveniently and efficiently manipulated by the algorithms that are developed. The ideas will be presented abstractly, although examples will be given in the language used in the programming workshop module

Ashenafi A. Yirga[Negative binomial mixed models for analyzing longitudinal CD4 count data](https://www.nature.com/articles/s41598-020-73883-7)

> This paper’s main contribution is the inclusion of the links between CD4 cell count and influencing covariates of biometric and demographic factors. Therefore, this study aims to cope with the statistical challenges of over-dispersion and incorporate within-subject correlation structures by applying NBMMs to longitudinal CD4 count data from the CAPRISA 002 AI Study and also detecting factors that are significantly associated with the response variable.

Ole Peters, Alexander Adamou[The sum of log-normal variates in geometric Brownian motion](https://arxiv.org/abs/1802.02939)

> Trajectories of GBM are distributed according to the well-known log-normal density, broadening with time. However, in many applications, what's of interest is not a single trajectory but the sum, or average, of several trajectories. The distribution of these objects is more complicated. Here we show two different ways of finding their typical trajectories. We make use of an intriguing connection to spin glasses: the expected free energy of the random energy model is an average of log-normal variates. We make the mapping to GBM explicit and find that the free energy result gives qualitatively correct behavior for GBM trajectories. We then also compute the typical sum of lognormal variates using Ito calculus. This alternative route is in close quantitative agreement with numerical work.

Ole Peters, Alexander Adamou[Insurance makes wealth grow faster](https://arxiv.org/abs/1507.04655)

> Voluntary insurance contracts constitute a puzzle because they increase the expectation value of one party's wealth, whereas both parties must sign for such contracts to exist. Classically, the puzzle is resolved by introducing non-linear utility functions, which encode asymmetric risk preferences; or by assuming the parties have asymmetric information. Here we show the puzzle goes away if contracts are evaluated by their effect on the time-average growth rate of wealth. Our solution assumes only knowledge of wealth dynamics. Time averages and expectation values differ because wealth changes are non-ergodic. Our reasoning is generalisable: business happens when both parties grow faster.

Rebecca Abraham, Zhi Tao [The Valuation of Cryptocurrencies in Single-Asset and Multiple-Asset Models](https://www.scirp.org/journal/paperinformation.aspx?paperid=92177)

> Theoretical formulations show that Markowitz models combined with bitcoin, located on the Capital Market Line (which we term CML portfolios), have low returns, mainly due to the presence of the riskless asset. Such portfolios are appropriately suited to the investment goals of risk-averse traders, while overlooking the preferences of risk-takers. To satisfy less risk-averse investors, we propose a high-return portfolio with 9 asset choices, consisting of risky assets, cryptocurrencies, US dollars, soybean futures, Treasury bond futures, oil futures, currency options on the US dollar, currency options on the Mexican peso, and technology, or biotechnology stocks. Laplace transforms are employed to suppress volatility, skewness, or kurtosis of returns, which empirical studies have found to contribute to tail risk contained in outliers in fat-tailed distributions.

Yonatan Berman [The Long Run Evolution of Absolute Intergenerational Mobility](https://www.aeaweb.org/articles?id=10.1257/app.20200631&from=f)

> This paper combines cross-sectional and longitudinal income data to present the evolution of absolute intergenerational income mobility in ten advanced economies in the 20th century. Absolute mobility decreased during the second half of the 20th century in all these countries. Increasing income inequality and decreasing growth rates have both contributed to the decrease. Yet, growth is the dominant contributor in most countries. We show that detailed panel data are effectively unnecessary for estimating absolute mobility over the long run.

Sébastien Farkas [Cyber claim analysis using Generalized Pareto regression trees with applications to insurance](https://www.sciencedirect.com/science/article/abs/pii/S0167668721000330)

> In this paper, we propose a method for cyber claim analysis based on regression trees to identify criteria for claim classification and evaluation. We particularly focus on severe/extreme claims, by combining a Generalized Pareto modeling – legitimate from Extreme Value Theory – and a regression tree approach. Coupled with an evaluation of the frequency, our procedure allows computations of central scenarios and of extreme loss quantiles for a cyber portfolio. Finally, the method is illustrated on a public database.

Robert Chin [Stochastics,Statistics,Skedastics](https://rzch.github.io/pdfs/stochastics-statistics.pdf)

> These are a collection of continuously-evolving notes in probability and statistics, that I started writing as a graduate student. They begin at a high-school or early-undergraduate introduction,and then go on to cover topics mainly from the undergraduate to early-graduate level.

James Hyman [A Poisson Betting Model with a Kelly Criterion Element for European Soccer](https://global-uploads.webflow.com/5f1af76ed86d6771ad48324b/607a445eee46ee3ac33595d3_KushalShah-PoissonBetting-RPpaper.pdf)

> The paper shows how we predicted the number of goals by each team in a game and utilized these predictions to create a Poisson distribution that determined the probability of each event (Win, Lose, Draw). To add another dimension to our model, we used an optimization technique known as Kelly Criterion to determine the optimal amount of money that should be bet on each match. This technique generates bet amounts while also creating a value (KCO Value) that acts as an accurate estimator of the risk associated with each match. By exploring the characteristics of this value, we were able to maximize the success of the model. After running the model for the 2018 and 2019 seasons across the five major European soccer leagues, we can safely say that our model was not only successful in predicting outcomes, but also in generating significant profit yields for a user. A profit percentage of 119.48% can be yielded using this model, which implies that a user would essentially double their money using this model. We also evaluate how the model performs in different leagues to understand which league characteristics benefit the model. The highest profit percentage was seen in the 2019 Bundesliga season with a profit percentage of 226.68%. The success of the model can not only help users generate significant profits, but it can also expose certain inefficiencies in the market.

Bob Carpenter [Typical Sets and the Curse of Dimensionality](https://mc-stan.org/users/documentation/case-studies/curse-dims.html)

> This case study illustrates the so-called “curse of dimensionality,” starting from scratch and using simple examples based on simulation. For example, generating points uniformly at random in a unit hypercube, it is easy to see how the average distance between random points increases with dimensionality. Similarly, such points tend to increasingly fall outside the hypersphere inscribed within the unit hypercube, showing that in higher dimensions, almost all of the volume is in the corners of the hypercube. Similarly, generating standard normal variates (zero mean, unit standard deviation) leads to draws that concentrate in a thin shell of increasing distance from the mean as dimensionality increases. The squared distance of a standard normal draw from the mode follows a standard chi-square distribution with degrees of freedom equal to the dimensionality. This allows the the precise bounds of the thin shell to be calculated using tail statistics, showing just how unlikely it is to get near the mode with a random draw from a standard multivariate normal. These properties of the standard normal distribution provides a segue into discussing the important information-theoretic concept of the typical set for a probability distribution, which is roughly defined as the central log density band into which almost all random draws from that distribution will fall. The rather surprising result is that for a normal distribution in high dimensions, the typical set does not include the volume around the mode. The density is highest around the mode, but the volume is low, and the probability mass is determined as the product of the density and the volume (or more precisely, the integral of the density over the volume).The standard normal log density is just negative squared Euclidean distance, which provides a straightforward demonstration of why the maximum likelihood estimate for a normal regression is identical to the least squares solution.

Jared Wilber [LINEAR REGRESSION A Visual Introduction To (Almost) Everything You Should Know](https://mlu-explain.github.io/linear-regression/)

> Linear Regression is a simple and powerful model for predicting a numeric response from a set of one or more independent variables. This article will focus mostly on how the method is used in machine learning, so we won't cover common use cases like causal inference or experimental design. And although it may seem like linear regression is overlooked in modern machine learning's ever-increasing world of complex neural network architectures, the algorithm is still widely used across a large number of domains because it is effective, easy to interpret, and easy to extend. The key ideas in linear regression are recycled everywhere, so understanding the algorithm is a must-have for a strong foundation in machine learning.

Lilian Weng [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)

> Diffusion models are inspired by non-equilibrium thermodynamics. They define a Markov chain of diffusion steps to slowly add random noise to data and then learn to reverse the diffusion process to construct desired data samples from the noise. Unlike VAE or flow models, diffusion models are learned with a fixed procedure and the latent variable has high dimensionality (same as the original data).

Brandon Rohrer [Transformers from Scratch](https://e2eml.school/transformers.html)

> Transformers were introduced in this 2017 paper as a tool for sequence transduction—converting one sequence of symbols to another. The most popular examples of this are translation, as in English to German. It has also been modified to perform sequence completion—given a starting prompt, carry on in the same vein and style. They have quickly become an indispensible tool for research and product development in natural language processing.

Yang Song[Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.net/blog/2021/score/#reversing-the-sde-for-sample-generation)

> This blog post focuses on a promising new direction for generative modeling. We can learn score functions (gradients of log probability density functions) on a large number of noise-perturbed data distributions, then generate samples with Langevin-type sampling. The resulting generative models, often called score-based generative models, has several important advantages over existing model families: GAN-level sample quality without adversarial training, flexible model architectures, exact log-likelihood computation, and inverse problem solving without re-training models. In this blog post, we will show you in more detail the intuition, basic concepts, and potential applications of score-based generative models.

Information for Gov 2003 at Harvard University [Materials for Gov 2003: Causal Inference with Applications](https://mattblackwell.github.io/gov2003-f21-site/materials.html)

> Lecture notes for Causal Inference with Applications
