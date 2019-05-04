# Dig That Lick & Jazzomat 
Material for the Dig That Lick lecture/workshop, May 6th 2019 at the JLU Gießen (part of the course "From No Time to Ragtime" by Andrew Wilson).
## Hands-on Exercises
### Tools
All tools accessible via https://jazzomat.hfm-weimar.de/interactive.html

* Feature History Explorer
* Pattern History Explorer
* Dig That Lick Pattern Search
* Dig That Lick Similarity Search

Choose excersises freely. You might want to start with tasks in bold. Group work highly recommended. Send me your results if you want feedback. Have fun! 

## Feature History Explorer
Visualizes development of solo features in the WJD over time.
  * x-axis: recording year (or decade).  
  * y-axis: selected feature. 
  * Scatterplot with (polynomial) regression line.
  * Goodness-of-fit values: R2, p value, AIC.
  * With or without aggregation.
  * Filtering, colouring, and presentations options.
  
Link: https://jazzomat.hfm-weimar.de/feature_history_jazz/

#### Questions & Tasks (select as you wish)
  * **What das abs_int_range mean? Give an intuitive explanation**.
  * What drives the trend in abs_int_range?
  * **What does CDPCX mean?**
  * **Which CDPCX values show significant trends?**
  * How do trends changes when you select “Mean” aggregation? Why? 
  * Find a feature with a much better quadratic trend ( = larger R2 and smaller AIC).
  * **Which solo has the highest event density, which the lowest?**
  * Which feature has the strongest aggregated trend?
  
## Pattern History Explorer
* Contains selection of 653 common interval patterns by eminent performers and its instances in the WJD.
* See “Help” tab for further details
* Listen & See: Shows pattern instances (score, audio, metadata)
* Instances: More detailed info on instances
* Stats: Stats for the pattern and its instances
* Timeline: Distribution of instances over recording time and performers
* General Stats: Stats of all patterns

Link: https://jazzomat.hfm-weimar.de/pattern_history/

#### Questions & Tasks (select as you wish)
  * **Find the longest arpeggio patterns. Who owns it?**
  * Find the longest “non-trivial” pattern. What can be said of its start pitch, harmonic context, accent pattern?
  * Find the most frequent pattern with the longest stretch of an ascending or descending whole tone scale. Who owns it? Who played it first (in the WJD)? Which are more common: ascending or descending?

## Dig That Lick Pattern Search
* Allows very flexible search for patterns in the WJD, the Essen Folk Song Collection and the Omnibook.
* Entry via abstract notation or virtual keyboard.
* Many different types of patterns. (“transformations”)
* Secondary search (search in search results).
* Metadata filter
* Displays scores and audios + additional metadata.

Link: https://dig-that-lick.hfm-weimar.de/pattern_search/

#### Questions & Tasks (select as you wish)
* Find “The Lick” in the WJD. Does it exist in the Essen Collection and the Omnibook? (Find the Lick in the internet if you don't know it, e.g., https://www.facebook.com/thelickpage/).
* **Find the beginning of “Hänschen Klein” in the WJD. Which is the most similar instance, why? Why are other instances not similar at all?**
* Repeat one of the previous searches Lick with tone context of 2 or more tones before and after. How does it change the pattern impression? What are the most common pre/successions?
* Find the longest ascending whole tone scale segment (within a single phrase) with only one search request.

## Dig That Lick Similarity Search
* Allows similarity search for patterns in the WJD,.
* Entry via abstract notation or virtual keyboard.
* Interval, fuzzy interval, pitch and CDPCX patterns.
* Metadata filter.
* Filter for extra conditions.
* Displays audios + additional metadata.
* Timeline and network visualizations.

Link: https://dig-that-lick.hfm-weimar.de/similarity_search/

#### Questions & Tasks (select as you wish)
* **How would you define pattern similarity? How did we define it?**
* **Search for an interval pattern of choice with 5 elements. How many instances for similarity thresholds 1, .75, .5 and maximal length difference 0, 1, 2 do you get?** 
* Search for “The Lick” with min sim = .8, max diff = 0. Then repeat: Start new similarity search (right click on the pattern) for the most frequent and most similar but not identical pattern. Does “The Lick” disappear from the result set? What happens? Why?
* Find the most frequent 8-interval pattern by Chris Potter and play it at half speed. Who owns the pattern? How might it reflect influences? What is the most common start pitch? How does is mostly fit the chords? (Tip: Don’t forget the PHE).

