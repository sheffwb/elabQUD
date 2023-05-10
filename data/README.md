```targets_and_questions.tsv``` contains the ElabQUD data set, namely the crowd-sourced questions and targets. 
The original text is not provided as the Newsela documents are restricted (but free-to-use for academic researchers: https://newsela.com/data).
This file contains 2878 question-target pairs for 1299 elaborations, each with:
- ```file_num```: the file number for the newsela article
- ```elab_line```: the line number for the elaboration
- ```worker_num```: an arbitrary index for identifying which worker provided the sample
- ```question```: the QUD answered by the elaboration
- ```target_line```: the line number of the target (the text which triggered the QUD answered by the elaboration)
- ```target```: the actual target.
