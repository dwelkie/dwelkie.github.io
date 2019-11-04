---
permalink: /projects/
title: "Projects"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/plates.jpg
  overlay_filter: 0.15
#toc: true
#toc_sticky: true
author_profile: false
classes: wide
sidebar:
  nav: "docs"

---
This page gets updated from time to time, if interested in recent work, contact me!
# UC San Diego

## Engineering Industrial Microorganisms
I am currently contributing to a multi-group project to develop a process for making advanced genetic tools, high throughput screening methods, and breeding technologies that will enable economical biofuel production from algae and cyanobacteria.  More specifically, I am a) performing bioinformatics on genome sequences of strains currently in industrial use, b) designing, building, and testing genetic tools such as synthetic promoters, inducible riboswitches, and translational control mechanisms, and c) performing markerless genome engineering using Cas12a (Cpf1) CRISPR. After characterization, we will demonstrate the utility of these synthetic biology tools via the photosynthetic bioproduction of a variety of target chemical products (short chain diacids).

## Genome-Scale Modeling
Genome-scale models of metabolism are important tools for metabolic engineering and production strain development. In a collaborative effort, I helped generate, experimentally validate, and manually curate a model of metabolism in _Synechococcus elongatus_ PCC 7942 that (i) lead to discovery of unique metabolic characteristics, such as the importance of a truncated, linear TCA pathway, (ii) highlights poorly understood areas of metabolism, and (iii) accurately quantifies light input and self-shading.

>Broddrick JT¹ , Rubin BE¹, **Welkie DG**¹ , Du D, Mih N, Diamond S, Lee JJ, Golden SS, Palsson BO. Unique attributes of cyanobacterial metabolism revealed by improved genome-scale metabolic modeling and essential gene analysis. Proceedings of the National Academy of Sciences. 2016. Dec 113;51:E8344-E8353. ¹co-1st authorship <br/>  Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/27911809){:target="_blank"}, [DOI](https://doi.org/10.1073/pnas.1613446113){:target="_blank"}, or<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1g8nSXTIxjOnFs6LV8sU_zyxZlm0jNWZj" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

We then utilized this model framework to develop proper constraints necessary to generate biologically realistic engineering predictions for phototrophic metabolism. By measuring high quality photophysiology parameters coupled to genome-scale flux balance analysis we were able to make accurate predictions of growth rates and metabolic reaction fluxes at low and high light conditions, characterize the metabolic cost of excess excitation energy and predict energy fluxes consistent with known light-adapted phenotypes. The highlight of this work was leveraging the model and constraints to characterize existing photoautotrophic and photomixtotrophic engineering strategies for 2,3-butanediol production.
>**Welkie DG**, Golden SS, Palsson BO. "Creating a predictive metabolic model of photoautotrophic metabolism in cyanobacteria to improve bioengineering design." Poster Presentation at the UC San Diego Chancellor’s Research Excellence Annual Symposium. University of California, San Diego, CA. October 25, 2018 <a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1Tjz-dU8d6TEGqH61Dzez6PnUo0GYBqW-" target="_blank" > <i class="far fa-file-pdf"></i> view poster.

>Broddrick JT, **Welkie DG**, Jallet D, Golden SS, Peers G, Palsson BO. Predicting the metabolic capabilities of *Synechococcus elongatus* PCC 7942 adapted to different light regimes. Metabolic Engineering. 2018 Nov 13;52:42-56.<br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/30439494){:target="_blank"} , [DOI](https://doi.org/10.1016/j.ymben.2018.11.001){:target="_blank"}, or<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1jJub7N5iiOAv4gPGpZ0kkDLXqO2AWwvn" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

## KaiA and Circadian Clock Regulation
The circadian clock in the model cyanobacterium _Synechococcus elongatus_ sp. PCC 7942 directly controls the expression of ~30% of the genome and indirectly almost its entirety when entrained to light-dark cycles. Yet metabolic processes important for growth under light-dark cycles and how the clock regulates them is less understood. I applied random bar-code transposon-site sequencing (RB-TnSeq) to quantitatively compare the changes in abundances of individual mutant strains in a dense pooled mutant population over time. By screening this library under constant light and light-dark cycling conditions I calculated a fitness contribution for each nonessential gene in the genome by leveraging multiple inactivating mutations spread across a genomic locus. The resulting identity of genetic contributors to fitness under light-dark cycles gives a comprehensive picture of diurnal metabolism and how the circadian signal output is critical to strain fitness in response to dark exposure.

>**Welkie DG**, Rubin BE, Chang Y, Smith S, LiWang A, Golden S. Genome-wide fitness assessment during diurnal growth reveals an expanded role of the cyanobacterial circadian clock protein KaiA. Proceedings of the National Academy of Sciences. 2018 July  115;30:E7174-E7183.<br/> Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/29991601){:target="_blank"}

