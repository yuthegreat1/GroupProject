## Project Title: Stream it or Skip it: Netflix or Other Streaming Platforms
## Slideshow Presentation Link:
https://docs.google.com/presentation/d/1QqVZHWmqhooQMctipirPp16ylWK7wH9HcjRCZKoN9cA/edit?usp=sharing
## Research Questions to Answer: 
How Netflix Originals perform compared to other content on the platform?
## Team Members: 
Allie Carlile, Brevin Owens, Brandon Yu
## Datasets to be used: 
- Netflix Orignals https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores
- Netflix content https://github.com/victoramsantos/netflix-backend/blob/master/movie-scraper/resources/dataset/IMDB-Movie-Data.csv
- Hulu https://www.kaggle.com/datasets/shivamb/hulu-movies-and-tv-shows
- Amazon Prime Video https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows
- Disney https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows
- IMDB Ratings https://rapidapi.com/blog/how-to-use-imdb-api/
- Netflix Titles https://www.kaggle.com/datasets/shivamb/netflix-shows (new)
## Project Description/Outline:
We choose to analyze netflix originals because we wanted to compare the content that netflix makes compared to the content it hosts. We are all netflix watchers and curious about what's going to perform well. With netflix stock decreasing we want to see whether the influx of original content can improve netflix and stop its stock from decreasing. 
## Inital Questions:
    1. How does netflix's original content compare to content that netflix only hosts?
    2. How well does netflix's original content compare to the content being produced by other streaming companies like hulu or HBO?
    3. How well does the netflix originals do by language?
## Rough Breakdown of Tasks:
    pandas guru - will be responsible for finalizing data cleaning tasks - brevin
    matplotlib expert - will be responsible for creating visualizations - allie
    API enthusiast - will be responsible for data acquisition - brandon
    github power user - will be responsible for creating the group repo and merging pull requests - brandon
    statistician extraordinaire - will be responsible for finalizing analytical findings and backing up analysis with statistical tests - allie
    master of ceremonies - will be responsible for finalizing the presentation slides - brevin
    project management specialist - will be responsible for arranging group meetings, presenting reports, and keeping everyone moving - allie
## Statistical Analysis: 
1. Question 1: What content is Netflix focusing on versus other streaming platforms?
    - We changed this question and the order in the presentation to question 1, due to a limitation brought to us by the data set. We were unable to find data on original content by other streaming services, such as Hulu and HBO. Therefore, what we decided to focus on for this question was the current state of the platforms and how they differ from Netflix. We also took this a step further and looked at what type of content the companies have been uploading to their platform over the years. 
    - As of mid 2021, which is when our data sets collected this data, Netflix had a majority of movies on there platform. Which is also true for Amazon Prime Video and Disney+. However, Hulu is different as they primarily have TV shows on their platform as shown by the folllowing images: 

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/NetflixContentCount.png?raw=true)

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/HuluContentCount.png?raw=true)

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/DisneyContentCount.png?raw=true)

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/AmazonContentCount.png?raw=true)

    - As stated above, we then took the question a step further and decided to look at the content that was uploaded by year for the platforms. What we found here is displayed by the following figures: 

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/NetflixUploadsByYear.png?raw=true)

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/HuluUploadsByYear.png?raw=true)

    ![alt text](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/DisneyUploadsByYear.png?raw=true)

    - We decided not to include a image for Amazon Prime Video here as our data set that we used had a lot of NA values for the date uploaded. So much so that the only year we had data for was the most recent year of upload, 2021. This was still helpful though, as it told us that Amazon Prime Video has a current focus on TV Show uploads. For the other streaming services, Netflix of course had a lot of movie uploads over the years, but in the last year had a sharp decline in movie uploads whereas the TV Show uploads stayed fairly consistent. This leads us to believe that Netflix is currently focusing on TV Shows versus movies. As for Hulu and Disney+, Hulu appears to have a heavy focus on movie uploads as they have consistently uploaded more and more movies over the last few years. Lastly, for Disney+, we only have the last 3 years of uploads available (2019-2021), but this is because Disney+ is a young platform that is just 3 years old. In their first year as a platform, they uploaded a lot of movies compared to TV Shows but this quickly changed as the uploads were very similar in 2021. This leads us to believe that Disney+ also has a similar focus on TV Shows similar to that of Netflix. 
    - Overall, what this question showed us is that Netflix has a lot of content on their platform and tends to lean on TV Shows in the last few years which differs from one of their counterparts - Hulu. However, Netflix seems to be on the same track as Disney+ and Amazon Prime so we had to look at other data sources to determine why they have struggled in recent years. 
2. Question 2: How does Netflix's original content compare to content that Netflix only hosts?
    - We moved this question second as it better flowed in the presentation.
    - The content that Netflix creates as opposed to the content that Netflix syndicates or hosts is, on average, worse. This indicates that the content Netflix creates is not of as high of quality as the content that it hosts. Even when splitting the content by genre, Netflix originals are not as highly rated as content that Netflix syndicates.
    - (see image below)

    ![alttext](https://github.com/yuthegreat1/GroupProject/blob/main/Figures/NetflixOriginalsvsNetflixRatings.png?raw=true)
    
    - Which makes sense when you consider that Netflix actively acquires the content due to its performance. Content that does poorly would not be acquired. Content that Netflix creates does not go through this vetting process and would be expected to do worse. Another reason for this discrepancy in quality would be because the dataset is the top-rated Netflix movies for our content.

    