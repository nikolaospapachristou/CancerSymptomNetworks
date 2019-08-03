# CancerSymptomNetworks

This is a demo of the application of Bayesian Networks (BNs) on cancer symptoms. If you are viewing this from github you can find its html form in the following link.
* [https://nikolaospapachristou.github.io/CancerSymptomNetworks/](https://nikolaospapachristou.github.io/CancerSymptomNetworks/)

Below please find attached **a list of interactive Bayesian Networks**, ran on the same set of cancer symptom data. The **complete dataset** consisted of 38 different symptoms collected from 1328 cancer patients. Inside this dataset, there were 295 male and 1033 female cancer patients. There were, also, 958 cancer patients below the age of 65 and 370 cancer patients above the age of 65.  

The networks were created by the **symptom dimension of occurrence**. The **size of nodes** represent the prevalence of each symptom in our dataset, among the 1328 cancer patients. The **width of the edges** are proportional to the strength that symptoms connect with each other, based on the conditional probabilities identified with the BN algorithm.

By **clicking on a node** you can see its markov blanket, meaning the specific symptom with its parents and children. You can see the same markov blanket by selecting a symptom in the **menu on the left**.

You can **move each node** in the diagram by click and drag. To **deselect** it click on the white space of the diagram. To **restart the diagram** refresh the page.

In the list below you will find the BNs created **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1] 

1. [All cancer patients (n=1328), Grow-Shrink, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1.html)
2. [All cancer patients (n=1328), Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2.html)
3. [All cancer patients (n=1328), Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1.html)
4. [All cancer patients (n=1328), Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2.html)
5. [All cancer patients (n=1328), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1.html)
6. [All cancer patients (n=1328), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
7. [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
8. [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
9. [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
10. [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
11. [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
12. [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)

In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]

13. [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1.html)
14. [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2.html) 
15. [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod1.html) 
16. [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod2.html) 
17. [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod1.html) 
18. [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agemod2.html) 
19. [Male cancer patients (n=295), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod1.html) 
20. [Male cancer patients (n=295), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod2.html) 
21. [Female cancer patients (n=1033), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1.html)
22. [Female cancer patients (n=1033), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2.html) 
23. [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod1.html)
24. [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenWomenmod2.html)

In the list below you will find the BNs created **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1] 

You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**. 

25. [All cancer patients (n=1328), Grow-Shrink, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod1group.html)
26. [All cancer patients (n=1328), Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GSmod2group.html)
27. [All cancer patients (n=1328), Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod1group.html)
28. [All cancer patients (n=1328), Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/HCmod2group.html)
29. [All cancer patients (n=1328), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod1group.html)
30. [All cancer patients (n=1328), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2group.html)
31. [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
32. [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
33. [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
34. [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
35. [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)
36. [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328) (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MMHCmod2.html)

In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **with the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1].

You can **see each symptom cluster (i.e., psychological, pain and abdominal pain, respiratory, hormonal, chemotherapy-related, nutritional) separately** by selecting a cluster in the **second menu on the left**.

37. [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod1group.html)
38. [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Agebelow65MMHCmod2group.html)
39. [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod1group.html)
40. [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/Ageabove65MMHCmod2group.html)
41. [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup1.html)
42. [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/AgeCompGroup2.html)
43. [Male cancer patients (n=295), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod1group.html)
44. [Male cancer patients (n=295), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/MenMMHCmod2group.html)
45. [Female cancer patients (n=1033), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod1group.html)
46. [Female cancer patients (n=1033), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/WomenMMHCmod2group.html)
47. [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup1.html)
48. [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013 (with symptom clusters)](https://nikolaospapachristou.github.io/CancerSymptomNetworks/GenderCompGroup2.html)


[1] Papachristou, N, Barnaghi, P, Cooper, B, Kober, KM, Maguire, R, Paul, SM, Hammer, M, Wright, F, Armes, J, Furlong, EP, McCann, L, Conley, YP, Patiraki, E, Katsaragakis, S, Levine, JD, Miaskowski, C (2019). [Network Analysis of the Multidimensional Symptom Experience of Oncology.](https://www.nature.com/articles/s41598-018-36973-1) Sci Rep, 9, 1:2258.
