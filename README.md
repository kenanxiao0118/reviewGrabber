# reviewGrabber
Grabbing reviews from rate my professor. Currenlty grabs the first 20 reviews given a link to a professor on ratemyprofessor.

To do:
  -Grab more than 20 reviews(must interact with js, maybe use selenium?)
  -Grab all professors. 


To run, you must have scrapy installed.

Instructions

1) Clone repository
2) Cd into reviewGrabber
3) run, scrapy crawl rmp -o reviews.csv.

This generates a file, reviews.csv, with the extracted info. 
