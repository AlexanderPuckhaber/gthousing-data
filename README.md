# gthousing-data

### [Visualization Webpage](https://alexanderpuckhaber.github.io/gthousing-data.github.io/) 
(based on [gthousing.tk from 2019](https://web.archive.org/web/20190309002436/http://gthousing.tk/), which I am not affiliated with and basically just copied the code for).  
And *always* check [https://housing.gatech.edu/available-rooms](https://housing.gatech.edu/available-rooms) for the official, most recently updated list.  
And keep in mind that some rooms you won't be able to register for for various reasons, from LLC to other restrictions.

The purpose of this project is to web-scrape data from [http://housing.gatech.edu/rooms/FreeRooms.json?](http://housing.gatech.edu/rooms/FreeRooms.json?) using GitHub Actions.

I just followed this tutorial: [https://simonwillison.net/2020/Oct/9/git-scraping/](https://simonwillison.net/2020/Oct/9/git-scraping/)

Data goes to the [/data/F21-S22/](/data/F21-S22/) folder. The timestamps are unix timestamps; see the commit messages for the timezone.

Also, the latest json file is put here: [/data/F21-S22/latest/latest.json](/data/F21-S22/latest/latest.json)
