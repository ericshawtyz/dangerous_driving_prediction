# Safety
### Based on telematics data, how might we detect if the driver is driving dangerously?
This is a data science assignment where you are expected to create a data model from a given training dataset.

# Problem Statement
Given the telematics data for each trip and the label if the trip is tagged as dangerous driving, derive a model that can detect dangerous driving trips.

# Submission Deadline
Please submit the final repository including documentation by or before 17 June 2019, 6.00pm (SGT).

# Dataset
The given dataset contains telematics data during trips (bookingID). Each trip will be assigned with label 1 or 0 in a separate label file to indicate dangerous driving. Pls take note that dangerous drivings are labelled per trip, while each trip could contain thousands of telematics data points. participants are supposed to create the features based on the telematics data before training models.

Field         | Description
------------- | -------------
bookingID     | trip id
Accuracy      | accuracy inferred by GPS in meters
Bearing       | GPS bearing in degree
acceleration_x| accelerometer reading at x axis (m/s2)
acceleration_y| accelerometer reading at y axis (m/s2)
acceleration_z| accelerometer reading at z axis (m/s2)
gyro_x        | gyroscope reading in x axis (rad/s)
gyro_y        | gyroscope reading in y axis (rad/s)
gyro_z        | gyroscope reading in z axis (rad/s)
second        | time of the record by number of seconds
Speed         | speed measured by GPS in m/s

# You will be judged on the following criteria:
### Code Quality
Code Quality, also known as Software Quality, is generally defined in two ways:
* How well does the code conform to the functional specifications and requirements 
of a project.
* Structural quality, which relates to the maintainability and robustness of the code.

### Feature Engineering
Feature Engineering also referred to as pre-processing, refers to the process of selecting and transforming variables when creating a data model for a given problem statement. While you will be given a general dataset which relates to the problem statement, you need to create “features” that make the models and algorithms work as intended.

Note that your code should be able to automatically create your desired features, that can be used in the evaluation of the Hold-out test set.

### Creativity in Problem-solving
Creativity speaks volumes about your capability to make sense of given data, derive tangible results relevant to the business needs of an organization and present the findings. All this, while keeping in mind the problem statements.

### Model Performance
Model performance determines how a model represents the data and how well the chosen model will work. In this challenge, we will be performing a Hold-out model evaluation. For this problem, you are given a training data set, and our evaluators will have a test data set (not seen by the model). This test dataset will assess the likely future performance of the model.

Model will be evaluated based on the AUC-ROC curve. The model produces the highest area on test dataset is preferred.

# Qualification Criteria
* Submit the correct link to your repository
* Make sure your repository includes the complete codebase (all the commits are done, documentation, complete, etc)
* Solve only one of the challenges mentioned on the website
* Do not plagiarise the code. That will be grounds for instant disqualification
* The link to your repository must be publicly accessibly from the time of submission.

# Submission Guidelines
You can submit the code (either as a codebase or a Jupyter notebook) by uploading it to a public Github or similar repository. The instructions to submit the repository link will be sent to you via email once you accept the challenge on https://www.aiforsea.com/

### For more information, visit https://www.aiforsea.com/safety
