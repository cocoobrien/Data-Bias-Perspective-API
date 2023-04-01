# Data-Bias-Perspective-API
Explores the concept of bias through querying an existing natural language processing model — specifically, the Perspective API released by Google Jigsaw. Evaluates Perspective API's accuracy and consistency when evaluating the same text or message translated in different languages to produce a toxicity scores. 

I hypothesized that the Italian comments would score lower than the English comments, even though they have been directly translated into one another with no context altered. To do so, I pulled sample comments from the initial dataset and created some of my own to build a diverse sample. This sample included 25 English comments, with their complementary Italian-translation in another feature column.

Given that English is the most popular language in the world and spoken by 1.5 billion people worldwide, I assumed that these comments have not only had greater testing and analysis, but are consequently likely to be graded more harshly than those in a different language. This would prove to be a weakness for the API as harmful, offensive, abusive, or dangerous comments could be posted to the internet undetected. If my hypothesis proves to be true, I would recommend Google Jigsaw and all those using the API to invest more time into strengthening the NLP’s accuracy across foreign languages.

LICENSE: This project is licensed under the terms of the MIT license.

Results:

I was correct in my hypotheses that Perspective API would not produce consistent scores when analyzing the same comment text, but in different languages. There are reportedly 7,106 living languages in the world. While it is an admirable goal to strive to be as inclusive as possible with this API, a good place to start in terms of training it with different foreign languages is shifting focus to the top 5 or perhaps top 10 spoken around the world. As a result,  Perspective API would not only produce scores with greater accuracy, but this would also allow it to become far more globally accessible, useful, and impactful to monitoring the prevalence of toxicity online.  

While these results do show a significant difference in scoring different languages, I recognize that when translating text into another language, there are often differences in cultural context, meaning, syntax and, grammar.
