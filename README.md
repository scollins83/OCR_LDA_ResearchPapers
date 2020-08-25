# Teal Deer
### TLDR_LDA_and_Text_Summarization.ipynb is the primary current notebook. 
Currently just hacking notebook. The notebook scrapes text from a directory of academic research pdf's, 
and then does LDA on it for prioritization of reading, and then trains a text summarization model based on the abstracts of the papers--- that way, if you find more, you can use the model to summarize them right away. Dataset for this run included just a handful of papers on chatbots from arxiv, but this notebook has been tested on corpuses of several hundred documents from both arXiv and google scholar in another domain with favorable results. OCR portion relies on: https://github.com/euske/pdfminer/blob/master/tools/pdf2txt.py
<br><br>
NOTE: Partially refactored as a discord bot, deployed via Heroku, to summarize channels in discord and direct message the results to the user. Still working on a more permanent plan for deployment. 
**In process:** <br>
Convert the notebook to a straight .py script to add the text summarization, which aims to generate abstracts or short summaries for large blocks
of text (i.e., an abstract for the rest of a paper). So, not only could papers be prioritized, but could be
summarized as well.
<br><br>
**Planned updates - See project tab as well:**<br>
   + Finish out OCR from PDF files part
   + Complete the text summarization portion - Thanks to Siraj Raval for making the video: https://www.youtube.com/watch?v=ogrJaOIuBx4
   + Clean up into python scripts with test suites
   + Experiment with other front-end usecases: i.e., a slackbot is currently underway (notebook to be added later). 
   + Add a CI framework into this repo.
   + Cartoon for a fun logo :-)
