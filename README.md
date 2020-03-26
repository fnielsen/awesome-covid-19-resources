# Awesome COVID-19 resources
A curated list of awesome data science, analytics and computer programming resources for COVID-19.

## Datasets 
- [COVID-19 DATABASE: COVID-19: CASISTICA RADIOLOGICA ITALIANA](https://www.sirm.org/category/senza-categoria/covid-19/) - Italian database with CT images of lungs.
- [Coronavirus-Dataset: Dataset of COVID-19 in South Korea](https://www.kaggle.com/kimjihoo/coronavirusdataset) - South Korean dataset detailing virus spread routes.
- [COVID-19 Open Research Dataset (CORD-19)](https://pages.semanticscholar.org/coronavirus-research) - dataset with scholarly articles about COVID-19.
- [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) - geographic distribution of COVID-19 cases worldwide
- [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

### Bioinformatics
- [SARS-CoV-2 and COVID-19 Pathway (Homo sapiens)](https://www.wikipathways.org/index.php/Pathway:WP4846) - WikiPathways model

### Archives
- [nCovMemory](https://github.com/2019ncovmemory/nCovMemory) - Memory of coronavirus: Media Coverage, Non-fiction Writings, and Individual Narratives.
- [COVID-19-TweetIDs](https://github.com/echen102/COVID-19-TweetIDs) - Twitter posts related to COVID-19. Described in *[COVID-19: The First Public Coronavirus Twitter Dataset](https://arxiv.org/abs/2003.07372)*.

## Tools 
- [cord-19-tools](https://pypi.org/project/cord-19-tools/) - David Josephs' pip-installable python package to load the *COVID-19 Open Research Dataset (CORD-19)* dataset. A full load take 5 GB of memory.

## Visualizations

### Count visualizations 
- [Visualization of Covid-19 confirmed cases](http://shinyapps.org/apps/corona/) - Interactive ShinyApp visualization by Felix Schönbrodt (@nicebread) et al. with longitudinal confirmed cumulative cases and deaths. Development from https://github.com/nicebread/corona and data from ECDC and Johns Hopkins University.
- [COVID-19 case counts](https://covid-stats.theo.io/dashboard_draggable.php) - Interactive visualization by [Theo Sanderson](https://twitter.com/theosanderson) of longitudinal COVID-19 cases by country with interactive date offset. Data from Johns Hopkins University.
- [EuroMOMO](https://www.euromomo.eu/outputs/zscore_country_total.html) - European monitoring of excess mortality for public health action weekly mortality as deviations from the baseline.

### Visualizations on maps
- [Visual Dashboard](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) - Coronavirus COVID-19 Global Cases by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University (JHU) described in *[An interactive web-based dashboard to track COVID-19 in real time](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(20)30120-1/fulltext)*.

### Epidemiological modeling
- [Modeling COVID-19 Spread vs Healthcare Capacity](https://alhill.shinyapps.io/COVID19seir/) - Interactive ShinyApps by Alison Hill with interactive settings of epidemiological parameters and longitudinal visualization.
- [Effekten af kontakt restriktioner og rejseforbud på COVID-19 udbrud i DK](https://kagr.shinyapps.io/COVID19/) - Interactive ShinyApps in Danish by Kaare Græsbøll and Elisabeth Ottesen Bangsgaard with various interactive epidemiological variables.

### Collections of visualizations
- [Observable Topic: "Coronavirus"](https://observablehq.com/collection/@observablehq/coronavirus) - A selection of interactive Observable notebooks related to COVID-19 and SARS-CoV-2

## Notebooks
- [Hierarchical Logistic Growth Curves](https://rpubs.com/bgautijonsson/588811) - Brynjólfur Gauti Jónsson's Bayesian modeling of daily COVID-19 counts with output at https://bgautijonsson.shinyapps.io/Hierarchical_Report/.

## Papers 
### Epidemiological modeling
- [Effective containment explains sub-exponential growth in confirmed cases of recent COVID-19 outbreak in Mainland China](https://arxiv.org/abs/2002.07572) - Model that captures both, quarantine of symptomatic infected individuals as well as population wide isolation in response to mitigation policies or behavioral changes.

### Lung-CT deep learning
- [A deep learning algorithm using CT images to screen for Corona Virus Disease (COVID-19)](https://www.medrxiv.org/content/10.1101/2020.02.14.20023028v3)
- [Deep learning-based model for detecting 2019 novel coronavirus pneumonia on high-resolution computed tomography: a prospective study in 27 patients](https://www.medrxiv.org/content/10.1101/2020.02.25.20021568v2)
- [Deep Learning-Based Quantitative Computed Tomography Model in Predicting the Severity of COVID-19: A Retrospective Study in 196 Patients](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3546089)

### Other 
- [Abnormal respiratory patterns classifier may contribute to large-scale screening of people infected with COVID-19 in an accurate and unobtrusive manner](https://arxiv.org/abs/2002.05534) - Description of recurrent neural network predicting 6 respiratory patterns from depth camera data ([Scholia](https://tools.wmflabs.org/scholia/Q87745200))
