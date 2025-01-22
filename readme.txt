******************************************************************************
LinkedIn Post Sentiment Analysis
Overview
R script for sentiment analysis of LinkedIn posts and responses using VADER.

******************************************************************************
REQUIREMENTS

R-Studio
tidyverse package 
vader package 

******************************************************************************
TEXT FILE PREPARATION

Prepare linkedin_posts.txt in same directory as rmd
Input file format:

One post/response per line, text that extends onto following line will work fine.

Prefix posts with p,, 
Prefix responses with r,, 

Example:

r,,Congratulations on your achievement!
p,,Attending an amazing conference this week
r,,Sounds like a great opportunity

******************************************************************************
FUTURE VERSIONS

It would be fun to hook into LinkedIn's API, wouldn't plan on doing more with this unless I complete that step, importing would be tedious. 