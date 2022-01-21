# School_District_Analysis

#Link to repository with work: https://github.com/zmbolke/School_District_Analysis 

#Purpose
The pourpose of this project is to upload and analyze testing data for a school district with 15 schools. The analysis takes into account certain criteria such as type of school, number of students, school budget, and budget per student. The data is then analysed using coding tools such as Pandas, Numpy, and Jupyter notebook. In the challenge, dishonest test reporting is suspected for the 9th graders at Thomas High School so this data is removed from the analysis below and compared to the original analysis.  

#Analysis
The data analysed herein is based on school and student csv files in the resources folder of the lined repository. An analysis was performed of the entire school district and presented below.  

![image](https://user-images.githubusercontent.com/95301484/150464427-5058a347-39ee-4ac4-a71b-9e7bb0de618f.png)
Then an analysis was performed on an individual school basis and can be seen below.

![per_school_summary ](https://user-images.githubusercontent.com/95301484/150464805-bcde9807-f251-4a5d-b3e2-ae3613041dac.png)
As previously noted, the test results for Thomas High School's 9th graders were are in question so the results were removed from the analysis. This analysis was repeated and presented below.  

![per_school_summary -9THS](https://user-images.githubusercontent.com/95301484/150464955-bb5eea0d-df1b-48fb-9b95-e0b4551229ee.png)

As shown in the tables, the % passing went from 66.9% to 93.2% for math and 69.7% to 97.0% for reading, while the overall passing percentage went from 65.1% to 90.6% for Thomas High School.
This placed Thomas High School in the top 5 school as shown below. 

![Top Schools -9THS](https://user-images.githubusercontent.com/95301484/150465245-59f49ae9-e9f0-4f2e-b241-1b0a3b84fc0d.png)

The bottom 5 schools are also shown

![Bottom Schools -9THS](https://user-images.githubusercontent.com/95301484/150465269-35589aa8-28f4-470e-918c-042a1818836d.png)

Then an analysis was performed by school by grade for both raw math and reading scores. The results are as follows: 

![Math Score by grade -9THS](https://user-images.githubusercontent.com/95301484/150465486-8a7084b5-044f-4678-b931-cac9f2db6b25.png)
![reading score by grade -9THS](https://user-images.githubusercontent.com/95301484/150465499-81fdc9a8-50d0-45f5-944e-2047948a1fd9.png)

As shown in the figures above the 9th grade THomas High School scores say NaN sionce they were canceled out. 
The following three images show average scores for math and reading, as well as percent passing math, reading, and overall based on budget per student, school size and school type. 

![score by spending -9THS](https://user-images.githubusercontent.com/95301484/150465668-a767727d-b173-47f9-8a37-d2a40218de96.png)
![scores by size -9THS](https://user-images.githubusercontent.com/95301484/150465670-543ea6a4-dea4-4ca4-8d82-1ddbf020a95d.png)
![scores by type -9ths](https://user-images.githubusercontent.com/95301484/150465675-a0ea7e3b-a6dd-46c6-a052-20f37ca9fcef.png)

It appears that the lowest spending schools had the highest test results. 
Results were close between the medium and small size schools. 
Charter schools performed better across all categories than district schools. 

#Summary


