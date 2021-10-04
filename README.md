# Summary
The backbone of the project is *__parstxt__* that identifies the participants and dialogues. *__parstxt_ind__*
is the test file used to develope the regex in *__parstxt__*. *__parstxt_ind__* was applied to 50 sampled test 
transcripts to ensure the regex search works properly. *__clean_tr_cont__* cleans non-XML transcripts.
Either convert the notebooks into scripts or run the notebooks directly. All codes require transcript text and 
tables of file name/directories. `pdf2txt` package was used to convert the pdf transcripts from FactSet to text.

`qna_measures` is one use of the data collected from all the transcripts. It identifies forward looking questions and 
answers from the dialogues.
