This repository contains the following elements: 

-**1. plots** = folder containing the images of the figures featured in '1. Predator model experiments - behaviour' and '2. Predator model experiments - vocal response'
   
-**0. R packages & libraries.md** = R packages needed to run the scripts
   
-**1. Predator model experiments - behaviour.md** = analyses of all behaviours but vocal responses
   
-**2. Predator model experiments - vocal response.md** = analyses of vocal responses

-**mangabey behaviour.csv** = dataset used in 1. Predator model experiments - behaviour

-**mangabey call wide.csv** = dataset used in 2. Predator model experiments - vocal response.md = analyses of vocal responses


Alex comments

-ensure that it is clear that I am tallking about the initial response of the first individual spotting the model (first 30s) not group response because after that all sorts of behaviours can happen (approaching, mobbing etc). 

-compare behaviours that I get with mangabey papers from Alex, Julian, Freddy to ensure consistency

-discuss that the size of the individual might play a role in escape response (the bigger you are, less likely you are to get attacked by an eagle

-for bayesian models we cannot use bonferonni correction because no p values. check there https://easystats.github.io/blog/posts/bayestestr_emmeans/ how to run pairwise

-for all models: set minimally informative priors (ask chatgpt which one depending on the type of distribution). Also when model is having issues working, try removing id as random effect

-model element interval vs condition: distribution (family) is not gamma but rather log normal, also here consider removing id as random effect


-model utterance type vs condition: put trial_id as random effect and not total utt; here again consider removing id as random effect

-pairwise comparisons: keep in mind that they might be not relevant so instead we can compare mean posterior with ci and if ci are not overlapping then there is a difference


Klaus 

Reaction of mangabeys to leopard are staying around vs chimps where they flee far; discuss tail raise (social role, age class, distance to predator)