These efforts along with those of my colleagues led to the production of a review article that serves as a summary of current knowledge (as of 2019) dealing with cyanobacteria and their lifestyle in light-dark cycling conditions.
>**Welkie DG**, Rubin BE, Diamond S, Hood RD, Savage DF, Golden SS. A hard day’s night: Cyanobacteria in diel cycles. Trends in Microbiology. 2018 Volume 27, Issue 3, March 2019, Pages 231-242 <br/>
Links to article: [DOI](https://doi.org/10.1016/j.tim.2018.11.002){:target="_blank"}

## Genetic Fitness and Interaction Screens
Cyclic di-adenosine monophosphate (c-di-AMP) is a molecule that has significant roles in many microorganisms. This work shows the existence of c-di-AMP for the first time in photosynthetic microorganisms. To identify other players in c-di-AMP’s function we developed a technique by applying our dense barcode transposon mutant library for revealing genetic interactions. By introducing a disruptive mutation in the gene that encodes the enzyme responsible for the synthesis of c-di-AMP into each of the thousands of other individual mutations in the library, we characterized  pairwise interactions that affect fitness of the resulting mutants.

>Rubin BE, Huynh TN, **Welkie DG**, Diamond S, Simkovsky R, Pierce EC, et al. High-throughput interaction screens illuminate the role of c-di-AMP in cyanobacterial nighttime survival. PLoS Genetics. 2018 Apr 14;4:e1007301 <br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/29608558){:target="_blank"}, [DOI](https://doi.org/10.1371/journal.pgen.1007301){:target="_blank"}, or:<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1YF5qtAZzlKsyA7ic3LZSWBq-Pe6_eSSJ" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

# Purdue

## Modifying Carbohydrate Storage
* The unicellular diazotrophic cyanobacteria of the genus _Cyanothece_ demonstrate oscillations in nitrogenase activity and H2 production when grown under light-dark cycles. At the time, genetic techniques were unable to resolve the restrictive mechanisms in many species of this genus, but, found success utilizing single stranded DNA to generate mutants in strain _Cyanothece_ sp. PCC 7822. With this came opportunity and the need to improve this strains the growth characteristics. In addition, major areas of its metabolism differed from other Cyanothece and I performed studies to illuminate intracellular carbon storage metabolism. I developed a growth medium that improved culture uniformity, enhanced the growth rate, and resulted in cells storing more nutrients in biomass instead of intercellular granules like PHB. Biochemical analysis and transmission electron microscopy analysis also revealed that glycogen storage in this strain was distinct from close relatives.

>**Welkie DG**, Sherman DM, Chrisler WB, Orr G, Sherman LA. Analysis of carbohydrate storage granules in the diazotrophic cyanobacterium *Cyanothece* sp PCC 7822. Photosynthesis Research 2013 Nov 118(1-2):25-36. <br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/24142038){:target="_blank"}, [DOI](https://doi.org/10.1007/s11120-013-9941-z){:target="_blank"}, or<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1JCrYEhuD9F8kURterbRSE07OF3k3k4--" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

Manipulating the storage of carbon into polysaccharide could be beneficial to improving targeted biosynthetic productivities and presents a viable solution for renewable carbon feedstock for heterotrophic bacteria, or even improve the sensory aspects of edible cyanobacterial strains. In this study, the discovery of morphological variation of polysaccharide storage in Cyanothece strains was further investigated via mutagenesis of the branching and debranching genes found in _Synechocystis_ sp. PCC 6803 to characterize their roles in determining granule morphology.

>**Welkie DG**, Lee BH, Sherman LA. Altering the structure of carbohydrate storage granules in the cyanobacterium *Synechocystis* sp. strain PCC 6803 through branching-enzyme truncations. Journal of Bacteriology 2015 Dec 198:701-710. <br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/26668264){:target="_blank"}, [DOI](https://doi.org/10.1128/JB.00830-15){:target="_blank"}, or<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1QE9B8kivtV29aVOk0OXDP0jNN2_bJV_Q" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

## Photosynthetic Isoprene Biosynthesis

This project's goal was to i) produce isoprene photosynthetically in a cyanobacterium, and ii) optimize this production using genome-scale flux balance analysis. I engineered _Synechocystis_ sp PCC6803 to produce the C5 compound, isoprene, by expressing a heterologous protein encoding isoprene synthase codon optimized from _Poplar_ and measured production using gas chromatography. I also tested computational modeling predictions to optimize productivity.

>**Welkie DG**, Saha R, Zhang X, Maranas CD, and Sherman LA. “Optimizing isoprene production in Synechocystis 6803 utilizing computational modeling and transcriptional regulation”. Poster 11th Workshop on Cyanobacteria. Washington University, St. Louis, MO. 2013 <a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1-zaVjOPzuPZxNSSGlnsWKzLhuLacNZ-0" target="_blank" > <i class="far fa-file-pdf"></i> view poster.

## Gene Expression in Light-Dark Cycles

Towards the goal of developing cyanobacteria for biofuel production in the strain _Cyanothece_ sp PCC7822, we set out to determine the genome-wide expression profile over a time-course in natural light conditions which the strain would be grown in industrially. In this study we performed transcriptomics and proteomics across the diurnal cycle and detailed the synchronicity of mRNA and protein abundances. One resulting finding was that while mRNA transcript changes can be dramatic over time, specific protein abundances can be much more steady. I also detailed profiles of genes that could be utilized for butanol and other chemical biosynthesis pathways.

>**Welkie D**, Zhang X, Markillie ML, Taylor R, Orr G, Jacobs J, Bhide K, Thimmapuram J, Gritsenko M, Mitchell H, Smith RD, Sherman LA. Transcriptomic and proteomic dynamics in the metabolism of a diazotrophic cyanobacterium, *Cyanothece* sp. PCC 7822 during a diurnal light-dark cycle. BMC Genomics 2014 Dec 15:1185.8 <br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/25547186){:target="_blank"},[DOI](https://doi.org/10.1186/1471-2164-15-1185){:target="_blank"}, or<a class="btn btn-success btn-lg" href="https://drive.google.com/open?id=1wFPTqduSg5XnYQjx3QbliGQbiuaZBXMS" target="_blank" ><i class="far fa-file-pdf"></i>open PDF

# UW-Madison

## Microbial Community Dynamics to Environmental Disturbance
Understanding microbial community dynamics in the rumen of dairy cows is vital to understanding animal health and productivity. In this study we used automated ribosomal intergenic spacer analysis to track changes in the microbial community during the feeding cycle of dairy cows. Using two animals eating the same diet, we found large changes in the associated liquid populations as well as in ruminal pH and voltile fatty acid (VFA) concentrations. This differed in solid-associated microbial communities that displayed much less change in composition within and across feeding cycles. To sample the ruminal microbiome, I reached into the rumen of  fistulated cows and collected a sample using a small cup over multile timepoints. Fun stuff!

>**Welkie DG**, Stevenson DM, Weimer PJ. ARISA analysis of ruminal bacterial community dynamics in lactating dairy cows during the feeding cycle. Anaerobe 2010 Apr 16;2:94-100.<br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/19615457){:target="_blank"}

Following this I worked on a Northern Temperate Lakes Microbial Observatory Project to study the microbial communities in fresh water lakes working under the supervision of Dr. Katherine McMahon and Dr. Ashley Shade. This project set out to separate the environmental drivers of microbial communities in freshwater ecosystems in response to seasonal and abrupt disturbances. My role in both these projects was to collect the samples from the field, perform DNA extractions and assist with data analysis and help with manuscript writing. <br/>

>Shade A, Read JS, **Welkie DG**, Kratz TK, Wu CH, McMahon KD. Resistance, resilience and recovery: Aquatic bacterial dynamics after water column disturbance. Environmental Microbiology 2011 Oct 13;10:2752-2767. <br/>
Links to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/21883795){:target="_blank"}
