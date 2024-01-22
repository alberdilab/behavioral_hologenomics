# BeHo_Mice_Luisa_PhD_Study

I'm a PhD candidate at the University of Copenhagen, Center for Evolutionary Hologenomics. My PhD is atm entitled "The bugs and behaviours of animals – Hologenomics as a tool for studying the role of the gut microbiota in mammalian behaviour". The main aim of PhD thesis is to investigate how/if the gut microbiome influences animal behaviour using a hologenomic approach. I have two research studies in my PhD to assess this and they are called:
1. Fox study (alias: behavioural fox study, fox project)
2. Mice study (alias: BeHo study, BeHo project, behavioural hologenomics mice study)

Here I share the computational work (codes and results) of the BeHo project. The text below origins from this document:
https://docs.google.com/document/d/1Ra6K9tJBcnQmh23X5Pv3lZoZJmxm84B3S1uOH_diuWY/edit?usp=sharing

## Project description
Much evidence suggests that the gut microbiome influences animal behaviour. Nevertheless, many behavioural traits have not been investigated yet, in particular those unassociated with diseases. Thus, in this study, we infer the behaviour dominance in J:DO laboratory mice (mus musculus) to test if the gut microbiome plays a role herein during different experimental treatments. Over the course of 14 weeks, we measured dominance of 80 mice in total, 40 of each sex, using a tube test to rank the dominance within a cage. Five males or five females were housed together per cage, and a hierarchy of dominance was therefore created ranking the individuals from 1 to 5, where 1 signified “most dominant” and 5 as “most submissive”. We further wanted to explore if the gut microbiome affects dominance under different biological conditions, such as changes in temperature or diet. Hence, the mice were exposed to five specific treatments, all known to interfere with the gut microbiome, each following a four day resting period for the mice to restore the potential unbalance caused (e.g. physiological or gut microbial). The order of treatments was i) an exposure to heat (temperature set to 34 degrees celsius), ii) an exposure to cold (temperature set to 14 degrees celsius), iii) a dietary change, where tryptophan was removed, iv) an antibiotic and antifungal treatment, and lastly, v) a fecal microbiota transplantation, where, among other, the feces from the most dominant animal was given to the most submissive, and vice versa, within each cage. However, two cages - one cage per sex - were not exposed to treatments, and thus, they serve as controls to examine what the gut microbes may have had of influence on dominance without any other biological disturbances. 

