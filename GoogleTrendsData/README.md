## Google Trends Project
Alex Papa 01/01/2020
#### __Notebooks__
- pytrends_data: template notebook
- trends_returns_analysis: terms from related queries on google trends
- trends_PCA_method: game names terms, many gaps, didnt apply PCA

#### __Stage 1__

- [x] Create list of search terms

- [ ] Data Wrangling
  - [ ] Stemming
  - [ ] Remove stop-words
  - [ ] Remove notation

- [ ] PCA

- [ ] DASH Visualization
  - [ ] Python
  - [ ] R

#### __Issues__
- google correlate has been discontinued
- google terms dataset has many gaps with nonsensical values (not 0-100)
- Issue arose from querying multiple terms together causing the ratio of searches is lost


#### Additional Ideas
- Better Term selection by processing STEAM comments / Company minutes / Filings
- Create regression models (RF, NLP) to predict intent behind search terms and assign to classes. (Better than simply volume)
  - fillings (https://seekingalpha.com/symbol/ATVI/earnings/transcripts)
