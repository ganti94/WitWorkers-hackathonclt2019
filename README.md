# WitWorkers-hackathonclt2019

A data-centric approach to identify key factors affecting the gaps in health care acess in Charlotte

## What it does?

Our project identifies the economic factors affecting the people in various areas of Charlotte. It makes an area-wise(using zip code) analysis of these economic factors and predicts the prime factors among those factors which made the people not use the services provided by Medlink. It can be helpful for the organization to carefully look for these factors in an area and thus can create better awareness to the people in those areas about Medlink's services.

We developed two predictive models which predict the number of people in a particular area who potentially should be using the Medlink services in future when provided the economic factors in that area. These models serve the system by predicting the actual number of patients who could be visited every week/month that can be crosschecked with the actual patients visited that week/month to fill up the gap.

We considered some important economic factors that we assumed to be crucial for the lives of people. But, we developed our model in such a way that it can be scaled up to analyze other economic or social or any potential factors that can be causing this problem. 

## How we built it?

We focussed more on extracting the crucial data from multiple sources of data provided. We then processed the data and prepared our dataset, which conveys the economic factors affecting people in particular areas of Charlotte and also the number of people using the services of Medlink from those areas.

For our first model, we used Random Forest Regressor to predict the potential number of people that can be visiting the health care centers. This model also explains the most critical features that are affecting the number of people using health care services. For our second model, we developed a predictive model, leveraging our knowledge of deep learning, to predict the same outcome as our previous model.

We used Python as our primary coding language with libraries like numpy, pandas and sklearn. Also, we designed our neural network with Tensorflow library. We used Tableau, matplotlib for visualizing our analysis.

## Files
- WitWorkers-Data-Processing : This jupyter notebook has the code for pre-preocessing the data from various data sources
- WitWorkers-Random-Forest-Model : This his jupyter notebook has the code for the random forest regression model
- WitWorkers-Tensor-Flow-Model : This his jupyter notebook has the code for the Deep learning regression model
- images: Various plots showing our analysis. 


Note: 'actual_num' is the number of people attended to avail the health services from that particular zipcode.