![BeHo treatments - simple - white bg](https://github.com/Santos-Bay/BeHo_Mice_Luisa_PhD_Study/assets/60342549/97d4fa9f-8ec2-4a94-a159-6a00d6552d2a)
## Objectives 
1. To reveal if/how the gut microbiome affects dominance in mice:
      * How’s the dominance hierarchy?
      * Are there other factors than the gut microbiome and planned treatments that affect dominance?
      * Does age matter?
      * Weight?
      * Phenotype (fur color)?
      * Crate?
2. To infer if changes in temperature affect dominance in mice via the gut microbiome
3. To assess if a change of diet that’s tryptophan depleted can influence dominance via the gut microbiome
4. To evaluate if antibiotics can modify dominance in mice via the gut microbiome
5. To determine if fecal microbiota transplantations can change the hierarchy of dominance within a cage via the gut (microbiomes)
   
## Hypotheses
The main hypothesis of my PhD thesis is:

Null hypothesis: The gut microbiomes of the mice have no effect on dominance

Alternative hypothesis: The gut microbiomes of the mice have an effect on dominance

I have subhypotheses as well, but they are not shared here.

## Experimental setup
We have a real-time experimental schedule of the BeHo 2020 study at ZiBA that shows how the experiment was conducted. I will below write about the experiment.

The experiment lasted 14 weeks in total. From Sep 7th to Dec 16th 2020.
The mice were 4 weeks upon arrival and thus, 18 weeks when euthanized.

We have 80 mice. 40 males and 40 females. 5 per cage. Two control cages (one per sex): Cage 4 (male) and 13 (female).

The mice were exposed to five different treatments: Heat, cold, diet, antibiotics and FMT. Between each treatment, the mice had five rest days.

The experiment was designed by Antton Alberdi, Ostaizka Aizpurua, Adam Koziol and me (Luisa Nielsen). If you want a thorough description of the study design and proceduces, ask Luisa Nielsen for this. We want to test the role of the gut microbiota in dominance in mice under the influence of five different biological factors referred to as treatments. We believe that one of the the main drivers behind dominance is the gut microbiota. We were therefore very focussed on frequently collecting fecal samples to identify potential changes in the gut microbiota. We also collected many other samples here among fur and organs. We aimed to collect blood as well to e.g. measure the cholestorol levels, but this was unfortunately not possible. We measured the dominance by using a tube test. The mice were tested in the acclimation and the five treatments. The tube test consisted usually of three consecutive days (= three replicates) testing the mice dominance within cages. Besides the tube test, we also measured the mice behaviour, specifically activity/movement, using an antenna system. However, this data will most likely not be included in my PhD. 

We took lab/experimental notes every day of the experiment. Thus, the daily details of the experiment can be tacked there. For example, we had a lot of aggression in cage 1, which was written about. We also have an Airtable called “Behavioural Hologenomics” where much information about the experiment can be found as well.

Below I’ve written information for each relevant (chronological) step of the experiment:

Arrival: The mice arrived Sep 7th 2023 in eight crates. They were randomisation within sex to distribute them into cages without any potential bais. The mice were weighted before transferring them into their corresponding cages. A few days after arrival the mice were tagged, so we could identify each of them.

Acclimation: The mice were acclimated for 4 weeks, before the first treatment (heat) began. This was to make sure that the animals were not stressed when starting the experiment and also to test procedures such as the tube test (very importantly). Acclimation was a temperature at 24 degrees celsius.

Rest period: The mice had five days of rest between each treatment. A rest day means that the mice were undisturbed (no handling of the mice). Also during the acclimation they had rest days, where we did not handle the mice.

Heat: The mice were exposed to 34 degrees celsius for 12 days. The mice were tube tested day 10, 11 and 12.

Cold: The mice were exposed to 14 degrees celsius for 12 days. The mice were tube tested day 10, 11 and 12.

Diet: The mice had a diet that was depleted of tryptophan 8 days. The mice were tube tested day 6, 7 and 8.

Antibiotics: The mice got antibiotics and antifungals via oral gavaging daily for day 1-5. The mice were tube tested day 6, 7 and 8. The duration of this treatment was thus 8 days.

FMT: The mice got FMT via oral gavaging day 1 and day 2. The fecal matter stored in glycerol was collected Nov 11th 2020 from the classified “super-donor-cages”. The accumulative wins used for FMT is the number of wins per mouse for all tube tests performed right before the FMT treatment began. We used this to evaluate the dominance hierachy per cage to then decide who should receive FMT from who.

Euthanization: The mice were euthanized if suffering following the European Union EFSA guidelines. Thus, a few mice died before the experiment ended (C8 mouse 3065, C16 mouse 3183, C7 mouse 2730, C3 mouse 3083, C1 mouse 4176). Once euthanized organs were collected such as the gut and brain. However, these organs are not a part of my thesis.

## Sequencing techniques applied
We have two sequencing techniques applied in BeHo:
* Metagenomics (short-read 150bp DNA sequencing)
* Host Genomics (long-read PacBio DNA sequencing)

## Datassets
Thus, we have two datasets in BeHo:
1. Metagenomic sequencing data
2. Genomic sequencing data

The metagenomic sequencing data derives from in total 470 fecal samples (from 40 mice) and five environmental samples (water, bedding material, nesting material and feed pellet with/without tryptophan).
The genomic sequencing data originates from in total 40 mice leg muscles. It is the same 40 individual animals as in the metagenomic data, except for male 4 (cage 3, tag 3083), who was mistakenly not processed. 

## Lab work
Novogene UK generated the genomics and metagenomics sequencing data. However, the libraries were pre-made in-house before shipment. The Pacbio sequencing data was generated by the Søren Sørensen’s group at KU, and they also built the libraries based on DNA extracts delivered by me.

For all three data sets, only 40 mice were processed out of the 80. The 40 mice derive from eigth cages, four male and four female: 3-6 (male) and 10-13 (female). Cage 4 and 13 are the control cages.

The sample source of the genomic data is leg muscle, and the sample source of the metagenomic data is feces. The leg muscles were collected at the end of the experiment when the mice were euthanized. There is thus one leg muscle sample per animal. In total 40 leg muscle samples were processed in the labs. The fecal samples were collected repeatedly at many time points (to get an overview look at the experimental schedule linked to earlier). For instance, at every tube test replicate 1. Therefore, in total 470 fecal samples were processed. The fecal samples were processed in three batches. The samples were randomised to reduce lab work associated bias.

Environmental samples were processed as well in the first batch. We collected and processed samples of water that the mice drank, the feed pellets (with and without tryptophan) and their (clean) nesting as well as bedding materials. However, the DNA concentrations were very low, but they were sequenced anyway.

## Mouse strain
The mice are from The Jackson Laboratory and are outbred:
J:DO - JAX Diversity Outbred
Stock #009376
https://www.jax.org/strain/009376


Lastest update: Friday 17th of November 2023
