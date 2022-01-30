# Model

This directory contains the hateSpeechDetection.Rmd file, which is the code with the natural language processing model.

To execute the code it can be done in RStudio, with the option ```knit to HTML```


# Data

The folder `Data` contains the datased stored as a CSV, where each instance contains 5 columns:

`count` = number of CrowdFlower users who coded each tweet (min is 3, sometimes more users coded a tweet when judgments were determined to be unreliable by CF).

`hate_speech` = number of CF users who judged the tweet to be hate speech.

`offensive_language` = number of CF users who judged the tweet to be offensive.

`neither` = number of CF users who judged the tweet to be neither offensive nor non-offensive.

`class` = class label for majority of CF users.
  0 - hate speech
  1 - offensive  language
  2 - neither
 
 `tweet` = text containing the analyzed tweet.
