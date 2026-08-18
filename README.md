# The Effect of Noisy Stimuli and Goal-directed Perception on Face Recognition in ECoG

For more information, view the project gallery: https://airtable.com/app1MtChyjyKEDzAt/shrR68OdIIny48Ynt/tblvFwAE4oqf3M10o/viw3Ma2non57ofw6z/recglye9UrEvHGkc4

## Background
Faces are fundamental stimuli specifically attended to by cortical regions in visual processing, such as the fusiform face area (Kanwisher et al., 1997), with faster reaction times compared to other stimuli (Crouzet, Kirchner & Thorpe, 2010). 

## Objective
In our project, we explore the differences within neuronal signatures of face vs house (a category with matching familiarity, mono-orientation, and spatial similarity to faces (Robbins et al., 2011; Yin, 1969)) perception and the way it is affected by selective attention (a goal-directed perception) vs. passive watching of stimuli. In addition, we aim to study the ability to perceive faces when the perception is noisy. 

## Hypothesis
The amplitude of response within goal-directed face perception is expected to be stronger. Additionally, we predict face perception to degrade more gradually than house perception as noise levels increase. 

## Methods
We analyze human ECoG from 7 participants across two paradigms: a passive-viewing task and a goal-directed face-detection task, the latter requiring a button press to report target detection under varying visual noise levels (0–100% in 5% increments). For analysis, we apply cluster permutation analysis in order to find electrodes that significantly react to either faces or houses. We analyze spatial and temporal activity dynamics on those specific electrodes, both in the time and frequency domains. This is in addition to behavioural response evaluation. Next, we apply a linear discriminant classifier and Drift Diffusion Model (DDM) to decode whether participants were viewing faces or houses from ECoG broadband activity. Using these decoding models, we compare the differences in alpha power across goal-directed perception and investigate the representation of the stimuli across different noise levels. 

## Expected Outcome
We expect the decoders to have higher classification accuracy for goal-directed face perception than their passive counterparts. Moreover, they should better match the noise curves for face perception as compared to house perception.
