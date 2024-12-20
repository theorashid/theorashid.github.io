# Theo Rashid

## about
### 
I am a statistician (applied scientist, data scientist, machine learning person, etc.). I am interested in Bayesian statistics, probabilistic programming, spatiotemoporal models, forecasting, and generative modelling.

I have worked at Amazon implementing multivariate, probabilistic time series models to forecast product demand, at [Faculty](https://faculty.ai/) building LLM applications, as well as several [freelance jobs](https://theorashid.github.io/cv/). I completed my PhD at Imperial College London looking at small-area trends in mortality in England using scalable Bayesian models, supervised by [Majid Ezzati](https://www.imperial.ac.uk/people/majid.ezzati), [James Bennett](https://www.imperial.ac.uk/people/umahx99) and [Seth Flaxman](https://sethrf.com). Before that, I studied theoretical physics, also at Imperial College, so I like any excuse to dig into the maths to speed up and scale Bayesian models (e.g. conjugate Gibbs samplers).

I'm keen to meet with anyone to chat about forecasting/maths/cricket or anything you're working on that you think might interest me. If you're in London – or if you want to invite me to your part of the world – contact me using the links in the footer.

![jacket](../media/jacket.webp)
![baseball](../media/baseball.webp)

## work
### code
[numpyro](https://github.com/pyro-ppl/numpyro). Several contributions, including an [example on spatiotemporal modelling](https://github.com/pyro-ppl/numpyro/pull/1295), and the [conditional autoregressive distribution](https://github.com/pyro-ppl/numpyro/pull/1394).
[pymc](https://github.com/pymc-devs/pymc). Several contributions, including [Hilbert space approximations to the periodic Gaussian process kernel](https://github.com/pymc-devs/pymc/pull/6877), decorator to allow a [functional-style model API](https://github.com/pymc-devs/pymc-extras/pull/268), some [moments of probability distributions](https://github.com/pymc-devs/pymc/pull/5163), extra [GitHub workflows](https://github.com/pymc-devs/pymc/pull/5490), organising hackathons to [implement approximate inference methods](https://github.com/pymc-devs/pymc-extras/issues/340) (INLA).
[pytensor](https://github.com/pymc-devs/pytensor)/[aesara](https://github.com/aesara-devs/aesara). Half-Normal and Half-Cauchy [jax distributions](https://github.com/aesara-devs/aesara/pull/1362), implementation of a [fixed point iterator](https://github.com/pymc-devs/pytensor/pull/978) for optimisation.
[bayeux](https://github.com/jax-ml/bayeux). [Example on using bayeux](https://github.com/jax-ml/bayeux/pull/28) to massively reduce [blackjax](https://github.com/blackjax-devs/blackjax) boilerplate inference code for a (jax) [dynamax](https://github.com/probml/dynamax) state space model.
[GPJax](https://github.com/JaxGaussianProcesses/GPJax). [Allowing different solve methods](https://github.com/JaxGaussianProcesses/GPJax/pull/478) during approximate sampling.
[Journal of Open Source Software](https://github.com/openjournals/joss-reviews). [Review of the GPJax package](https://github.com/openjournals/joss-reviews/issues/4455).
[probabilistic-programming-packages](https://github.com/theorashid/probabilistic-programming-packages). Implementing the same forecasting model in many probabilistic programming languages in python, R and Julia.
[mortality-statsmodel](https://github.com/theorashid/mortality-statsmodel). Scalable hierarchical Bayesian models for modelling mortality over space and time, in nimble and numpyro. These models have been generalised to other health outcomes in [bayesian-envhealth-models](https://github.com/sparklabnyc/bayesian-envhealth-models).
[cookiecutter-r-project](https://github.com/sparklabnyc/cookiecutter-r-project). Template for analysis projects in R.
[numba-oslo](https://github.com/theorashid/numba-oslo). Simulating self-organised criticality efficiently using numba.
[xarray-tropical-cyclones](https://github.com/theorashid/xarray-tropical-cyclones). Revisiting tropical cyclone data using arrays.

I'm also interested in [blackjax](https://github.com/blackjax-devs/blackjax), [dynamax](https://github.com/probml/dynamax), [nimble](https://github.com/nimble-dev/nimble), and would like to contribute more when I get some time. If you're a developer of one of those projects and have something I can work on, please get in touch.

I have moved my (more technical) Obsidian [notes](https://theorashid.github.io/notes/) online in an effort to learn in public and share knowledge.

### visualisations
[Life expectancy for 6,791 communities in England](https://equitablehealthycities.org/focus-cities/london/mortality-map-england/). Interactive map of small-area life expectancy in England, written in D3.js.

Life expectancy inequality at the MSOA level in England: remaking the main plot of my thesis in [D3.js](https://observablehq.com/d/79152026daedf243) and [Observable Plot](https://observablehq.com/d/3f751f12d7efb15c).

### media
[Why are Americans dying so young?](https://www.ft.com/content/653bbb26-8a22-4db3-b43d-c34a0b774303) John Burn-Murdoch, The Financial Times. 31 March 2023.

[Decades-long drop in life expectancy leaves the North more exposed to Covid](https://www.telegraph.co.uk/news/2021/10/12/decades-long-drop-life-expectancy-leaves-north-exposed-covid/). Sarah Knapton, The Telegraph. 12 October 2021.

Also on life expectancy in England: Polly Toynbee for [the Guardian](https://www.theguardian.com/commentisfree/2021/oct/15/tory-austerity-deaths-cut-human-cost-cruel-policy), Danny Dorling for [openDemocracy](https://www.opendemocracy.net/en/nhs-a-and-e-delays-austerity-emergency-care-hospitals-hunt-hancock-lansley/), [the FT](https://www.ft.com/content/3d25b1c9-33bf-448a-bb07-6a0fc3a8a603), [BBC News](https://www.bbc.co.uk/news/uk-58893328), [Daily Mail](https://www.dailymail.co.uk/health/article-10084055/Life-expectancy-falling-fifth-English-communities-Covid-struck.html), [Evening Standard](https://www.standard.co.uk/news/uk/england-life-expectancy-imperial-college-london-government-london-b960199.html), [Independent](https://www.independent.co.uk/news/health/northern-england-life-expectancy-decline-b1937537.html), [Metro](https://metro.co.uk/2021/10/13/life-expectancy-varies-by-nearly-30-years-depending-on-where-you-live-in-england-15412913/), [Sky News](https://news.sky.com/story/life-expectancy-declines-in-england-before-covid-hit-with-big-north-south-divide-new-data-shows-12432798), [politics.co.uk](https://www.politics.co.uk/news-in-brief/life-expectancy-declined-in-parts-of-the-north-over-past-decade/), and more.

On inequalities in cancer mortality in England: [the Mirror](https://www.mirror.co.uk/news/uk-news/astounding-cancer-death-differences-area-31651311), [the Mail](https://www.dailymail.co.uk/health/article-12850889/England-highest-cancer-death-risk-revealed.html), [the Guardian](https://www.theguardian.com/society/2023/dec/11/risk-of-dying-from-cancer-in-england-varies-hugely-between-regions-say-scientists), [the BMJ](https://www.bmj.com/content/383/bmj.p2925), [the Times](https://www.thetimes.co.uk/article/health-inequality-raises-chance-of-fatal-cancer-70-percent-in-poor-areas-8tq2dmvkh), [the Sun](https://www.thesun.co.uk/health/25023618/areas-england-most-likely-die-cancer/) and [Andrew Marr on LBC](https://twitter.com/ImperialSPH/status/1735339297270636639).

### thesis
[Spatiotemporal modelling of all-cause and cause-specific mortality in England](https://theorashid.github.io/thesis/)
Supervisors: Majid Ezzati, James E Bennett, Seth Flaxman
Examiners: Usama Bilal, Marta Blangiardo, Oliver Ratmann

### publications
Theo Rashid, James E Bennett, et al. (2024). [Mortality from leading cancers in districts of England from 2002 to 2019: a population-based, spatiotemporal study](https://doi.org/10.1016/S1470-2045%2823%2900530-2). The Lancet Oncology.

Ricky Nathvani, Vishwanath D., et al. (2023). [Beyond here and now: Evaluating pollution estimation across space and time from street view images with deep learning](https://doi.org/10.1016/j.scitotenv.2023.166168). Science of The Total Environment.

Seth Flaxman, Charles Whittaker, Elizaveta Semenova, Theo Rashid, et al. (2023). [Assessment of COVID-19 as the underlying cause of death among children and young people aged 0 to 19 years in the US](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2800816). JAMA Network Open.

Theo Rashid, James E Bennett, et al. (2023). [Changes in life expectancy and house prices in London from 2002 to 2019: hyper-resolution spatiotemporal analysis of death registration and real estate data](https://doi.org/10.1016/j.lanepe.2022.100580). The Lancet Regional Health Europe.

Ricky Nathvani, Sierra N Clark, et al. (2022). [Characterisation of urban environment and activity across space and time using street images and deep learning in Accra](https://www.nature.com/articles/s41598-022-24474-1). Scientific Reports.

Perviz Asaria, James E Bennett, Paul Elliott, Theo Rashid, et al. (2022). [Contributions of event rates, pre-hospital deaths and hospital case fatality to variations in myocardial infarction mortality in 326 districts in England: spatial analysis of linked hospitalisation and mortality data](https://www.sciencedirect.com/science/article/pii/S2468266722001086). The Lancet Public Health.

Elizaveta Semenova, Yidan Xu, Adam Howes, Theo Rashid, et al. (2022). [PriorVAE: encoding spatial priors with variational autoencoders for small-area estimation](https://royalsocietypublishing.org/doi/10.1098/rsif.2022.0094). Journal of the Royal Society Interface.

Vasilis Kontis, James E Bennett, Robbie M Parks, Theo Rashid, et al. (2022). [Lessons learned and lessons missed: impact of the coronavirus disease 2019 (COVID-19) pandemic on all-cause mortality in 40 industrialised countries and US states prior to mass vaccination](https://wellcomeopenresearch.org/articles/6-279/v2). Wellcome Open Research.

Theo Rashid, James E Bennett, Christopher J Paciorek, et al. (2021). [Life expectancy and risk of death in 6791 communities in England from 2002 to 2019: high-resolution spatiotemporal analysis of civil registration data](https://doi.org/10.1016/S2468-2667%2821%2900205-X). The Lancet Public Health.

Theo Rashid, Toby Pepperrell (2021). Recentring our economy around wellbeing following the COVID-19 pandemic: A book review of The Case for Degrowth. Journal of Health and Social Sciences.

Toby Pepperrell, Florence Rodgers, et al. (2021). [Making a COVID-19 vaccine that works for everyone: ensuring equity and inclusivity in clinical trials](https://doi.org/10.1080/16549716.2021.1892309). Global Health Action.

Vasilis Kontis, James E Bennett, Theo Rashid, et al. (2020). [Magnitude, demographics and dynamics of the effect of the first wave of the COVID-19 pandemic on all-cause mortality in 21 industrialized countries](https://doi.org/10.1038/s41591-020-1112-0). Nature Medicine.

Shuai Wang, Theo Rashid, Henry Throp, Ralf Toumi (2020). [A Shortening of the Life Cycle of Major Tropical Cyclones](https://doi.org/10.1029/2020GL088589). Geophysical Research Letters.

Vasilis Kontis, James E Bennett, Robbie M Parks, Theo Rashid, et al. (2020). [Age- and sex-specific total mortality impacts of the early weeks of the COVID-19 pandemic in England and Wales: Application of a Bayesian model ensemble to mortality statistics](https://doi.org/10.1101/2020.05.20.20107680). medRxiv.

[google scholar profile](https://scholar.google.com/citations?view_op=list_works&hl=en&user=hoPzFGkAAAAJ)
[mathematics genealogy page](https://genealogy.math.ndsu.nodak.edu/id.php?id=314742)

### goals
![goal](../media/goal.webp)

## [notes](https://theorashid.github.io/notes/)

## [cv](https://theorashid.github.io/cv/)
