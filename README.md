# COVID-19-XrayDetection

### Content
The novel coronavirus 2019 (COVID-2019) first appeared in Wuhan city of China in December 2019. It spread rapidly all around the globe to be finally declared a global pandemic by the World Health organization on the 11th of March 2020.

Covid-19 has resulted in countless numbers of lives lost, ruining multiple businesses all over the world and disrupting the global economy.


t is critical to detect the positive cases as early as possible so as to prevent the further spread of this pandemic and to quickly treat affected patients. The need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available. 

Recent findings obtained using radiology imaging techniques suggest that such images contain salient information about the COVID-19 virus. Application of advanced artificial intelligence (AI) techniques coupled with radiological imaging can be helpful for the accurate detection of this disease, and can also be assistive to overcome the problem of a lack of specialized physicians in remote villages. [source of information: ncbi]

 

### Problem Statement
The Covid-19 spreads as easily like any other flu and the number of positive cases grows at an incredibly high exponential rate. If we do not take every necessary measure and utilize all possible diagnostic tools, it would take us a significantly longer amount of time to combat this pandemic.

### Objective
You are given X-ray images of patients. You are required to build a machine learning model that would detect if the patient is a COVID (i.e. the target value as 1) patient or Non-COVID (i.e. the target value as 0) patient.

### Evaluation Criteria
Submissions are evaluated using F1 Score.



### How do we do it? 

Once we release the data, anyone can download it, build a model, and make a submission. We give competitors a set of data (training data) with both the independent and dependent variables. 

We also release another set of data (test dataset) with just the independent variables, and we hide the dependent variable that corresponds with this set. You submit the predicted values of the dependent variable for this set and we compare it against the actual values. 

The predictions are evaluated based on the evaluation metric defined in the datathon.

![covid_19](https://user-images.githubusercontent.com/44323155/99985598-290d8280-2dd4-11eb-925d-ca2a2061d683.jpg)



### About the data

The training dataset contains X-ray and CT scan images of patients with positive Corona test and negative Corona test. 


###### Dataset Link: https://drive.google.com/file/d/1BFc2Lt2N1swO8BKRvLMEyUhLzF52RFvr/view?usp=sharing

From the above link you will be able to download a zip file named ‘covid_image_data.zip’. After you extract this zip file, you will get four files:

**train** - contains all the x-ray images of covid and non-covid patient that are to be used for training your model.  Each image has a unique name.

**Training_set_covid.csv** - this csv file contains all the image ids present in the train folder with their respective label of ‘COVID’ i.e. 1 or ‘Non-COVID’ i.e. 0

**test** - contains X-ray and CT scan images of covid and non-covid patient. For these images you are required to make predictions as ‘COVID’ i.e. 1 or ‘Non-COVID’ i.e. 0.

**Testing_set_covid.csv** - this is the order of the predictions for each image that is to be submitted on the platform. Make sure the predictions you download are with their image’s filename and in the same order as given in this file.

**sample_submission:** This is a csv file that contains the sample submission for the data sprint.


## Acknowledgment
@article{cohen2020covid,  title={COVID-19 image data collection},  author={Joseph Paul Cohen and Paul Morrison and Lan Dao},  journal={arXiv 2003.11597},  year={2020} }
