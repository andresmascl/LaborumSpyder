# LaborumSpyder

This is one of the few projects I am able to make public, since the great majority of projects I have worked on are either too specific (to the point where it wouldn't make sence to share them in the first place) or deal with sensitive information for the client.

This Jupyter Notebook was written in order to determine the correlation between keywords (of technologies) and occupations being demanded in the chilean labor market, based on information scraped from the job board site laborum.com.

The client, a professional training company specializing on mining technology, wanted to find out if certain technologies were on demand in the chilean market for jobs in the mining industry.

A list of keywords was created which were used to determine if a certain job post required expertise in one of the technologies the client offered training on.

Another list containing professional career names available in the country is provided to the notebook for later comparison.

A web scraper built inside the Notebook uses the keywords list to make job searches on the jobs board site.

The results are saved in a list containing the urls to the resulting job posts.

The scraper then visits every url and saves the title of the position, the name of the company, and the details of the job.

Finally, the notebook returns a matrix of rows and columns where every row represents a specific career name (occupation) and every column represents a keyword for one of the technologies the client was interested on researching.  For every occupation matrix indicates how many job openings were found which contained each of the keywords provided.

Te matrix is saved in an excel file.

This notebook and the code within it is provided as is, for learning purposes only.
