dblpscholarscrapeopensource
===========================
Goal of the repo is to scrape dblp for particular conferences, then see if the papers are available openly. We scrape Google Scholar using Scholar.py to find that. The code will output a  csv file containing the paper title, title returned from scholar search (why this?), citations, years and link to the open source version, if any. 

to run:

python scrapeDBLP.py [conf. name as in dblp, for ex: jcdl/sigir] [start year (2000) [endyear (2013)] [outputfilename to save dblp scraping output]

python scholar-check-opensource-inptxt.py [outputfilename to save dblp scraping output] [csv-file-to-save-the-open-source-data]
