# CancerSymptomNetworks

This is a demo of the application of Bayesian Networks (BNs) on cancer symptoms. If you are viewing this from github you can find its html form in the following link.
* [https://nikolaospapachristou.github.io/CancerSymptomNetworks/](https://nikolaospapachristou.github.io/CancerSymptomNetworks/)

Below please find attached **a list of interactive Bayesian Networks**, ran on the same set of cancer symptom data. The **complete dataset** consisted of 1328 cancer patients, and 38 different symptoms. Inside this dataset, there were 295 male and 1033 female cancer patients. There were, also, 958 cancer patients below the age of 65 and 370 cancer patients above the age of 65.  

The networks were created by the **symptom dimension of occurrence**. The **size of nodes** represent the prevalence of each symptom in our dataset. The **width of the edges** are proportional to the strength that symptoms connect with each other, based on the conditional probabilities identified with the BN algorithm.

By **clicking on a node** you can see its markov blanket, meaning the specific symptom with its parents and children. You can see the same markov blanket by selecting a symptom in the **menu on the left**.

You can **move each node** in the diagram by click and drag. To **deselect** it click on the white space of the diagram. To **restart the diagram** refresh the page.

In the list below you will find the BNs created **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1] 
* [All cancer patients, Grow-Shrink, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1.html)
* [All cancer patients, Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2.html)
* [All cancer patients, Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1.html)
* [All cancer patients, Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2.html)
* [All cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1.html)
* [All cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)

In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]  :
* [Cancer patients with age below 65, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1.html)
* [Cancer patients with age below 65, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2.html)
* [Cancer patients with age above 65, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod1.html)
* [Cancer patients with age above 65, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod2.html)
* [Cancer symptoms network differences between cancer patients below the age of 65 and above the age of 65, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod1.html)
* [Cancer symptoms network differences between cancer patients below the age of 65 and above the age of 65, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod2.html)
* [Male cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod1.html)
* [Male cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod2.html)
* [Female cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1.html)
* [Female cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2.html)
* [Cancer symptoms network differences between male and female cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)
* [Cancer symptoms network differences between male and female cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)

In the list below you will find the BNs created **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1] 

You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**.
* [All patients, Grow-Shrink, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1group.html)
* [All patients, Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2group.html)
* [All patients, Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1group.html)
* [All patients, Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2group.html)
* [All patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1group.html)
* [All patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2group.html)

In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1].

You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**.



[1] Papachristou, N, Barnaghi, P, Cooper, B, Kober, KM, Maguire, R, Paul, SM, Hammer, M, Wright, F, Armes, J, Furlong, EP, McCann, L, Conley, YP, Patiraki, E, Katsaragakis, S, Levine, JD, Miaskowski, C (2019). [Network Analysis of the Multidimensional Symptom Experience of Oncology.](https://www.nature.com/articles/s41598-018-36973-1) Sci Rep, 9, 1:2258.
