# data-512-homework_1

This repository contains the necessary notebooks and files required for homework 1. The goal of this assignment is to retrieve user view counts for dinosaur Wikipedia pages from the Pageview API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end), [data license](https://dumps.wikimedia.org/legal.html)) using the Wikimedia REST API ([website](https://www.mediawiki.org/wiki/Wikimedia_REST_API), [terms of use](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions)). Then, after retrieving the data and storing it, create timeseries visualizations utilizing the Wikipedia dinosaur view count data.

The notebooks in the main folder of the repository, with all modules declared in the first cell. Section 1 of the homework was completed using file_extraction.ipynb with the outputs being stored in the data folder. The data goes from July 2015 to September 2022. Earlier data cannot be retrieved as Wikimedia does not have it accessible. Section 2 of the homework was completed using timeseries_visualizations.ipynb with the outputs being stored in the data folder.

All three data files have the same objects: project is the website the data comes from, article is the name of the Wikipedia page for the dinosaur, granularity is the level of detail the data is grouped at, timestamp is the date of the data, agent is what type of views are being counted, and views are the number of views.

All visualizations are timeseries where the date is the x-axis and views is the y-axis.
