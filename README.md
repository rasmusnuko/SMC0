# **NotePerformer**

## Problem
Accurate portrayal of a musical piece from digital engraving software is not always guaranteed. This is due to poor playback qualities, both the overall sound and phrasing prevent the composer from having a seamless workflow. 

## Focus Group
We want to establish a focus group with approx.  80% trained composers and 20% musicologists.
The majority is composers, since they are our end users.
The musicologists can help us decide on the technical music perception and cognition factors.


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
style="width:75%">
</figure>


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

#### **Aims**
+ Convincing playback (accurate representation of timbre, articulation and dynamics)
  - Endorsed by at least 70% of the focus group.
+ Support for industry standard notation software (Sibelius, Dorico, Finale)


## Milestones
+ Establishing the focus group.
+ Deciding on important expression parameters.
+ Deciding on form of synthesis.
+ Building MVP.
+ Closed beta for larger composer audience.
+ Official release.
