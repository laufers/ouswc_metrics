# ouswc_metrics

These are a collecton of scripts to produce plots of various metrics for Carpenty workshops hosted by the OU Libraries. Curently we are tracking attendence and domain/department/center information about our learns to have some measure of the impact the Carpentries have here at the UNiversity of Oklahoma. 

### Files

* metric_reporting.ipynb is the work in progress as the scripts are developed. 
  * Currently this plots the number of learners who have attended workshops 
  * Domains are scheduled to be worked on next.
  
  
### Data
* swc_lerner_count.csv
  * totals for learners in attendence 
  * data for the early workshops was not kept, only the total for the year
  
date: start day and month of workshop as ##0-MMM
year: four digit integer number for year (eg. 2017)
month: integer number for month (1-12)
learners: integer nuber of learners(attendees)
workshops: Integer number of workshops 
* This is done to account for no individual workshop counts in 2014-2015
* This also allows for simutations workshops to occer in differeent locations on the same date
  * Joint sessions to accomidate numbers or topics (eg. Python and R)
notes: additional notes regarding workshop
  
