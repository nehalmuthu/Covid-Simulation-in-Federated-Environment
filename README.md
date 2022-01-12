# Covid-Simulation-in-Federated-Environment

The draft of the paper can be found under Paperfolder in the repo. [https://github.com/nehalmuthu/Covid-Simulation-in-Federated-Environment/blob/master/Paper/draft.pdf](here)

## Abstract 
The prediction of infection rate of COVID-19 disease is worthwhile if the mobility of patients in different regions is taken into account. Also,due to the patients’ privacy concerns, the data is still scarce. To address
these issues, we propose a federated multitask learning (FMTL) to predict the number of state wise COVID-19 infected people in various
locations of USA based on mobility and using a SEIR epidemic model.
To find a suitable control threshold for infection rate, the preventive
measures like vaccination, social distance and lock down are playing a
vital role. Using SEIR model with an additional constraint to check
the availability of beds, we can ensure that the beds are available in
case of need. We have used the real time mobility data sets in various states of USA during the years 2020 and 2021. We have chosen
five states for the study and we observe that there exists correlation
among the number of COVID-19 infected cases even though the rate of
spread in each case is different. We have considered each US state as
node in federated learning environment and a linear regression model
is built at each and every node. Our experimental results show that
the mean square error for the actual and prediction of COVID-19 cases
is low for Wiscosin state and high for Virginia state. Based on SEIR
simulation model , we conclude that it will take at least 400 days to
reach extinction when there is no proper vaccination or social distance.