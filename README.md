# Hard-Skill-Detection

Problem Statement:

- Develop a code that can clean a dataset containing technical jargon and extract Technical (Hard) skills
- Technical skills are defined as demonstrable and quantifiable skills. They can be tested to prove their capacity in each hard skill an individual possesses
- Sample of 900 random examples of technical skills will be provided

Approaches:

- Identify acronyms
- Identify words that are not in dictionary
- Create reference using Example list
- Consider frequencies of words in the English language to identify unusual words/common words
- Treat numeric values
- Treat empty values

Libraries used: 
- numpy 
- pandas 
- re
- wordfreq 
- random

English word list (words.csv) obtained from:

https://github.com/dwyl/english-words

Results contained in HardSkill2.csv. Some considerations:

- Accuracy of the model was of 92% when using a sample of 25 data points
- Data set contained large number of hard skills, would have to try with a data set containing mostly soft skills
- Hard skills not extracted from sentences 
- Frequency of words library contained samples from many sources, including websites. Fiction based library could provide more reliable frequency values for tech words
- Further increase hard skill word bank
- Use NLTK tools to better analyze the language and adapt to never-before-seen cases








