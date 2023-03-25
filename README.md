# Module-5-Challenge

## Pymaceuticals Inc.

As the senior data analyst at Pymaceuticals Inc you have been tasked with reviewing the data from the most recent animal study beta testing new drug regimens to combat skin cancer.I do not agree with animal testing personally, but this is a ficticious assignment so have fun with it.

During this study we want to compare performances of all drug regimens while paying close attention to the regimen of interest, Capomulin.

We will receive all data from our research team to compile an analysis with visuals to present to the executive team.

--------------------------------------------------------------------------

-Before we get to the Charts and graphs we can see from the Tumor Volume Mean and Standard deviatian that Capomulin and Ramicane have had the most successful trials.


                        Tumor Volume (mm3)
                    mean	median	var	std	sem
Drug Regimen					
Capomulin	40.675741	41.557809	24.947764	4.994774	0.329346
Ceftamin	52.591172	51.776157	39.290177	6.268188	0.469821
Infubinol	52.884795	51.820584	43.128684	6.567243	0.492236
Ketapril	55.235638	53.698743	68.553577	8.279709	0.603860
Naftisol	54.331565	52.509285	66.173479	8.134708	0.596466
Placebo	    54.033581	52.288934	61.168083	7.821003	0.581331
Propriva	52.320930	50.446266	43.852013	6.622085	0.544332
Ramicane	40.216745	40.673236	23.486704	4.846308	0.320955
Stelasyn	54.233149	52.431737	59.450562	7.710419	0.573111
Zoniferol	53.236507	51.818479	48.533355	6.966589	0.516398


---------------------------------------------------------------------------

- From the Bar charts we can see that Capomulin and Ramicane were tested on the majority of the mice, which begins to validate our data for our previous statement.

image.png

---------------------------------------------------------------------------

- From the Pie chart we can determine that the gender was fairly close to being balanced with 51% male mice and 49% female mice. However, this does not give us a sound reference that all drug regimens were tested evenly across male and female mice.

image.png

---------------------------------------------------------------------------

- From the Box Plot and the previous analysis statements we can determine that Capomulin and Ramicane had the higher success rates with the lowest final tumor volume averages. 

image.png

---------------------------------------------------------------------------

- When we randomly selected Mouse L509 we can see the effect of Capomulin with a 7.8% Tumor decrease over the course of 45 days. 

image.png

---------------------------------------------------------------------------

- We were able to find a positive correlation between the mouse weight and the average tumor volume. This tells us that when the weight of the mouse increases, our tumor size increases as well

- Our Linear regression model shows us that our dependant variable (Tumor Volume) increases as our independant variable (Weight (g)) increases. From the positive slope this gives us a way to predict and track larger subjects to test Capomulin. 
 
image.png