# ouswc_metrics

These are a collection of scripts to produce plots of various metrics for Carpentry workshops hosted by the OU Libraries. Currently we are tracking attendance and domain/department/center information about our learns to have some measure of the impact the Carpentries have here at the University of Oklahoma.

### Files

* metric_reporting.ipynb is the work in progress as the scripts are developed.
  * Currently this plots the number of learners who have attended workshops
  * Domains are scheduled to be worked on next.


### Data
* swc_lerner_count.csv
  * totals for learners in attendance
  * data for the early workshops was not kept, only the total for the year

> **Columns**
> date: start day and month of workshop as ###-MMM
> year: four digit integer number for year (eg. 2017)
> month: integer number for month (1-12)
> learners: integer number of learners(attendees)
> workshops: Integer number of workshops
> notes: additional notes regarding workshop

Workshop variable is 1 per event but has been designed to allow for values > 1 for the following:
* This is done to account for having only yearly workshop counts for 2014-2015
* This also allows for simultaneous workshops to occur in different locations on the same date
  * examle: Joint sessions to accommodate larger enrollment numbers or multiple session topics (eg. Python and R)
