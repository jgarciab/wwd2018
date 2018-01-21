EUSpeech is a new dataset of 18,403 speeches from EU leaders (i.e., heads of government in 10 member states, EU commissioners, party leaders in the European Parliament, and ECB and IMF leaders) from 2007 to 2015. These speeches vary in sentiment, topics and ideology, allowing for fine-grained, over-time comparison of representation in the EU.

For questions, contact Gijs Schumacher (g.schumacher@uva.nl) or Martijn Schoonvelde (h.j.m.schoonvelde@vu.nl).

This dataset contains the following files:

1) create_super_dtm.R - a R script that generates two files from speeches.zip: (1) "super.dtm" which is a document-term matrix of all speeches; (2) "supercorpus", which contains for all speeches their text and metadata

2) speeches.tar.gz - a file that contains all speeches english and translated speeches across institutions and countries in R data format

3) remove_words.csv - a csv file containing words removed when cleaning the speeches

4) super.dtm.Rdata - a document-term matrix for all English and Translated speeches (generated from create_super_dtm.R)

5) supercorpus.Rdata - all English and Translated speeches and their metadata (generated from create_super_dtm.R)

6) EUSpeech.pdf - the paper that introduces EUSpeech data, published in the Proceedings of the International Conference on the Advances in Computational Analysis of Political Text

7) speeches_csv.tar.gz - a file that contains all speeches english and translated speeches across institutions and countries in csv format

NB: These files can be opened in R. You will need to install the quanteda package to run the scripts.

install.packages("quanteda")
library(quanteda) 


When using the data, please the following citations:

Gijs Schumacher, Martijn Schoonvelde, Tanushree Dahiya, and Erik De Vries. 2016. EuSpeech. dx.doi.org/10.7910/DVN/XPCVEI, Harvard Dataverse, V2.

Gijs Schumacher, Martijn Schoonvelde, Denise Traber, Tanushree Dahiya and Erik de Vries. 2016. EUSpeech: a New Dataset of EU Elite Speeches. Proceedings of the International Conference on the Advances in Computational Analysis of Political Text.









