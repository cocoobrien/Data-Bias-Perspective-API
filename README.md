# Data-Bias-Perspective-API
This study delves into the concept of bias by interrogating the Perspective API, specifically Google Jigsaw's offering. The examination revolves around assessing the accuracy and consistency of the Perspective API when evaluating identical text or messages translated into distinct languages, aiming to generate toxicity scores.

My hypothesis posited that Italian comments would yield lower scores than their English counterparts, even when directly translated without altering context. To test this, I curated a sample from the initial dataset, comprising 25 English comments paired with their corresponding Italian translations in a separate feature column.

The rationale behind this exploration stems from the prominence of English, spoken by 1.5 billion people globally. I presumed that English comments, being more widely tested and analyzed, might receive harsher evaluations. This potential bias could lead to undetected harmful or offensive content online, exposing a vulnerability in the API. If proven true, my recommendation is for Google Jigsaw and users of the API to dedicate efforts to enhance the NLP's accuracy across various languages.

LICENSE: This project is licensed under the terms of the MIT license.

CSV File/Dataset Attributes:

- English Comment: Text for analysis in English
- Italian Comment: Italian translation of the English comment for analysis
- English Score: Perspective API 'toxicity score' for the English translation produced by the AnalyzeComment function
- Italian Score: Perspective API 'toxicity score' for the Italian translation produced by the AnalyzeComment function

Results:

The findings validate my hypothesis that the Perspective API exhibits inconsistency in scoring when analyzing identical text in different languages. Acknowledging the existence of 7,106 living languages worldwide, while inclusivity is commendable, a strategic approach could involve prioritizing the top 5 or 10 most spoken languages for training. This targeted focus would likely result in more accurate scores and enhance the API's global accessibility, utility, and impact in monitoring online toxicity.

It's crucial to note that these results showcase significant differences in scoring across languages, recognizing the inherent challenges in translating text, including disparities in cultural context, meaning, syntax, and grammar.
