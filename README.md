# Neural_Network_Charity_Analysis
## Overview

To create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.<br>
Data contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns<br>
APPLICATION_TYPE—Alphabet Soup application type<br>
AFFILIATION—Affiliated sector of industry<br>
CLASSIFICATION—Government organization classification<br>
USE_CASE—Use case for funding<br>
ORGANIZATION—Organization type<br>
STATUS—Active status<br>
INCOME_AMT—Income classification<br>
SPECIAL_CONSIDERATIONS—Special consideration for application<br>
ASK_AMT—Funding amount requested<br>
IS_SUCCESSFUL—Was the money used effectively<br>

## Result
  ### Data Processing
  Target: "IS_SUCCESSFUL"
  To Remove: "EIN","NAME"
  Features: All other variables
  ### Compiling, Training, and Evaluating Model
  Attempt 1: 2 Hidden Node layer, 80 and 30 neurons, with 50 Epochs.
  
  <img width="996" alt="image" src="https://user-images.githubusercontent.com/104419959/215211398-516d67bd-98fc-40d0-8140-e93cee949381.png">

  Attempt 2: 2 Hidden Node layer, 80 and 30 neurons, with 100 Epochs.
  
  <img width="1037" alt="image" src="https://user-images.githubusercontent.com/104419959/215211533-76505358-7133-43ad-a6c8-e7a770b5335e.png">

  Attempt 3: 2 Hidden Node Layer, 100 and 40 Neurons, with 75 Epochs.
  <img width="943" alt="image" src="https://user-images.githubusercontent.com/104419959/215211617-03f591ab-af36-4eee-bee0-40278191e158.png">

  Attempt 4: 3 Hidden Node Layer, 80, 20 and 10 Neurons, with 50 Epochs.
  <img width="1081" alt="image" src="https://user-images.githubusercontent.com/104419959/215211691-37809aaa-5a3c-44d4-b64f-7dfecce0bd5a.png">

## Summary
After multiple attempts, I was unable to reach accuracy of 75%.<br> Average percentage of accuracy was 72.3%.
<img width="741" alt="image" src="https://user-images.githubusercontent.com/104419959/215211302-29619c3d-2ff4-4748-a8d9-f24bf41864e0.png">

