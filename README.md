Data preprocessing & model creation in Main.ipynb.

Raw SKEMPI data: https://life.bsc.es/pid/skempi2/database/index

Info on prot_bert for amino-acid sequence encoding: https://huggingface.co/Rostlab/prot_bert

Trained model expects (n*2050) input, with 1024 features for wt amino-acid sequence (.pooler_output of prot_bert), 1024 features for mutant sequence encoded likewise, total number of mutations feature and mutation_location categorical feature.
