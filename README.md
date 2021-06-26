# vortan_corpus

A collection of corpora for vortan.

## Dataset

### Eastern

- [uni_freq_wiki_eastern.txt](/dataset/uni_freq_wiki_eastern.txt)
  - 171,038 unigram frequencies generated from [wiki_eastern.txt](/processed/wiki_eastern.txt)
- [bi_freq_wiki_eastern.txt](/dataset/bi_freq_wiki_eastern.txt)
  - 1,007,324 bigram frequencies generated from [wiki_eastern.txt](/processed/wiki_eastern.txt)

### Western

- [uni_freq_wiki_western.txt](/dataset/uni_freq_wiki_western.txt)
  - 48,634 unigram frequencies generated from [wiki_western.txt](/processed/hy_wiki_western.txt)
- [bi_freq_wiki_western.txt](/dataset/bi_freq_wiki_western.txt)
  - 144,228 bigram frequencies generated from [wiki_western.txt](/processed/wiki_western.txt)

## Processed

- [wiki_eastern.txt](/processed/wiki_eastern.txt)
  - 270,005 Eastern Armenian sentences extracted from wikipedia by [@ekeleshian](https://github.com/ekeleshian) using this extractor [script](https://github.com/ekeleshian/wikiextractor/blob/liz-branch/extract_sentences_hy.py).
  - You can see some more context around the dataset in [this PR](https://github.com/common-voice/common-voice/pull/3067) to the [common_voice](https://github.com/common-voice/common-voice) repo.
- [wiki_western.txt](/processed/wiki_western.txt)
  - 24,189 Western Armenian sentences extracted from wikipedia by [@ekeleshian](https://github.com/ekeleshian) using this extractor [script](https://github.com/ekeleshian/wikiextractor/blob/liz-branch/extract_sentences_hy.py).
  - You can see some more context around the dataset in [this PR](https://github.com/common-voice/common-voice/pull/3067) to the [common_voice](https://github.com/common-voice/common-voice) repo.

## Raw

- todo
