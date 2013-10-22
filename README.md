aaron-project-hppr: Phrase Tagset Mapping for French and English Treebanks and Its Application in Machine Translation Evaluation
==================

Welcome to the aaron-project-hppr!

In the paper "Phrase Tagset Mapping for French and English Treebanks and Its Application in Machine Translation Evaluation",
a universal phrase tagset containing 9 commonly used phrasal categories is proposed, including NP (noun phrase), 
VP (verbal phrase), AJP (adjective phrase), AVP (adverbial phrase), PP (prepositional phrase), S (sub-sentence), 
CONJP (conjunction phrase), COP (coordinated phrase), and X (a less clear category, e.g. describing list marker, 
foreign words, interjection, abbreviation, idiosyncratic unit, unknown or uncertain ones). The phrase tagset mapping 
between current treebanks (French and English) tagset and the universal phrase tagset has also been designed in the paper.
Furthermore, using the proposed universal phrase tagset and the mapping work, a novel unsupervised machine translation 
evaluation metric HPPR is proposed.



HPPR is open source, free for research purpose.

HPPR: Phrase Tagset Mapping for French and English Treebanks and Its Application in Machine Translation Evaluation

HPPR is a machine translation evaluation metric for French-English language pair without using reference translations.
HPPR uses the developed French and English phrase tagset mapping and measuring algorithms to perform the machine 
translation evaluation. The evaluation is conducted on the phrase sequences of source sentence and target translation. 
The phrase sequences are converted into the designed Universal phrase tags before the measuring of similarity.


Experiments on ACL-WMT 2011 and 2012 French-to-English translation corpora show HPPR yields promising  correlation 
scores with human judgments as compared to the reference-aware metrics BLEU and TER. 
The Spearman rank correlation scores of HPPR with human judgments are 0.63 and 0.59 respectively on WMT11 and WMT12 corpus.

Detailed knowledge of HPPR is shown in the paper "Phrase Tagset Mapping for French and English Treebanks and Its 
Application in Machine Translation Evaluation" by Aaron Li-Feng Han, Derek F. Wong, Lidia S. Chao, Liangye He, Shuo Li,
and Ling Zhu. 2013. Proceedings of the GSCL 2013, Germany. LNCS Vol. 8105, pp. 119–131. Volume Editors: Iryna Gurevych,
Chris Biemann and Torsten Zesch. 

Source code: https://github.com/aaronlifenghan/aaron-project-hppr

Download paper: http://link.springer.com/chapter/10.1007/978-3-642-40722-2_13#

If you use the HPPR metric in your researches, please cite the paper. All rights reserved.

Contact: hanlifengaaron AT gmail.com
