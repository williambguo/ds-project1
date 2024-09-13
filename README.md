# **Introduction:**  
With a given dataset that contains multitudes of information about flight information. With over thirty columns of information pertaining to each model of plane, we wanted to use this information to look for the ten safest small planes.  
![Image_1](https://github.com/user-attachments/assets/c769509d-de97-4d6e-8d8b-b69f1edc893f)

![Image_2](https://github.com/user-attachments/assets/a64dc5f7-866f-46f8-b7f9-81e817e20167)



  # **Overview:**   
  In order to get an accurate analysis of what the top ten safest small planes could be, we needed to isolate columns that pertains to what needed to quantitate to determine safety and tie those values to specific planes. After cleaning the data we then need to focus on doing EDA (Exploratory Data Analysis) . The results from this then finally lead to creating filters and creating a separate data set(s) from the larger one we started with. Finally from this curated data, we begin to make visualizations that better explain our findings and final results. 

# **Business Understanding:**

To get to our findings with the given data, we need to figure out the following questions:

1\) Are there categories of the airline industry that are more accessible to expand into (I.E, large commercial planes vs. Small personal aircrafts) ? 

2\) What are the risks with those planes and how can we explain in an explicit manner these results are worth investigating further?

3\) What are the types of outside metrics or options outside the given data to consider once our findings are more finalized? 

# **Data Understanding and Analysis:**

To really extrapolate relevant information  we first need to filter out irrelevant information to fine tune the information we’ll need for our findings. So by dropping irrelevant columns it wastes less time when trying to figure out correlation between two or more categories.   

![Dataclean_1](https://github.com/user-attachments/assets/bcaf27d7-4e52-464e-9476-b92d1747d63f)

From this we can begin to start creating a filtered data set to really work off of. For example, we filtered out data to just care about ‘airplanes’ instead of other extraneous types of aircrafts. 

<br>![Dataclean_7](https://github.com/user-attachments/assets/0d98bff3-23c3-4d98-a578-f36cde6489ed)</br>


And finally we wanted to really focus on planes that were built from the 1990’s and forward 
as well as removing all planes built by amateurs 

<br>![Dataclean_5](https://github.com/user-attachments/assets/e5d24d09-df49-4233-9311-7708501f7739)</br>

<br>![Dataclean_2](https://github.com/user-attachments/assets/77320f9b-162d-42c8-bf88-7eb020ae4146)</br>


Just as well we needed to filter out the types of organizations that built the airplanes, we decided to remove any airplanes that were amateur built. Just these three filters we had set up took our data set

 **from :**   

 ![Dataclean_3](https://github.com/user-attachments/assets/da7603ea-c7c1-4115-ac04-e5c01f824a33)

**to**:   

![Dataclean_4](https://github.com/user-attachments/assets/7fc925e4-41be-4953-abca-e689190390ac)


From there we dropped all rows with missing values and also replaced rows with missing values to zero values instead (where it made sense).  This then led to taking existing metrics and creating new ones that we could work off of. To make informed metrics that took account of various indexes based on reported injuries and incidents with each specific plane.   
This left us with more columns of that that were able to make rough visualizations on to correlate accidents to years   
![Viz_1](https://github.com/user-attachments/assets/f6a553b9-dce7-455a-bbdc-67bc67d8b846)


# **Results:** 

When we finally processed all of the actionable metrics we had we first came up with a general risk index that looked at all of the planes in our second data frame: 

![Image_6](https://github.com/user-attachments/assets/825ee091-7146-4842-9977-cedb61b3b8d0)

This gave us a clear and concise look at the relationship between overall accidents and fatal incidents.  Which we coupled with a weighted scale to give a correlation between how often a specific plane model would get into an accident which becomes more apparent:   

![Viz_2](https://github.com/user-attachments/assets/1d3bac4a-9320-4566-9cf7-d91e53a3d165)

 
This allowed us to visualize the top ten most safest small aircrafts, however we wanted to compare these values with the raw values from the kinds of accidents and also how frequent these aircrafts would get into at more than 100 flights or so:   

![Viz_3](https://github.com/user-attachments/assets/9e057080-81b8-4aec-a883-df5cd77f7f9a)

  
# **Conclusions:**

When we compare the risk index values of each plane with their respective accident reports, the empirical decision on what makes a safe plane becomes slightly harder. We believe in order to come up with a discrete and less nebulous answer is to determine a Cost/Risk analysis based on how much capital it would take to operate and maintain these planes over the predicted risks
that come along with said models.  
![Image_3](https://github.com/user-attachments/assets/a5d43ce7-bfe1-4e44-9bec-b7e376a88da8)
![Image_4](https://github.com/user-attachments/assets/b0fefcd8-d0f6-4f57-8b65-18a447ebe5fb)

