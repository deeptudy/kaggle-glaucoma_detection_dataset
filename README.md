# kaggle-glaucoma_detection_dataset

---
Player1,2,3 = (이유성, 정서익, 김도연)

# Date Information
![image](https://github.com/deeptudy/kaggle-glaucoma_detection_dataset/assets/103613730/6b39f58b-1db8-4e4e-acb8-954d1586631b)

Total Columns : 17

Total Index of column data : 10000

total data type: Float64(3), int(2), object(12)

# Missing value
**visualization**<br>
![image](https://github.com/deeptudy/kaggle-glaucoma_detection_dataset/assets/103613730/aef7789f-1dd7-41d5-a7e7-5443a9facb24)<br>
**percent**<br>
![image](https://github.com/deeptudy/kaggle-glaucoma_detection_dataset/assets/103613730/c2f79f2e-2b1b-44a7-9a73-0d0ec43a5103)<br>

Looking at the data, you can see that there are two types(Medical History, Medication Usage) of missing values.

Missing values ​​in Medical History were filled based on yes or no in Family History. (Glaucoma in family or Glaucoma not in family)

Fill in the missing data by selecting the top 4 most used Medications Usage Medical History.

**Change the contents of Columns**
Diagnosis -> No Glaucom : 0 , Glaucoma : 1<br>
Gender -> Female : 0 , Male : 1<br>
Family History -> No : 0 , Yes : 1<br>
Visual Field Test Results -> Sensitivity, Specificity<br>
Optical Coherence Tomography (OCT) Results -> RNFL_Thickness, GCC_Thickness, Retinal_Volume, Macular_Thickness<br>
**Change the type**
Sensitivity, Specificity, RNFL_Thickness, GCC_Thickness, Retinal_Volume, Macular_Thickness: object -> float <br>
