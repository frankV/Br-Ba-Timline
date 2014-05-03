The [Br]eaking [Ba]d Timeline
=============

####This project aims to create a visual timeline representation of AMC's Breaking Bad.

##Episode Data Collected From:
Data for Epsiodes up to Season 5 - Part 1
<br>[A Year in the Life of Walter White: A Breaking Bad Timeline](http://blog.thegreenfieldgroup.org/a-year-in-the-life-of-walter-white-a-breaking-bad-timeline/)
<br>by Sean Aranda

Data for Episodes up to Season 3
<br>[How Much Time Has Passed on Breaking Bad?](http://www.vulture.com/2011/07/breaking_bad_calendar.html)
<br>by Ray Rahman

Epsiode meta-data collected from [IMDb](http://imdb.com)
<br>using [IMDbPy](http://imdbpy.sourceforge.net/)


##Running the Episode Scraper
```bash
$ python scrape-eps.py data/seasons_time_guide.html
Walt's birthday = 1957-09-07
Walt's 50th = 2007-09-07
First calendar day in show = (2007, 36, 5)


1.1: "Pilot," (3 weeks) Calendar Duration: 2007-09-07 to 2007-09-28
1.2: "Cat’s in the Bag … " (3 weeks, 2 days)  Calendar Duration: 2007-09-28 to 2007-09-10
...
5.3: "Hazard Pay," (50 weeks) Calendar Duration: 2008-08-01 to 2008-08-22
5.4: "Fifty-One," (52 weeks)  Calendar Duration: 2008-08-22 to 2008-09-05
```

<br>
##Software Resources and Dependencies
Flask
<br>MongoDB
<br>IMDbPy
<br>BeautifulSoup4
<br>Bootstrap

<br>
##Project Creators
[Emily Morehouse](/emilyemorehouse)
<br>
[Frank Valcarcel](/frankv)