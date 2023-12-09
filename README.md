# HuangZheng
This is the ENV 872 Course Group Project for Yuechen Huang and Shiqi Zheng

Our project focuses on understanding and investigating the temperature-dependent sex determination (TSD) phenomenon in the Testudines order. We are interested in determinants that influence the sex ratio of Turtle Offspring and we aim to explore questions about temperature impacts on the sex ratio of turtles and other factors that may also influence the sex ratio.

The dataset we used was downloaded from <https://github.com/calebkrueger/ROSIE/tree/main>. It is a dataset called Reptilian Offspring Sex and Incubation Environment (ROSIE) and contains over 7,000 individual measurements of offspring sex ratios in the order Testudines from 1966 to 2020. The variables we wrangled and used are shown below: 
| Used Variables      | Description                                                                            |
|:-----------------------------------|:-----------------------------------|
| Species information | Order, Family, Genus, Species                                                          |
| Spatial information | Wild sampling location, or native range of species if captive or location not provided. Provided in average latitude and longitude |
| Captivity           | Eggs from captive or/and wild individuals. 0 - wild and 1 - captive                                              |
| Time                | Time of turtle nesting/egg collection. Start date and end date are provided, in this report, we mainly use the end date as time                         |
| Temperature         | Mean of actual/recorded incubator temperature in degrees Celsius                       |
| Humidity            | Relative humidity of incubation chamber between 0 and 1                                |
| Sex ratio           | Proportion of male                                                                     |
