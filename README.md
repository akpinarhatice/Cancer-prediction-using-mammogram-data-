# Cancer-prediction-using-mammogram-data-
Predicting if a mass detected in a mammogram is benign or maligant ,on the basis of that we can easily tell that whether its sign of cancer or not. previously this work is done using seeing the mammogram image manually by doctor predicting whether its maligant or not but now we are using Machine learning model to learn from previous patient data and predict for new patient whether they have to worry or not.
**Predicting Cancer  mammogram data**
A mammogram is an x-ray picture of the breast. 
![enter image description here](https://s3-us-west-2.amazonaws.com/utsw-patientcare-web-production/original_images/blog_oct_19_2017_3d-mammogram-texas-insurance-2.jpg)
It can be used to check for breast cancer in women who have no signs or symptoms of the disease. It can also be used if you have a lump or other sign of breast cancer. Screening mammography is the type of mammogram that checks you when you have no symptoms.

 whether its benign or maligant
![enter image description here](https://www.researchgate.net/profile/Victor_Navarro11/publication/284165798/figure/fig1/AS:297312892014592@1447896325068/Examples-of-benign-left-and-malignant-right-masses-in-mammograms-Subsequent-biopsy.png)If you have been diagnosed with a tumor, the first step your doctor will take is to find out whether it is **malignant** or **benign**, as this will affect your treatment plan. In short, the meaning of malignant is cancerous and the meaning of benign is non-cancerous. Learn more about how either diagnosis affects your health.
*Previously doctors do this using manually seeing mammogram photo*
![enter image description here](https://einsteinperspectives.com/wp-content/uploads/2016/11/doctor-copout.jpg)
But now with help of previos patient data we can create a machine learning model to learn from it and make future prediction whether its maligant or benign
patient is having cancer or not.
**1.Data**        
data is provided by uci                          
**2. Sources:**

   (a) Original owners of database:
        Prof. Dr. Rüdiger Schulz-Wendtland
        Institute of Radiology, Gynaecological Radiology, University Erlangen-Nuremberg
        Universitätsstraße 21-23
        91054 Erlangen, Germany
        
   (b) Donor of database:
        Matthias Elter
        Fraunhofer Institute for Integrated Circuits (IIS)
        Image Processing and Medical Engineering Department (BMT) 
        Am Wolfsmantel 33
        91058 Erlangen, Germany
        matthias.elter@iis.fraunhofer.de
        (49) 9131-7767327 
        
   (c) Date received: October 2007
 
**3. Past Usage:**
    M. Elter, R. Schulz-Wendtland and T. Wittenberg (2007)
    The prediction of breast cancer biopsy outcomes using two CAD approaches that both emphasize an intelligible decision process.
    Medical Physics 34(11), pp. 4164-4172

4. Relevant Information:
    Mammography is the most effective method for breast cancer screening
    available today. However, the low positive predictive value of breast
    biopsy resulting from mammogram interpretation leads to approximately
    70% unnecessary biopsies with benign outcomes. To reduce the high
    number of unnecessary breast biopsies, several computer-aided diagnosis
    (CAD) systems have been proposed in the last years.These systems
    help physicians in their decision to perform a breast biopsy on a suspicious
    lesion seen in a mammogram or to perform a short term follow-up
    examination instead.
    This data set can be used to predict the severity (benign or malignant)
    of a mammographic mass lesion from BI-RADS attributes and the patient's age.
    It contains a BI-RADS assessment, the patient's age and three BI-RADS attributes
    together with the ground truth (the severity field) for 516 benign and
    445 malignant masses that have been identified on full field digital mammograms
    collected at the Institute of Radiology of the
    University Erlangen-Nuremberg between 2003 and 2006.
    Each instance has an associated BI-RADS assessment ranging from 1 (definitely benign)
    to 5 (highly suggestive of malignancy) assigned in a double-review process by
    physicians. Assuming that all cases with BI-RADS assessments greater or equal
    a given value (varying from 1 to 5), are malignant and the other cases benign,
    sensitivities and associated specificities can be calculated. These can be an
    indication of how well a CAD system performs compared to the radiologists.

**5**. Number of Instances: 961

**6**. Number of Attributes: 6 (1 goal field, 1 non-predictive, 4 predictive attributes)

**7**. Attribute Information:
   1. BI-RADS assessment: 1 to 5 (ordinal)  
   2. Age: patient's age in years (integer)
   3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
   4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
   5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
   6. Severity: benign=0 or malignant=1 (binominal)

8. Missing Attribute Values: Yes
    - BI-RADS assessment:    2
    - Age:                   5
    - Shape:                31
    - Margin:               48
    - Density:              76
    - Severity:              0                                                     
    *After performing all the data preparation our trained model is good to go for predicting patient cancer*                                           
    **Note:** project is in running mode to get 99.999999% accuracy
