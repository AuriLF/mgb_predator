This repository contains the following elements: 

-**1. plots** = folder containing the images of the figures featured in '1. Predator model experiments - behaviour' and '2. Predator model experiments - vocal response'
   
-**0. R packages & libraries.md** = R packages needed to run the scripts
   
-**1. Behaviours.md** = analyses of all behaviours but vocal responses
   
-**2. Vocal responses - acoustic analyses (pDFA).md** = analyses of sound elements using a set of acoustic parameters extracted from Raven Pro

-**3. Vocal responses - utterance composition.md** = analyses of utterance composition (i.e., structure)

-**mangabey behaviour.csv** = dataset used in 1

-**mangabey call wide.csv** = dataset used in 2

-**mangabey call acoustic.csv** = dataset used in 2 & 3 

--------
Feedback presentation TCP lab meeting + Klaus 07/04/2025

Analysis flee duration: add trials with no flee with time = 0. Then change variable name from flee to something like 'time spend moving away/fleeing'

Analysis flee direction: variable response would be climb up in the trees yes/no, then add trials when they don't flee toghether with flee down or straigh in 'no' and flee up in 'yes'

Analysis nb vocal uterances: add 0 if no vocal responses

Graphs: change yellow colour into more dark colour

pDFA: check if we need to remove corellated parameters or not

Check shrill acoustic properties depending on position in utterance/call/sequence?

Discussion: hoos might be fore more serious danger; adult males might have difference vocal responses to eagle for mobbing; check closest relative alarm system so see if it they have general alarm to eagle and leopard or not. also for viper or snakes


--------
Alex comments

-ensure that it is clear that I am tallking about the initial response of the first individual spotting the model (first 30s) not group response because after that all sorts of behaviours can happen (approaching, mobbing etc). 


-compare behaviours that I get with mangabey papers from Alex, Julian, Freddy to ensure consistency


-discuss that the size of the individual might play a role in escape response (the bigger you are, less likely you are to get attacked by an eagle


-for bayesian models we cannot use bonferonni correction because no p values. check there https://easystats.github.io/blog/posts/bayestestr_emmeans/ how to run pairwise


-pairwise comparisons: keep in mind that they might be not relevant so instead we can compare mean posterior with ci and if ci are not overlapping then there is a difference


Klaus comments

Reaction of mangabeys to leopard are staying around vs chimps where they flee far; discuss tail raise (social role, age class, distance to predator)
