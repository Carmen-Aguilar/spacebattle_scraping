# Private launches driving space exploration

The Israel's moon mission gives us an opportunity to explore space data. If the spacecraft Beresheet succeeds on Thursday 11, it will be the first private space expedition in touching the moon.

We then used historical data in the story [Israel's moon mission set to make space exploration history](https://news.sky.com/story/israels-moon-mission-set-to-make-space-exploration-history-11688719) to put this expedition into context and to enrich the story by showing how the private sector has been driven space exploration since the 90s.

## Data gathering and analysis

After consulting sources from the space industry, we were adviced to use [Jonathan's Space Report](http://www.planet4589.org/) to collect historical launches. We selected only orbital launches (see the difference with the suborbital [here](https://exosaero.com/2016/04/05/suborbital-vs-orbital-flights/)) and we were interested in knowing how many of them came from state agencies and how many from private sector. As a second level, we thought it may be an interesting line to look at the "success rate" in the launches.

The [R book](https://github.com/Carmen-Aguilar/spacebattle_scraping/blob/master/space.Rmd) explains the process of getting the data and the analysis we did. It also contains links to the data and to the definitions and documentation. It may be worth spending time (more than ususal) understanding it as the subject is a quite hard to understand if you are not used to report about space stories. 

It was particularly useful the `read.fwf()` function which I hadn't used before and it was key to scrape the information. 

## Visualisation

We visualised the story using Flourish:
- The <strong>race barchart</strong> shows the competition between US and USSR before the 90s, the emergence of the private companies and the irruption of China during the last decade. 
- The <strong>histogram</strong> shows the volume of launches public and privately supported each year. 
- The <strong>bar chart</strong> shows the main private companies. 
