gug-data
========

A dataset of learner sentences with ordinal labels for grammaticality. More detail about the creation of the data set can be found in Heilman et al. (2014). 

## Annotation File Format
The `gug_annotations.tsv` file contains the annotated dataset. There are 6 columns:

1. Id: the id for the annotated sentence
2. Sentence: the sentence that was annotated
3. Expert Judgement: the annotation assigned by the expert judge
4. Crowd Flower Judgements: the 5 annotations assigned through crowd-sourcing
5. Average: the average of all 6 judgements
6. Dataset: whether the sentence and its annotation were part of the train, dev or test set. The sentences annotated as "Other" by our expert were not submitted for crowd-sourcing. 

## Annotation Scheme
The `gug_instructions_with_sample_survey.pdf` file contains the full set of instructions given to annotators, as well as an example annotation task. The annotation scheme contains 5 categories:

* 4. Perfect
* 3. Comprehensible
* 2. Somewhat Comprehensible
* 1. Incomprehensible
* O. Other/Incomplete


## Reference
The following paper should be cited in any publications that use this dataset: 

Michael Heilman, Aoife Cahill, Nitin Madnani, Melissa Lopez, Matthew Mulholland and Joel Tetreault (2014) Predicting Grammaticality on an Ordinal Scale (2014) In Proceedings of the 52nd Annual Meeting of the Association for Computational Linguistics Baltimore, MD.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.