# pandas-challenge  
### Robert Lane  |  RobertLaneJr@gmail.com  |  github.com/RL-Lane  

Below is listed a summary of a generated dataset designed to compare high schools.  This will summarize various categories of the provided data in order to present data-driven analysis.  The scores here are based upon standardized test scores for both reading and math.  It should be noted both that correlation is not causation and that the dataset of individual schools is too small in order to be able to predict performance of other schools by type.

As demonstrated within the data tables below, the first notable and observable trend is that within this district, charter schools seem to greatly outperform the district schools.  The combined effect of improved reading and math scores shows that in this dataset, charter school students are nearly twice as likely to pass both reading and math standardized tests as district students.

The second trend seen in this dataset is that *lower* budgets per student corresponds with higher passing rates in both math and reading, although it is most pronounced for math scores.  

## District Summary:  

| **Total Schools** 	| **Total Students** 	| **Total Budget** 	| **Average Math Score** 	| **Average Reading Score** 	| **% Passing Math** 	| **% Passing Reading** 	| **% Overall Passing** 	|
|------------------:	|-------------------:	|-----------------:	|-----------------------:	|--------------------------:	|-------------------:	|----------------------:	|----------------------:	|
|         15        	| 39,170             	| 24,649,428       	| 78.99                  	| 81.88                     	| 74.98              	| 85.81                 	| 65.17                 	|


## Schools Summary:  

|                **School** 	| **Type** 	| **Student Count** 	| **Total Budget** 	| **Budget Per Student** 	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|--------------------------:	|---------:	|------------------:	|-----------------:	|-----------------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
|   **Bailey High School**  	| District 	| 4,976             	| 3,124,928        	| 628.0                  	| 77.05              	| 81.03                 	| 66.68             	| 81.93                	| 54.64             	|
|  **Cabrera High School**  	| Charter  	| 1,858             	| 1,081,356        	| 582.0                  	| 83.06              	| 83.98                 	| 94.13             	| 97.04                	| 91.33             	|
|  **Figueroa High School** 	| District 	| 2,949             	| 1,884,411        	| 639.0                  	| 76.71              	| 81.16                 	| 65.99             	| 80.74                	| 53.20             	|
|    **Ford High School**   	| District 	| 2,739             	| 1,763,916        	| 644.0                  	| 77.10              	| 80.75                 	| 68.31             	| 79.30                	| 54.29             	|
|  **Griffin High School**  	| Charter  	| 1,468             	| 917,500          	| 625.0                  	| 83.35              	| 83.82                 	| 93.39             	| 97.14                	| 90.60             	|
| **Hernandez High School** 	| District 	| 4,635             	| 3,022,020        	| 652.0                  	| 77.29              	| 80.93                 	| 66.75             	| 80.86                	| 53.53             	|
|   **Holden High School**  	| Charter  	| 427               	| 248,087          	| 581.0                  	| 83.80              	| 83.81                 	| 92.51             	| 96.25                	| 89.23             	|
|   **Huang High School**   	| District 	| 2,917             	| 1,910,635        	| 655.0                  	| 76.63              	| 81.18                 	| 65.68             	| 81.32                	| 53.51             	|
|  **Johnson High School**  	| District 	| 4,761             	| 3,094,650        	| 650.0                  	| 77.07              	| 80.97                 	| 66.06             	| 81.22                	| 53.54             	|
|    **Pena High School**   	| Charter  	| 962               	| 585,858          	| 609.0                  	| 83.84              	| 84.04                 	| 94.59             	| 95.95                	| 90.54             	|
| **Rodriguez High School** 	| District 	| 3,999             	| 2,547,363        	| 637.0                  	| 76.84              	| 80.74                 	| 66.37             	| 80.22                	| 52.99             	|
|  **Shelton High School**  	| Charter  	| 1,761             	| 1,056,600        	| 600.0                  	| 83.36              	| 83.73                 	| 93.87             	| 95.85                	| 89.89             	|
|   **Thomas High School**  	| Charter  	| 1,635             	| 1,043,130        	| 638.0                  	| 83.42              	| 83.85                 	| 93.27             	| 97.31                	| 90.95             	|
|   **Wilson High School**  	| Charter  	| 2,283             	| 1,319,574        	| 578.0                  	| 83.27              	| 83.99                 	| 93.87             	| 96.54                	| 90.58             	|
|   **Wright High School**  	| Charter  	| 1,800             	| 1,049,400        	| 583.0                  	| 83.68              	| 83.96                 	| 93.33             	| 96.61                	| 90.33             	|

