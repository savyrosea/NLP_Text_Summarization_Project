# Podcast_Text_Summarization_NLP_Project

# Overview
I spend countless hours a week absorbing podcasts, and I am also passionate about exploring new NLP technique. In this project I am comparing two text sumamrization models while summarizing some top 2021 podcast descriptions. Hopefully I discover a new podcast to listen to along the way!

# Data
The podcast descriptions and photos used in this project were scraped from a goodhousekeeping article that can be found here:
https://www.goodhousekeeping.com/life/entertainment/g28353940/best-podcasts/

# Text Summarization Using Pegasus
The first method of text summarization that I wanted to explore was PEGASUS. PEGASUS is the latest state-of-the-art model for abstractive summarization open-sourced by Google. I am using a Pegasus model that has been pre-trained on the XSUM dataset as well as using this huggingface page as a basis for my Pegasus model.
https://huggingface.co/google/pegasus-xsum

Read more about Pegasus here: 
https://ai.googleblog.com/2020/06/pegasus-state-of-art-model-for.html


# Text Summarization Using Google T5 Model
https://huggingface.co/transformers/task_summary.html

# My Findings
In general, Pegasus is more casual, fun, and grammatically correct, but sometimes takes too big of leaps that are not true. 
Google T5 is a much more accurate summarization but uses poor grammar, often leaving sentences hanging even if the summary hasn't met the max word requirement.

There were examples when the Pegasus preformed better than the Google T5 model:
example here

And vice versa:
example here
