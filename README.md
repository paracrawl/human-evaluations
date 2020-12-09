# human-evaluations

You will find the human judgements in the files named sorted.en-xx where xx is one of the 23 official languages of the EU, Norwegian Bokmål, Norwegian Nynorsk and Icelandic. Also for the realease 7 there are Spanish co-official languages.

The format of the files for release 3 corresponds to tab separated values for URLs source, URL target, sentence source, sentence target, hunalign score, zipporah score, bicleaner score, evaluation, comments:

```
url1 url2 src trg hunalign zipporah bicleaner evaluation comments
```

The format of the files for release 6 and 7 corresponds to tab separated values for URLs source, URL target, sentence source, sentence target, bicleaner score, evaluation, comments. evaluation time(s):
```
url1 url2 src trg bicleaner evaluation comments time
```

Evaluation is the human judgement and can be one of these:

* Wrong language identification [L]
* Incorrect alignment [A]
* Wrong tokenization [T]
* MT translation [MT]
* Translation error [E]
* Free translation [F]
* Valid translation [V]
