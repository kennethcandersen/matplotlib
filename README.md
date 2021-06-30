##STATISTICAL ANALYSIS OF A PHARMACEUTICAL STUDY ON 249 MICE
 
 <table style="width:100%">
  <tr valign="top">
    <th><img height="300" alt="Average Salaries Histogram" src="https://github.com/kennethcandersen/sql-challenge/blob/main/output_charts/average_salary_histogram.jpg"></th>
    <th><img height="300" alt="Average Salaries by Position" src="https://github.com/kennethcandersen/sql-challenge/blob/main/output_charts/average_salary_by_position.jpg"></th>
  </tr>
</table> 


249 mice received cancer treatment over 45 days from 10 different trial drugs. The mission was to analyze results from observations and determine the relative success of one drug (Capomulin) to reduce tumor sizes, compared to the other 9 competitors. 

The project utilized Python, Pandas in Jupyter Notebook, and Matplotlib to visualize the data. 

**CONCLUSIONS**
  
**1. Only capomuline and ramicane seem effective - at first glance** 

Figuring that all mice started treatment with tumor sizes of 45, then only 2 drugs finished the study with average tumor size less than 45: Capomuline and Ramicane.

**2. Very strong correlation coefficient of .88 between mouse weight and final tumor volume**

All mice started the study with tumor volume at 45. The the weight of thie mice mouse could have had an influence on final tumor volume.

**3. The data needs to be analyze again and controlled for mouse weight**

A hypothesis could be that the two drugs that seemed to be successful happened to have a disproportionate number of light mice in their subset.

Mice did not seem to change weight during the study. The average weight for the successful drugs was 20 grams, versus 27 grams for the unsuccessful drugs. Therefore, a
hypothesis could be that a very large percentage of success count be attibuted to testing on lighter mice. Again, this is assuming that mouse weight did not change during the
duration of the study. Further study is recommended to control for mouse weight.


