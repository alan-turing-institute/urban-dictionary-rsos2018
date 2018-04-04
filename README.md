# Urban Dictionary

This repository contains annotations and R analysis code for the RSOS article on Urban Dictionary by Nguyen, McGillivray and Yasseri.

Please contact Dong Nguyen if you have any questions.
# Data

* content\_type\_annotations\_merged.csv: This file contains the crowdsourced annotations on aspects of the content in Urban Dictionary (opinion versus meaning, familiarity, formality, proper nouns). Each definition was annotated by 3 workers. For example the *familiar\_1*, *familiar\_2* and *familiar\_3* columns contain the annotations on familiarity. The *familiar* column contains the final category based on majority vote.

* offensive\_annotations\_merged.csv: This file contains the crowdsourced annotations on the offensiveness of the content.

#Code

* content\_types.rmd: R code for analyzing aspects of the content in Urban Dictionary
* offensiveness.rmd: R code for analyzing the offensivess of the content.
* popularity\_content.rmd: R code for analyzing how different aspects affect the ranking of the definitions.