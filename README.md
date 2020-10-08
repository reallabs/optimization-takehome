# optimization-takehome
JetFuel Takehome - for ML/AI Optimization candidates!

This is a optimization exercise that will give you the chance to see the types of problems we're working on here at JetFuel!

In particular, we're going to be predicting the click-through rates on ads. We've collected a training set of 1M rows of existing data, and a test set of 100k rows. You can access the data by unziping the archive 'data.zip'

Your task is to train an optimization model the predict the whether or not an ad will be clicked on or not.

In both files, the data is in the following format:

id      -- ad identifier\
click   -- 0/1 for non-click/click\
hour    -- format is YYMMDDHH, so 14091123 means 23:00 on Sept. 11, 2014 UTC.\
C1      -- anonymized categorical variable\
banner_pos\
site_id\
site_domain\
site_category\
app_id\
app_domain\
app_category\
device_id\
device_ip\
device_model\
device_type\
device_conn_type\
C14-C21  -- anonymized categorical variables\

Feel free to include multiple models in your submission. We'd like to see your full process, so please include models you trained that didn't work out!

## Getting started

Download the 

```
cd optimization-takehome/
unzip data.zip
open predict.py
```
