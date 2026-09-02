# mt-baseline-benchmark

**What:**
Build 3 statistical/embedding-based MT baselines for Hindi↔English.
Compute BLEU for each.

**Systems:**
1. Word-by-word dictionary lookup,
2. Statistical phrase-based alignment (`nltk.translate`),
3. Cross-lingual word embedding mapping (word2vec + Procrustes alignment).

**Dataset:**
IIT Bombay English-Hindi Parallel Corpus (10K subset)
