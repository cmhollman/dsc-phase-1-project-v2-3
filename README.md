![Header](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Images/banner.png)

# Microsoft Movie Analysis

**Author**: [Chris Hollman](mailto:chollman91@gmail.com)

## Overview

This project analyzes movie data pertaining to Microsoft's entry into film making. This is a brand new film studio with significant resources, but little experience with film making. Analysis of box office numbers and film critic reviews does reveal some trends as to why some films tend to perfrom better than others. Microsoft can use this data to help guide their decision making as the begin to produce feature films. 

## Business Problem

Microsoft needs insight into how to invest their resources. While Microsoft is a giant in other industries, they have no prior experience producting films. Microsoft can increase the liklihood that their early films will be successful by examining box office and film critic review data from previous movies. In doing this, Microsoft can gain a clearer understanding of what types of films tend to generate more profit, and which film professionals tend to make successful products. 

## Data

The data for this project comes from three sources:
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [The Numbers](https://www.the-numbers.com/)

These datasets contain extensive information from over 5000 movies including production budgets, box office performance, ratings, relase dates, and genres. The Rotten Tomatoes dataset contains data from of 54,000 film reviews.   

## Methods

This project uses descriptive analysis of Movie data, which can help show where Microsoft should focus their spending and who to partener with to start producing films.  

## Results

The most lucrative genres both in terms of ROI and profit, are animation, sci-fi, adventure, and family. There are a few other viable genres, but overall there is significant drop off in profitability outside of these categories
![profit_bar_plot](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Images/Profit%20Bar%20Plot.png)
![ROI_bar_plot](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Images/ROI%20Barplot.png)

The domestic and worldwide box office gross numbers shadow one another. The both peak in May and remain elevated through July. There are secondary peaks in March and November. The months with the lowest average box office performance are January and September.

![release_date_plot](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Images/Release%20Line%20Plot.png)

Lastly, I compiled a list of directors most frequently reviewed by top film critics. I then chose the top 15 based on ratio of postive ("fresh") reviews per negative ("rotten") review. The director with the most positive reviews within this subset is Clint Eastwood, the director with the highest fresh/rotten ration is Alexander Payne.

![director_review_plot](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Images/Director%20Review%20Plot.png)

## Conclusions

This analysis leads to three recommendations for Microsofts early films:

- **Focus on films that fall into the more lucrative genres.** For early films, Microsoft should focus on genres that have a history of performing well at the box office. They should produce mainly films that fall into one or more of the top genres on the ROI and profit bar charts.
- **From partenerships with the top 15 directors.** There is some nuance required here, as some of these directors will not have experience or interest in producing films that fall into the animation category in particular. In general, all of these directors have good reputations among influential critics and tend to generate positive reviews. 
- **Release high budget films during May-July.** While Microsoft should avoid having multiple releases overlap and compete with one another for ticket sales, it would be beneficial to stagger releases throughout peak months.

### Next Steps

Further analyses could provide more insight for Microsoft's new movie studio:

- **Further insight into secondary film earnings.** The study would include popularity on streaming services as well as sales of physical and digital copies. This would lead to a clearer picture of a films overall profitability.
- **Explore popular writers and actors.** This could be done with small tweaks the the existing code to produce lists of actors and writers similar to the top 15 directors list referenced in this study.
- **Analysis of flops** This analysis could identify trends in movies that performed more poorly than anticipated. This could yield valuable information about which pitfalls to avoid in Microsoft's films. 

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Microsoft_Project.ipynb) 

or review this [presentation](https://github.com/cmhollman/dsc-phase-1-project-v2-3/blob/master/Microsoft_Proposal_Slides.pdf).

For additional info, contact Chris Hollman at [chollman91@gmail.com](mailto:chollman91@gmail.com)


## Repository Structure

```
├── images
├── zippedData
├── Microsoft_Project.ipynb
├── CONTRIBUTING.md
├── LICESNSE.md
├── Microsoft_Proposal_Slides.pdf
└── README.md
```