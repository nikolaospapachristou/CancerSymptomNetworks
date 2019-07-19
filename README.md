# CancerSymptomNetworks
Demo of my code and expirements on cancer symptoms and their symptom clusters

Below please find attached a list links of interactive Bayesian Networks, ran on the same set of cancer symptom data. The dataset consisted of 1328 patients, and 38 symptoms. The networks were created by the symptom dimension of occurrence. 

The **size of nodes** represent the prevalence of occurrence for each symptom in our dataset. The **width of the edges** are proportional to the strentgh that symptoms connect with each other, based on the conditional probabilities identified with the BN algorithm.

By **clicking on a node** you can see its markov blanket, meaning the specific symptom with its parents and children. You can see the same markov blanket by selecting a symptom by the **menu on the left**.

You can **move each node** in the diagram by click and drag. To **deselect** it click on the white space of the diagram. To **restart the diagram** refresh the page.

The Bayesian Networks without the symptom clusters (i.e., communities) identified in the Papachristou et al. 2019. [1] 
* [All patients, Grow-Shrink, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1.html)
* [All patients, Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2.html)

[1] Papachristou, N, Barnaghi, P, Cooper, B, Kober, KM, Maguire, R, Paul, SM, Hammer, M, Wright, F, Armes, J, Furlong, EP, McCann, L, Conley, YP, Patiraki, E, Katsaragakis, S, Levine, JD, Miaskowski, C (2019). [https://www.nature.com/articles/s41598-018-36973-1](Network Analysis of the Multidimensional Symptom Experience of Oncology.) Sci Rep, 9, 1:2258.

# A few words about me

My name is **Nikolaos Papachristou** and I am currently finishing my PhD on "Machine Learning for Exploring and Predicting Cancer Symptom Clusters" at the Centre for Vision, Speech and Signal Processing (CVSSP), University of Surrey. My supervisor is Professor [Payam Barnaghi](http://personal.ee.surrey.ac.uk/Personal/P.Barnaghi/), my co-supervisor is Dr [Sarah Allison](https://www.surrey.ac.uk/nutrition/People/154416/), and my external supervisor is Professor [Christine Miaskowski](https://profiles.ucsf.edu/christine.miaskowski) (University of California, San Francisco). 

You can have an overview of my PhD research in my public presentation about ["Data analysis in oncology for predicting cancer patients' symptoms during their chemotherapy treatment", 3rd Health Innovation Conference](https://www.youtube.com/watch?v=2hMLdn9D2Hc) (the slides are in English but the presentation is in Greek).