## Top 5 Schools (by percentage passing both reading and math):

|              **School** 	| **Type** 	| **Student Count** 	| **Total Budget** 	| **Budget Per Student** 	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|------------------------:	|---------:	|------------------:	|-----------------:	|-----------------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
| **Cabrera High School** 	| Charter  	| 1,858             	| 1,081,356        	| 582.0                  	| 83.06              	| 83.98                 	| 94.13             	| 97.04                	| 91.33             	|
|  **Thomas High School** 	| Charter  	| 1,635             	| 1,043,130        	| 638.0                  	| 83.42              	| 83.85                 	| 93.27             	| 97.31                	| 90.95             	|
| **Griffin High School** 	| Charter  	| 1,468             	| 917,500          	| 625.0                  	| 83.35              	| 83.82                 	| 93.39             	| 97.14                	| 90.60             	|
|  **Wilson High School** 	| Charter  	| 2,283             	| 1,319,574        	| 578.0                  	| 83.27              	| 83.99                 	| 93.87             	| 96.54                	| 90.58             	|
|   **Pena High School**  	| Charter  	| 962               	| 585,858          	| 609.0                  	| 83.84              	| 84.04                 	| 94.59             	| 95.95                	| 90.54             	|


## Bottom 5 Schools (by percentage passing both reading and math):  

|                **School** 	| **Type** 	| **Student Count** 	| **Total Budget** 	| **Budget Per Student** 	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|--------------------------:	|---------:	|------------------:	|-----------------:	|-----------------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
| **Rodriguez High School** 	| District 	| 3,999             	| 2,547,363        	| 637.0                  	| 76.84              	| 80.74                 	| 66.37             	| 80.22                	| 52.99             	|
|  **Figueroa High School** 	| District 	| 2,949             	| 1,884,411        	| 639.0                  	| 76.71              	| 81.16                 	| 65.99             	| 80.74                	| 53.20             	|
|   **Huang High School**   	| District 	| 2,917             	| 1,910,635        	| 655.0                  	| 76.63              	| 81.18                 	| 65.68             	| 81.32                	| 53.51             	|
| **Hernandez High School** 	| District 	| 4,635             	| 3,022,020        	| 652.0                  	| 77.29              	| 80.93                 	| 66.75             	| 80.86                	| 53.53             	|
|  **Johnson High School**  	| District 	| 4,761             	| 3,094,650        	| 650.0                  	| 77.07              	| 80.97                 	| 66.06             	| 81.22                	| 53.54             	|

## Math Scores Per School, Per Grade Level:

|            **School** 	| **9th** 	| **10th** 	| **11th** 	| **12th** 	|
|----------------------:	|--------:	|---------:	|---------:	|---------:	|
|   **Bailey High School**  	| 77.08 	| 77.00 	| 77.52 	| 76.49 	|
|  **Cabrera High School**  	| 83.09 	| 83.15 	| 82.77 	| 83.28 	|
|  **Figueroa High School** 	| 76.40 	| 76.54 	| 76.88 	| 77.15 	|
|    **Ford High School**   	| 77.36 	| 77.67 	| 76.92 	| 76.18 	|
|  **Griffin High School**  	| 82.04 	| 84.23 	| 83.84 	| 83.36 	|
| **Hernandez High School** 	| 77.44 	| 77.34 	| 77.14 	| 77.19 	|
|   **Holden High School**  	| 83.79 	| 83.43 	| 85.00 	| 82.86 	|
|   **Huang High School**   	| 77.03 	| 75.91 	| 76.45 	| 77.23 	|
|  **Johnson High School**  	| 77.19 	| 76.69 	| 77.49 	| 76.86 	|
|    **Pena High School**   	| 83.63 	| 83.37 	| 84.33 	| 84.12 	|
| **Rodriguez High School** 	| 76.86 	| 76.61 	| 76.40 	| 77.69 	|
|  **Shelton High School**  	| 83.42 	| 82.92 	| 83.38 	| 83.78 	|
|   **Thomas High School**  	| 83.59 	| 83.09 	| 83.50 	| 83.50 	|
|   **Wilson High School**  	| 83.09 	| 83.72 	| 83.20 	| 83.04 	|
|   **Wright High School**  	| 83.26 	| 84.01 	| 83.84 	| 83.64 	|

