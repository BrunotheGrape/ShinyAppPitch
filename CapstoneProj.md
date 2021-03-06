Capstone Project Pitch
========================================================
author: Boyd Ingalls
date: March 19, 2017
autosize: true

Word Prediction App
========================================================

What it does:

You can enter a phrase of any length in English and the app will offer 6 predictions in declining probability of which word is likely to follow the submitted phrase.

How It Does It Work?
========================================================
The app uses a back off strategy leveraging tables with phrase fragments, 4 word, 3 word, and 2 word strings from 15,000 document samples. It takes the words you enter and looks at the last 3 words, the last 2 words, and the last word is, and determines what the most likely following word is in the data based on the proportion of instances each word shows up in the results. The app is coded to look at 5 and 6 word fragments however the code has been disabled for to reduce lag time.


What Would You Use The App For?
========================================================
The back off strategy can be used in business applications where the user wants to predict outcomes based on free form text. It can be used to analyze IT issue chats to determine the risk of a particular failure. Similarly it can be used by service centers to predict customer outcomes or sales following various service conversations or approaches. The uses are in fact many and varied.

How Can You Use This Type Of Analysis
====================================================
This app quantifies free form text analysis. Contexts in which it can be leveraged include:
 - Technology issue resolution chats
 - Customer service chats
 - Forensic document analysis
 - Your project here
