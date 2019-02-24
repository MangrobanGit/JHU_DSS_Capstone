rm( list = ls() )

# commonly used libraries
library(caret)        # ML 
library(glmnet)       # regressions
library(rpart)        # decision trees
library(rpart.plot)   # tree plotting
library(DataExplorer) # EDA 
library(tidyverse)    # tidy data and plots
library(kableExtra)   # pretty tables
library(flextable)    # pretty tables for word docs
library(data.table)   # data handling
library(pROC)         # ROC plots and metrics
library(scales)       # scaling and other helpers
library(stats)        # AIC/BIC
library(gridExtra)    # Gridded plots
library(glmnet)       # glms, ridge, lasso, enet
library(mice)         # imputation
library(VIM)          # viz missing data
library(fastDummies)  # fast binarizers - using dummy_cols

# Text Mining
# library(tm)
# library(qdap)
# library(RWeka)
# library(NLP)
# library(SnowballC)
# library(wordcloud)
library(quanteda)
library(readtext)

# Set seed for reproducibility
set.seed(2425)

### Other Initializations
# Set classification thresholds  
thresh_1 <- .50  
thresh_2 <- .75  
thresh_3 <- .90  

big_n = 30000 # Number of rows pulled from file. These are sequential
small_n = 500 # of rows sampled from the initial row pull

