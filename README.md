# New York City Taxi Trip Duration
<img width="1900" height="400" alt="image" src="https://github.com/user-attachments/assets/b8b71677-0410-4f4c-98ec-2e1976f7f083" />

# Description
In this competition, Kaggle is challenging you to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

Longtime Kagglers will recognize that this competition objective is similar to the ECML/PKDD trip time challenge we hosted in 2015. But, this challenge comes with a twist. Instead of awarding prizes to the top finishers on the leaderboard, this playground competition was created to reward collaboration and collective learning.

We are encouraging you (with cash prizes!) to publish additional training data that other participants can use for their predictions. We also have designated bi-weekly and final prizes to reward authors of kernels that are particularly insightful or valuable to the community.

# Evaluation
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as:
<img width="258" height="62" alt="rmsle" src="https://github.com/user-attachments/assets/c4aef9d8-6410-4b57-b8b5-7e4542d16574" />

Where:
\\(\epsilon\\) is the RMSLE value (score)
\\(n\\) is the total number of observations in the (public/private) data set,
\\(p_i\\) is your prediction of trip duration, and
\\(a_i\\) is the actual trip duration for \\(i\\).
\\(\log(x)\\) is the natural logarithm of \\(x\\)

# Submission File
For every row in the dataset, submission files should contain two columns: id and trip_duration.  The id corresponds to the column of that id in the test.csv. The file should contain a header and have the following format:
<img width="451" height="107" alt="submission-file" src="https://github.com/user-attachments/assets/b17e9092-d53b-406a-b00f-28050880acd2" />

