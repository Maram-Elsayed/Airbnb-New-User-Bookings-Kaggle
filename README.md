My solution to Kaggle Airbnb new user booking challenge : https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings

This solution got 0.82216 nDCCG score. 

Here are somes links to files that were too big to upload:

sessions.csv: https://drive.google.com/open?id=1a7tLQSLwDobdv_Omu0rhGjjd-g5HZE7z

train_scaled_2.csv: https://drive.google.com/open?id=1-FXiuMXIzh-NpdKrfqfVynxPvv7MrAHy

test_scaled_2.csv: https://drive.google.com/open?id=1-GsA_qqIB7MTulfDpQ4B2MCka7hmzpSV
                                                   
                                                   
                                                   Airbnb New User Bookings

Problem Description:

New users on Airbnb can book a place to stay in 34,000+ cities across 190+ countries. By accurately predicting where a new user will book their first travel experience, Airbnb can share more personalized content with their community, decrease the average time to first booking, and better forecast demand.

There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. Please note that 'NDF' is different from 'other' because 'other' means there was a booking, but is to a country not included in the list, while 'NDF' means there wasn't a booking.

Data Description:

test_users.csv - the test set of users
train_users.csv - the trainig set of users (id, date_account_created, timestamp_first_active, date_first_booking, gender, age, signup_method, signup_flow, language, affiliate_channel,affiliate_provider, first_affiliate_tracked, first_device_type ,first_browser
country_destination)
sessions.csv - web sessions log for users (user_id, action, action_type, action_detail, device_type, secs_elapsed)
countries.csv - summary statistics of destination countries in this dataset and their locations
age_gender_bkts.csv - summary statistics of users' age group, gender, country of destination
sample_submission.csv - correct format for submitting your predictions

Notebooks Description:

- Data_Exploration: Contains observations about the data
- Preprocessing: Has all needed preprocessing of the data
- Modeling: Reads the file created in the Preprocessing nodebook and models the data using Decision Tree and KNN

Models Used: 
- Descision Tree
- KNN

