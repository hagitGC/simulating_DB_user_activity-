# simulating_DB_user_activity-
This project contains a simulator of database users activity. 

Each time frame is produced by sampling a risk for each user. The risk is generated from his Gamma distribution. 
We forced trends in the user’s risk activity using exponential smoothing. 
Each time-framesample is smoothed with the previous time-frame.
