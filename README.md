# ParlaMint_Sentiment: Workflow for utterance-level sentiment annotation

The repository contains settings for manual sentiment annotation at
the utterance and sentence level, as well as data analysis of both.
In addition, the workflow includes experiments to aggregate
sentence-level scores.

The sentence-level annotations for Slovenian are available in the [the multilingual sentiment dataset of parliamentary debates ParlaSent 1.0](http://hdl.handle.net/11356/1868). 

The utterance-level annotations for Slovenian parliamentary debates are available in the [Speech-level sentiment annotation dataset of Slovenian parliamentary debates ParlaSent-SI 1.0](http://hdl.handle.net/11356/2256).


## Annotation settings
- 2,600 sentences annotated
- 1,000 full utterances (i.e. speeches) annotated
- 6-class and 3-class (Negative, Positive, Neutral) schema

6-class schema (originally proposed by [Batanović et al (2020)](https://doi.org/10.1371/journal.pone.0242050)):

- Positive for sentences/utterances that are predominantly positive 
- Negative for sentences/utterances that are predominantly negative 
- M_Positive for sentences/utterances that convey an ambiguous sentiment or a mixture of sentiments, but lean more towards the positive sentiment 
- M_Negative for sentences/utterances that convey an ambiguous sentiment or a mixture of sentiments, but lean more towards the negative sentiment 
- P_Neutral for sentences/utterances that only contain non-sentiment-related statements, but still lean more towards the positive sentiment 
- N_Neutral for sentences/utterances that only contain non-sentiment-related statements, but still lean more towards the negative sentiment.



## Directories:

**[Aggregation](/Aggregation/)**: Tests and development of the
  aggregation methods

**[Sentences](/Sentences)**: Sentiment annotation of the level of
  individual sentences

**[Utterances](/Utterances)**: Sentiment annotation on the level of
  utterances (full speeches)





