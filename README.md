# Xbox Twitter Sentiment Analysis

A marketing analytics project using R to perform sentiment analysis on Twitter data around the **Xbox Series X** launch. Pulls ~18,000 tweets, cleans and tokenizes the text, and analyzes public sentiment toward the product release.

## Research Context

Built around the Xbox Series X launch window. Searches Twitter for variations of "xbox series x", "xbox release", "microsoft xbox series x", and related terms to capture public reaction.

## What It Does

- Connects to the Twitter API via `rtweet` to pull up to 18,000 tweets in English
- Cleans and deduplicates tweet text (lowercasing, removing stop words)
- Tokenizes text using `tidytext` and `unnest_tokens`
- Identifies top words and phrases associated with Xbox Series X
- Performs sentiment scoring using NLP lexicons
- Generates word clouds and sentiment visualizations

## Stack

- R / R Markdown
- rtweet, tidytext, tidyverse, wordcloud, tm, stringr, lubridate

## Files

- `Marketing Analytics Project.Rmd` — full analysis

