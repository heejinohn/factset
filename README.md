# Summary
The backbone of the project is `parstxt` that identifies the participants and dialogues. `parstxt_ind`
is the test file used to develope the regex in `parstxt`. `parstxt_ind` was applied to 50 sampled test 
transcripts were used to ensure the regex search works properly. `clean_tr_cont` cleans non-XBRL transcripts.

`qna_measures` is one use of the data collected from all the transcripts. It identifies forward looking questions and 
answers from the dialogues.
