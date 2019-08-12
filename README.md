# CancerSymptomNetworks

This is a demo of the application of Bayesian Networks (BNs) on cancer symptoms. If you are viewing this from github you can find its html form in the following link.
* [https://nikolaospapachristou.github.io/CancerSymptomNetworks/](https://nikolaospapachristou.github.io/CancerSymptomNetworks/)

Below please find attached **a list of interactive Bayesian Networks**, ran on the same set of cancer symptom data. The **complete dataset** consisted of 38 different symptoms collected from 1328 cancer patients. Inside this dataset, there were 295 male and 1033 female cancer patients. There were, also, 958 cancer patients below the age of 65 and 370 cancer patients above the age of 65.  

The networks were created by the **symptom dimension of occurrence**. The **size of nodes** represent the prevalence of each symptom in our dataset, among the 1328 cancer patients. The **width of the edges** are proportional to the strength that symptoms connect with each other, based on the conditional probabilities identified with the BN algorithm.

By **clicking on a node** you can see its markov blanket, meaning the specific symptom with its parents and children. You can see the same markov blanket by selecting a symptom in the **menu on the left**.

You can **move each node** in the diagram by click and drag. To **deselect** it click on the white space of the diagram. To **restart the diagram** refresh the page.

**A.** In the list below you will find the BNs created **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]

 * [SF1] [All cancer patients (n=1328), Grow-Shrink, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1.html)
 * [SF2] [All cancer patients (n=1328), Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2.html)
 * [SF3] [All cancer patients (n=1328), Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1.html)
 * [SF4] [All cancer patients (n=1328), Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2.html)
 * [SF5] [All cancer patients (n=1328), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1.html)
 * [SF6] [All cancer patients (n=1328), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
 * [SF7] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSHCmod1.html)
 * [SF8] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSHCmod2.html)
 * [SF9] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSMMHCmod1.html)
 * [SF10] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSMMHCmod2.html)
 * [SF11] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCMMHCmod1.html)
 * [SF12] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCMMHCmod2.html)

**B.** In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]
 * [SF13] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1.html)
 * [SF14] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2.html)

* [SF15] [Cancer patients with age below 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1.html)
 * [SF16] [Cancer patients with age below 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2.html)
 
 * [SF17] [Cancer patients with age above 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod1.html) 
 * [SF18] [Cancer patients with age above 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod2.html) 
 
 * [SF19] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod1.html) 
 * [SF20] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod2.html) 
 
 * [SF21] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod1.html) 
 * [SF22] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod2.html) 
* [SF23] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and below the age of 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod1.html) 
 * [SF24] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod2.html) 
 
 
 
 * [SF25] [Male cancer patients (n=295), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod1.html) 
 * [SF26] [Male cancer patients (n=295), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod2.html) 
 * [SF27] [Female cancer patients (n=1033), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1.html)
 * [SF28] [Female cancer patients (n=1033), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2.html) 

 * [SF29] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1.html)
 * [SF30] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2.html) 


* [SF31] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)
 * [SF32] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod2.html)
 
 * [SF33] [Cancer symptoms' network differences between male (n=295) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)
 * [SF34] [Cancer symptoms' network differences between male (n=295) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod2.html)
 * [SF35] [Cancer symptoms' network differences between female (n=1033) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)
 * [SF36] [Cancer symptoms' network differences between male (n=1033) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod2.html)
 

**C.** In the list below you will find the BNs created **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1] You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**. 
 * [SF37] [All cancer patients (n=1328), Grow-Shrink, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1group.html)
 * [SF38] [All cancer patients (n=1328), Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2group.html)
 * [SF39] [All cancer patients (n=1328), Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1group.html)
 * [SF40] [All cancer patients (n=1328), Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2group.html)
 * [SF41] [All cancer patients (n=1328), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1group.html)
 * [SF42] [All cancer patients (n=1328), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2group.html)
 * [SF43] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSHCmod1group.html)
 * [SF44] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSHCmod2group.html)
 * [SF45] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSMMHCmod1group.html)
 * [SF46] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSMMHCmod2group.html)
 * [SF47] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCMMHCmod1group.html)
 * [SF48] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCMMHCmod2group.html)

**D.** In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]. You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**.
 * [SF49] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1group.html)
 * [SF50] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2group.html)

* [SF51] [Cancer patients with age below 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1group.html)
 * [SF52] [Cancer patients with age below 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2group.html)

 
 * [SF53] [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod1group.html)
 * [SF54] [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod2group.html)
 * [SF55] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup1.html)
 * [SF56] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup2.html)
 
* [SF57] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup1.html)
 * [SF58] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup2.html)
 * [SF59] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and below the age of 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup1.html)
 * [SF60] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and below the age of 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup2.html)
 
 * [SF61] [Male cancer patients (n=295), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod1group.html)
 * [SF62] [Male cancer patients (n=295), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod2group.html)
 * [SF63] [Female cancer patients (n=1033), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1group.html)
 * [SF64] [Female cancer patients (n=1033), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2group.html)

 * [SF65] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1group.html)
 * [SF66] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2group.html)

* [SF67] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup1.html)
 * [SF68] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup2.html)

* [SF69] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup1.html)
 * [SF70] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup2.html)
* [SF71] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup1.html)
 * [SF72] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup2.html)



[1] Papachristou, N, Barnaghi, P, Cooper, B, Kober, KM, Maguire, R, Paul, SM, Hammer, M, Wright, F, Armes, J, Furlong, EP, McCann, L, Conley, YP, Patiraki, E, Katsaragakis, S, Levine, JD, Miaskowski, C (2019). [Network Analysis of the Multidimensional Symptom Experience of Oncology.](https://www.nature.com/articles/s41598-018-36973-1) Sci Rep, 9, 1:2258.
