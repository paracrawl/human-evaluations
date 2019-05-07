# human-evaluations

You will find the human judgements in the files named sorted.en-xx where xx is one of the 23 official languages of the EU other than English. 

The format of the files corresponds to tab separated values for URLs source, URL target, sentence source, sentence target, hunalign score, zipporah score, bicleaner score, evaluation, comments: 

```
url1 url2 src trg hunalign zipporah bicleaner evaluation comments 
```

Evaluation is the human judgement and can be one of these:

* Wrong language identification [L]	
* Incorrect alignment [A]	
* Wrong tokenization [T]	
* MT translation [MT]	
* Translation error [E]	
* Free translation [F]	
* Valid translation [V]