## Reading Scores Per School, Per Grade Level:

|                **School** 	| **9th** 	| **10th** 	| **11th** 	| **12th** 	|
|--------------------------:	|--------:	|---------:	|---------:	|---------:	|
|   **Bailey High School**  	| 81.30   	| 80.91    	| 80.95    	| 80.91    	|
|  **Cabrera High School**  	| 83.68   	| 84.25    	| 83.79    	| 84.29    	|
|  **Figueroa High School** 	| 81.20   	| 81.41    	| 80.64    	| 81.38    	|
|    **Ford High School**   	| 80.63   	| 81.26    	| 80.40    	| 80.66    	|
|  **Griffin High School**  	| 83.37   	| 83.71    	| 84.29    	| 84.01    	|
| **Hernandez High School** 	| 80.87   	| 80.66    	| 81.40    	| 80.86    	|
|   **Holden High School**  	| 83.68   	| 83.32    	| 83.82    	| 84.70    	|
|   **Huang High School**   	| 81.29   	| 81.51    	| 81.42    	| 80.31    	|
|  **Johnson High School**  	| 81.26   	| 80.77    	| 80.62    	| 81.23    	|
|    **Pena High School**   	| 83.81   	| 83.61    	| 84.34    	| 84.59    	|
| **Rodriguez High School** 	| 80.99   	| 80.63    	| 80.86    	| 80.38    	|
|  **Shelton High School**  	| 84.12   	| 83.44    	| 84.37    	| 82.78    	|
|   **Thomas High School**  	| 83.73   	| 84.25    	| 83.59    	| 83.83    	|
|   **Wilson High School**  	| 83.94   	| 84.02    	| 83.76    	| 84.32    	|
|   **Wright High School**  	| 83.83   	| 83.81    	| 84.16    	| 84.07    	|

## Average Scores by Budget Range:

| **Budget Range** 	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|-----------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
|    **575-600**   	| 83.43              	| 83.89                 	| 93.54             	| 96.46                	| 90.27             	|
|    **600-625**   	| 83.60              	| 83.93                 	| 93.99             	| 96.54                	| 90.57             	|
|    **625-650**   	| 78.03              	| 81.42                 	| 71.11             	| 83.45                	| 59.94             	|
|    **650-675**   	| 76.96              	| 81.06                 	| 66.22             	| 81.09                	| 53.52             	|

## Grades by Student Count Ranges:

| **Student Count Ranges** 	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|-------------------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
|        **small**        	| 83.55              	| 83.85                 	| 93.53             	| 96.50                	| 90.24             	|
|       **medium**      	| 80.75              	| 82.77                 	| 83.06             	| 90.16                	| 76.01             	|
|         **large**        	| 76.99              	| 80.97                 	| 66.37             	| 80.99                	| 53.58             	|

## Grades by School Type:

|   **Type**   	| **Avg Math Score** 	| **Avg Reading Score** 	| **% Passed Math** 	| **% Passed Reading** 	| **% Passed Both** 	|
|:------------:	|-------------------:	|----------------------:	|------------------:	|---------------------:	|------------------:	|
|  **Charter** 	| 83.47              	| 83.90                 	| 93.62             	| 96.59                	| 90.43             	|
| **District** 	| 76.96              	| 80.97                 	| 66.55             	| 80.80                	| 53.67             	|