---
title: ""
---

**Day**
: **Lecture**
    : **Readings**

Fri, Aug 30
: **Class 1:** Introduction to Data Systems and COSI 127A <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class1.pdf" target="_blank"><span class="slides-icon"></span></a>
    : 

Tue, Sep 3
: **Class 2:** Data Systems Architectures Essentials - Part 1 <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class2.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Architecture of a Database System"](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf){:target="_blank"}, *Foundations and Trends in Databases*, 2007 <br>
[B] ["The Design and Implementation of Modern Column-Oriented Database Systems"](https://stratos.seas.harvard.edu/files/stratos/files/columnstoresfntdbs.pdf){:target="_blank"}, *Foundations and Trends in Databases*, 2012  <!--<a href="#"><span class="talk-icon"></span></a> <a href="#"><span class="video-icon"></span></a> -->

Fri, Sep 6
: **Class 3:** Data Systems Architectures Essentials - Part 2 <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class3.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["The Seattle Report on Database Research"](https://dl.acm.org/doi/pdf/10.1145/3524284){:target="_blank"}, *SIGMOD Record*, 2022 <br>
[B] ["The Seattle Report on Database Research"](https://db.cs.washington.edu/events/other/2018/Seattle_DBResearch_Report-Full.pdf){:target="_blank"}, *SIGMOD Record*, 2018

Tue, Sep 10
: **Class 4:** Row-Stores vs. Column-Stores <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class4.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Column-Stores vs. Row-Stores: How Different Are They Really?"](https://www.cs.umd.edu/~abadi/papers/abadi-sigmod08.pdf){:target="_blank"}, *SIGMOD*, 2008 <br> [__Technical Question 1__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/4899143){:target="_blank"} <b> <span style="color:#6e01fa">[What are the paper's main contributions? What is "late materialization"?](https://www.gradescope.com/courses/828851/assignments/4899143){:target="_blank"}</span> </b><br>
[B] ["C-Store: A Column-oriented DBMS"](https://web.stanford.edu/class/cs345d-01/rl/cstore.pdf){:target="_blank"}, *VLDB*, 2005

Fri, Sep 13
: **Class 5:** LSM Basics - Part 1 <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class5.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["LSM-based Storage Techniques: A Survey"](https://arxiv.org/pdf/1812.07527){:target="_blank"}, *VLDB Journal*, 2019 <br>
[B] ["Dissecting, Designing, and Optimizing LSM-based Data Stores"](https://dl.acm.org/doi/pdf/10.1145/3514221.3522563){:target="_blank"}, *SIGMOD*, 2022

Tue, Sep 17
: **Class 6:** LSM Basics - Part 2 <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class6.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Monkey: Optimal Navigable Key-Value Store"](https://nivdayan.github.io/monkeykeyvaluestore.pdf){:target="_blank"}, *SIGMOD*, 2017 <br> [__Technical Question 2__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/4962877){:target="_blank"} <b> <span style="color:#6e01fa">[When does a tiered LSM-tree behave similarly to a leveled LSM-tree? What is the key contribution of the paper?](https://www.gradescope.com/courses/828851/assignments/4962877){:target="_blank"}</span> </b><br>
[B] ["The LSM Design Space and its Read Optimizations"](){:target="_blank"}, *ICDE*, 2023

Fri, Sep 20
: **Class 7:** Class Project Overview <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class7.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Data Structures for Data-Intensive Applications"](https://cs-people.bu.edu/mathan/publications/fnt23-athanassoulis.pdf){:target="_blank"}, *Foundations and Trends in Databases*, 2023  <br>
[B] ["The Log-Structured Merge-Tree (LSM-Tree)"](https://www.cs.umb.edu/~poneil/lsmtree.pdf){:target="_blank"}, *Acta Informatica*, 1996

Tue, Sep 24
: **Class 8:** LSM Memory Buffer <br>__Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Shubham Kaushik__](https://shubhamkaushik.com){:target="_blank"}{: .label .label-guest-name} <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class8.pdf" target="_blank"><span class="slides-icon"></span></a> 
    : __[P]__ ["Anatomy of the LSM Memory Buffer: Insights & Implications"](https://dl.acm.org/doi/pdf/10.1145/3662165.3662766){:target="_blank"}, *DBTest*, 2024 <br> [__Technical Question 3__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/4993895/){:target="_blank"} <b> <span style="color:#6e01fa">[How does the memory allocation strategy affect the query latency for a pre-allocated vector vs. a dynamically allocated one? Given a workload, how would do decide the prefix length for a hash-hybrid buffer implementation?](https://www.gradescope.com/courses/828851/assignments/4993895/){:target="_blank"}</span> </b><br>
[B] ["Breaking Down Memory Walls: Adaptive Memory Management in LSM-based Storage Systems"](https://vldb.org/pvldb/vol14/p241-luo.pdf){:target="_blank"}, *VLDB*, 2020

Fri, Sep 27
: **Class 9:** LSM Compactions <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class9.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Constructing and Analyzing the LSM Compaction Design Space"](https://subhadeep.net/assets/fulltext/Constructing_and_Analyzing_the_LSM_Compaction_Design_Space.pdf){:target="_blank"}, *VLDB*, 2021 <br>
[B] ["Compactionary: A Dictionary for LSM Compactions"](https://subhadeep.net/assets/fulltext/Compactionary-A_Dictionary_for_LSM_Compactions.pdf){:target="_blank"}, *SIGMOD*, 2022

Tue, Oct 1
: **Class 10:** LSM Tuning & Robustness <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Andy Huynh__](https://ndhuynh.com/){:target="_blank"}{: .label .label-guest-name} <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class10.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Endure: A Robust Tuning Paradigm for LSM Trees Under Workload Uncertainty"](https://arxiv.org/pdf/2110.13801){:target="_blank"}, *VLDB*, 2022 <br> [__Review Paper 1__{: .label .label-yellow}](https://www.gradescope.com/courses/828851/assignments/5066340/){:target="_blank"} <b> <span style="color:#6e01fa"></span> </b><br>
[B] ["CliffGuard: A Principled Framework for Finding Robust Database Designs"](https://web.eecs.umich.edu/~mozafari/php/data/uploads/sigmod_2015.pdf){:target="_blank"}, *SIGMOD*, 2015

Fri, Oct 4
: **Rosh Hashanah -- No Class**{: .label .label-grey}

Tue, Oct 8
: **Class 11:** LSM Filters <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Zichen Zhu__](https://cs-people.bu.edu/zczhu/){:target="_blank"}{: .label .label-guest-name} <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class11.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["LSM-Tree Under (Memory) Pressure"](https://cs-people.bu.edu/mathan/publications/adms22-mun.pdf){:target="_blank"}, *ADMS*, 2022 <br> [__Technical Question 4__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/5066391/){:target="_blank"} <b> <span style="color:#6e01fa">[SHaMBa achieves better lookup performance when large Bloom filters do not fit in memory. Can we do something similar if we have large index blocks? Give a concrete example to explain why it could work or not.](https://www.gradescope.com/courses/828851/assignments/5066391/){:target="_blank"}</span> </b><br>
[B] ["Reducing Bloom Filter CPU Overhead in LSM-trees on Modern Storage Devices"](https://dl.acm.org/doi/pdf/10.1145/3465998.3466002){:target="_blank"}, *DaMoN*, 2021

Fri, Oct 11
: **Yom Kippur -- No Class**{: .label .label-grey}

Tue, Oct 15
: **Class 12:** LSM Deletes <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class12.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Lethe: A Tunable Delete-Aware LSM Engine"](https://subhadeep.net/assets/fulltext/Lethe_A_Tunable_Delete-Aware_LSM_Engine.pdf){:target="_blank"}, *SIGMOD*, 2020 <br> [__Technical Question 5__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/5066436/){:target="_blank"} <b> <span style="color:#6e01fa">[To ensure bounded delete persistent latency, Lethe aggressively performs compactions. How does these eager compactions affect write amplification of the overall system?](https://www.gradescope.com/courses/828851/assignments/5066436/){:target="_blank"}</span> </b><br>
[B] ["Acheron: Persisting Tombstones in LSM Engines"](https://subhadeep.net/assets/fulltext/Acheron_Persisting_Tombstones_in_LSM_Engines.pdf){:target="_blank"}, *SIGMOD*, 2023

Fri, Oct 18
: **Class 13:** LSM Tuning Optimization <br> __Student Presentation - 1__{: .label .label-student-presentation}  <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class13.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["Learning to Optimize LSM-trees: Towards A Reinforcement Learning based Key-Value Store for Dynamic Workloads"](https://dl.acm.org/doi/pdf/10.1145/3617333){:target="_blank"}, *SIGMOD*, 2023 <br> 
[B] ["Dostoevsky: Better Space-Time Trade-Offs for LSM-Tree Based Key-Value Stores via Adaptive Removal of Superfluous Merging"](https://scholar.harvard.edu/files/stratos/files/dostoevskykv.pdf){:target="_blank"}, *SIGMOD*, 2018

Tue, Oct 22
: **Brandeis Thursday -- No Class**{: .label .label-grey}
    : 

Fri, Oct 25
: **Class 14:** Class canceled!
    : 

Tue, Oct 29
: **Class 15:** Adaptive Radix Trees <br> __Student Presentation - 2__{: .label .label-student-presentation} <br><a title="Presentation slides" href="/COSI-167A/assets/slides/COSI167A-Class15.pdf" target="_blank"><span class="slides-icon"></span></a>
    : __[P]__ ["The Adaptive Radix Tree: ARTful Indexing for Main-Memory Databases"](https://db.in.tum.de/~leis/papers/ART.pdf){:target="_blank"}, *ICDE*, 2013 <br> [__Review Paper 2__{: .label .label-yellow}](https://www.gradescope.com/courses/828851/assignments/5182321/){:target="_blank"} <b> <span style="color:#6e01fa"></span> </b><br> 

Fri, Nov 1
: **Class 16:** Adaptive Indexing & Cracking <br> __Student Presentation - 3__{: .label .label-student-presentation} 
    : __[P]__ ["Adaptive Adaptive Indexing"](https://bigdata.uni-saarland.de/publications/Adaptive_Adaptive_Indexing_ICDE18.pdf){:target="_blank"}, *ICDE*, 2018 <br> 
[B] ["Self-organizing Tuple Reconstruction in Column-stores"](https://scholar.harvard.edu/files/IKM_SIGMOD09.pdf){:target="_blank"}, *SIGMOD*, 2009

Tue, Nov 5
: **Class 17:** Sortedness-Aware Indexing <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Aneesh Raman__](https://ramananeesh.github.io/){:target="_blank"}{: .label .label-guest-name}
    : __[P]__ ["Indexing for Near-Sorted Data"](https://cs-people.bu.edu/mathan/publications/icde23-raman.pdf){:target="_blank"}, *ICDE*, 2023 
    <br> [__Review Paper 3__{: .label .label-yellow}](https://www.gradescope.com/courses/828851/assignments/5253698/){:target="_blank"} <b> <span style="color:#6e01fa"></span> </b><br>
[B] ["BoDS: A Benchmark on Data Sortedness"](https://cs-people.bu.edu/mathan/publications/tpctc22-raman.pdf){:target="_blank"}, *TPCTC*, 2022


Fri, Nov 8
: **Class 18:** Modern Hardware Trends
    : 

Tue, Nov 12
: **Class 19:** Parametric I/O Model <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Tarikul Islam Papon__](https://cs-people.bu.edu/papon/){:target="_blank"}{: .label .label-guest-name}
    : __[P]__ ["ACEing the Bufferpool Management Paradigm for Modern Storage Devices"](https://cs-people.bu.edu/papon/pdfs/icde23-papon.pdf){:target="_blank"}, *ICDE*, 2023 <br> 
    [__Technical Question 6__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"} <b> <span style="color:#6e01fa">[Consider you have three SSDs with the following asymmetry values: (i) α = 2.0, (ii) α = 4.0, (iii) α = 6.0. Your workload contains 50% writes with a predictive pattern. Which device will have the highest speedup after implementing ACE bufferpool and why? Also, will you use any prefetcher? Justify your answer.](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"}</span> </b><br>
[B] ["A Parametric I/O Model for Modern Storage Devices"](https://cs-people.bu.edu/papon/pdfs/2021_TIP_MA_Damon.pdf){:target="_blank"}, *DaMoN*, 2021

Fri, Nov 15
: **Class 20:** Self-Designing Storage Engine <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Dr. Subarna Chatterjee__](https://chatterjeesubarna.github.io/){:target="_blank"}{: .label .label-guest-name}
    : __[P]__ ["Cosine: A Cloud-Cost Optimized Self-Designing Key-Value Storage Engine"](https://chatterjeesubarna.github.io/files/cosine.pdf){:target="_blank"}, *VLDB*, 2022 <br> 
[B] ["Design Continuums and the Path Toward Self-Designing Key-Value Stores that Know and Learn"](https://www.cidrdb.org/cidr2019/papers/p143-idreos-cidr19.pdf){:target="_blank"}, *CIDR*, 2019

Tue, Nov 19
: **Class 21:** : HTAP Systems <br> __Student Presentation - 4__{: .label .label-student-presentation} 
    : __[P]__  ["FASTER: A Concurrent Key-Value Store with In-Place Updates"](https://www.microsoft.com/en-us/research/uploads/prod/2018/03/faster-sigmod18.pdf){:target="_blank"}, *SIGMOD*, 2018 <br> 
    [__Technical Question 7__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"} <b> <span style="color:#6e01fa">[How does FASTER manage data between the "hot" in-memory section and the "cold" disk-resident section? What criteria determine when data is moved between these sections?](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"}</span> </b><br>

Fri, Nov 22
: **Class 22:** Relational Memory <br> __Guest Lecture__{: .label .label-guest-lecture}| [<i class="guest-lecture"></i> __Prof. Ju Hyoung Mun__](https://sites.google.com/view/juhyoungmun/){:target="_blank"}{: .label .label-guest-name}
    : __[P]__  ["Relational Memory: Native In-Memory Accesses on Rows and Columns"](https://openproceedings.org/2023/conf/edbt/paper-177.pdf){:target="_blank"}, *EDBT*, 2023 <br> 
[B] ["Relational Fabric: Transparent Data Transformation"](https://cs-people.bu.edu/mathan/publications/icde23-vision.pdf){:target="_blank"}, *ICDE*, 2023

Tue, Nov 26
: **Class 23:** Data Structures in Databases <br> __Student Presentation - 5__{: .label .label-student-presentation} 
    : __[P]__  ["The Data Calculator: Data Structure Design and Cost Synthesis from First Principles and Learned Cost Models"](https://dl.acm.org/doi/pdf/10.1145/3183713.3199671){:target="_blank"}, *SIGMOD*, 2018 <br> 
    [__Technical Question 8__{: .label .label-red}](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"} <b> <span style="color:#6e01fa">[TBD.](https://www.gradescope.com/courses/828851/assignments/5253760/){:target="_blank"}</span> </b><br>
[B] ["The Periodic Table of Data Structures"](https://stratos.seas.harvard.edu/sites/scholar.harvard.edu/files/stratos/files/periodictabledatastructures.pdf){:target="_blank"}, *DEBull*, 2018

Fri, Nov 29
: **Thanksgiving Holiday -- No Class**{: .label .label-grey}
    

Tue, Dec 3
: **Class Project -- Presentations A**{: .label .label-blue}
    : 

Fri, Dec 6
: **Class Project -- Presentations B**{: .label .label-blue}
    : 

Tue, Dec 10
: **Class Project -- Code Review**{: .label .label-green}
    : 

