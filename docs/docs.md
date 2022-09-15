# merge sentiment tracker

**Eseoghene Efekodo**
14th September, 2022.

## about the project

## Notes

- The majority of current text analytical
  tools operating on social media datasets
  are disproportionally focused on sentiment
  analysis or polarity of opinions (positive,
  negative, or neutral)
- The metadata associated with social media
  activity specifies the creation of a post/tweet/
  check-in to the second and it is then up to the
  researcher to decide at what temporal level
  the data is aggregated. For example, does it
  make sense to plot sentiment around a specific event for every second or should a summary sentiment score be computed by minute, hour,
  day, week or month? For studies with a
  high n during a short burst of time a smaller
  aggregation may be appropriate, but for other
  studies where cases are limited it may be
  necessary to summarize data over a longer
  period.

- Sentiment analysis is an
  extremely popular text classification technique because the tone of text can convey a
  lot of information about the subject’s perspective and lead to aggregate analyses of
  reviews, message polarity, or reactions.

- the complexities and nuances
  inherent in language context make sentiment analysis less straightforward than spam
  detection.

- Sentiment analysis refers to the process of
  computationally identifying and categorising emotional polarity expressed in an
  utterance—e.g., to determine the relative
  negativity or positivity of the writer or
  speaker’s feelings.

## things to do

1. set up project structure ✅
2. figure out authentication ✅
3. get test data - in progress.✅
4. get software downloaded
5. start analysis ✨💃🏽

## Steps of the project

1. Tweepy installation and authentication.
2. Data Collection with Tweepy.
3. Data Cleaning.
4. Sentiment Analysis.
5. AFINN dictionary and emoji dictionary.
6. Add spaces before and after an emoji.
7. Computing the polarity of the tweets.
8. Analyzing the polarity of the tweets.
9. Future improvements and main challenges to overcome.
10. Analyzing the evolution of the polarity through time.
11. Summary of the project.

## how my code can be better

Create a pip-installable package instead of using brittle paths.
This is a more scalable solution using a `setup.py` file and a `__init__`.py file

## further work (research)

- analyze miner subreddits r/ethermining and r/gpumining to check sentiments before and after the merge. probably use praw for reddit data.
- here, i use AFINN. run analyses on the text data here with other sentiment analysis packages (nltk, vader, bayes filtering? et all) and then compare difference in results.

## blockers, further work (technical)

- Figure out a way to filter tweets with a specific text in twitter bio (like #btc in bio et al) with tweepy.
- Exclude tweets with links to manage spam😭
- move my exports from my scripts folder to the data folder and still work around these paths!
- only reference my afinn txt file from data!

## updates at 6:08am wat

1. r/gpumining is shut down. link - <https://www.reddit.com/r/gpumining/comments/xecer8/the_end_of_rgpumining/?utm_source=share&utm_medium=web2x&context=3>

### right now, i want to grab tweets from the past one hour with "the merge" or "ethereum merge" or "#ethereummerge"

## helpful links

<https://nono.ma/environment-variable-python-notebook-os-environ-get>

<https://medium.com/besedo-engineering/sentiment-analysis-part-1-a-friendly-guide-to-sentiment-analysis-963e09d9fc9b>

<https://medium.com/besedo-engineering/sentiment-analysis-part-2-how-to-choose-pre-annotated-datasets-for-sentiment-analysis-d79736e8c147>

<https://medium.com/besedo-engineering/sentiment-analysis-part-3-data-annotation-d0845d1a8a1b>

<https://medium.com/besedo-engineering/sentiment-analysis-part-4-a-survey-of-sentiment-analysis-methods-2ba84759f3d>

<https://appdividend.com/2020/12/10/how-to-convert-python-list-to-csv-file/>

<https://www.linuxtut.com/en/3417c91cc111e4f16ef3/>
