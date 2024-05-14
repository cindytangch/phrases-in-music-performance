# Phrases in performance and phrases in the score
This study is a part of the DH-401 Digital musicology course at EPFL.

In this work, our objective is to investigate how phrasing in performance is related to phrasing as in musical structure.

## Dataset

The data utilized is sourced from the [Aligned Scores and Performances (ASAP) dataset](https://github.com/fosfrancesco/asap-dataset), which comprises 236 musical scores with 1067 performances from 15 composers in MIDI formats.

For our analysis, we choose to focus on the [Mozart's Piano Sonata n°8 I](https://github.com/fosfrancesco/asap-dataset/tree/master/Mozart/Piano_Sonatas/8-1) subcorpus.

## Instructions
### [Task A] Close listening: "What is a phrase?"
Listen carefully to one performance of the piece that you chose from the dataset while looking at the MIDI and the symbolic score. Pay special attention to phrases, especially their boundaries. Discuss what gives a phrase its unity in terms the following points:
1. Characterize what a phrase is in terms of performance attributes, such as the
   - contour of the dynamics (loudness curve or "velocity" in MIDI)
   - timing: "speeding up" or "slowing down", more/less timing flexibility
   - accents
   - or other potential features you observe
2. Characterize what a phrase is in terms of the attributes of the symbolic score, such as the
   - melodic contour
   - harmony
   - rhythm and hypermeter
   - texture
   - or other potential features you observe

### [Task B] Close listening: annotate phrases by hand
1. Annotate the phrases on the symbolic score by hand (on the PDF or musescore file using distinct symbols for phrase boundaries). Do two runs using different symbols to:
   - denote boundaries from hearing the performance
   - denote boundaries from your understanding of the score

Briefly compare the two.

2. Do you hear phrases to have further parts? How would you describe those both in terms of performance attributes and score attributes? Present your observations and findings in writing with references to specific measures in the score. You can also visualize your understanding of a phrase in terms of a drawing.

### [Task C] Computational Modeling: Implement a phrase segmentation algorithm
1. Informed by your previous findings, implement a simple phrase segmentation algorithm `Model_P` that outputs phrase boundaries using only performance attributes.
2. Compare your model-predicted phrases with the ones marked by yourselves.
3. Implement another phrase segmentation algorithm to either
   - detect phrases in unperformed scores, or
   - improve `Model_P` by using score attributes.
4. Run both of your algorithms on a larger suitable corpus chosen by you. Give statistics on the number of phrases detected per piece and additional suitable statistics. Discuss your results and give a brief qualitative assessment of your algorithm's performance on one new piece. Discuss general perspectives on improving phrase detection even further.


## Credits
Authors: Romane Clerc - Octavio Profeta - Cindy Tang - Shu Yang

Professor: Martin Rohrmeier

Course: DH-401 Digital musicology, EPFL

Date: 15.05.2024
