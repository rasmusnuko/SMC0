# **NotePerformer**

## Problem
When using digital engraving software, accurate portrayal of a musical piece is not always guaranteed.
The overall sound is artificial and phrasing does not sound natural, preventing the composer from having a seamless workflow. 

## Product

## Requirements
#### NON-FUNCTIONAL
+ Natural sounding.
  - Timbre, dynamics, articulation.
  - 70% of the focus group should be satisfied with the sound.
+ Tested and endorsed by trained composers
+ Easy parameter customization.
+ Accessible + easy to use UI, determined by the input of the focus group. 
+ Support Industry standard notation software (Sibelius, Finale, Dorico)

#### FUNCTIONAL
+ Sample based synthesis, in order to play instrument recordings.
+ Multiple recordings of each: Instrument $\times$ Pitch $\times$  Intensity $\times$ Technique.
+ AI model for processing output of synthesizers.
  - Large training dataset of different orchestral recordings and notation in various different configurations / situations.
  - As well as categorization of these recordings. Based on music perception and cognition.
+ Ability to toggle AI on output on/off.
+ Mixing possibilities. Volume adjustments, panning, reverb (small, med, large rooms, concert hall, church), EQ, compressor.
  1. Per staff.
  2. Per section.
  3. Master.

## Workflow
##### 1. Interview focus group for requirements
##### 2. Design product
##### 3. Develop
##### 4. Test with users

<figure>
<figcaption align = "center">
Visual representation of the iterative workflow.
</figcaption>
<img src="pictures/gantt.png"
<style width="80%">
</figure>

## Focus Group
We want to establish a focus group with approx. 80% trained composers and 20% musicologists.
The majority is composers, since they are our end users.
The musicologists can help us decide on the technical music perception and cognition factors.

## Milestones
1. Establish the focus group.
2. Decide important expression parameters.
3. Synth engine version 1 complete.
4. ML Model implemented. 
5. Build MVP.
6. User evaluation complete.
7. Support for industry standard notation software (Sibelius, Dorico, Finale).
8. Closed beta for larger composer audience.
9. Official release.




## Key Elements
#### **Synth engine**
We use sample based synthesis, due to possibilty to have a less CPU intensive synth engine.

The form of synthesis might be changed over time,
if another alternative turns out to be more effective and realistic.

#### **ML Model**
The model alters the output of the synth with relevant characteristics of human expressiveness.
Based on specific musical contexts derived from the notation input.

The model has been trained with a combination of live recordings and the corresponding musical score.
The recordings are categorized based on their emotional and expressive properties, in addition to melody, harmony, rhythm and repetition.

#### **UI / UX**
The UI should be easy to use, and features easy parameter customization.
This was achieved by surveying the focus group, and finding a middle ground where most users were satisfied.

Mixing interface with the possibility to group channels for small groups/sections.  Per-channel controls: volume, panning, reverb (small, medium, large, concert hall, church).

