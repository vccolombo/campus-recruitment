# Campus Recruitment - Data Science

## Introduction

One of the main concerns of students enrolled in all sorts of courses is whether they will find a job or not after finishing their studies.

## Data

The [dataset](https://www.kaggle.com/benroshan/factors-affecting-campus-placement) consists of 215 rows representing students that completed an MBA course at an Indian University. The columns are as follow:

- **SerialNumber**: An increasing number which represents the row id.
- **Gender**: The gender of the student (M / F).
- **LowerSecondarySchollGrade%**: The average of grades in middle school (in %).
- **LowerSecondarySchollBoard**: Schools in India are separated in "Boards", depending on their region (Central / Others).
- **HigherSecondarySchollGrade%**: The average of grades in high school (in %).
- **HigherSecondarySchollBoard**: Same as middle school board, but for high school (Central / Others).
- **HigherSecondarySchollSpecialization**: The area of specialization during high school (Commerce / Science / Arts).
- **DegreeGrade%**: The average of grades in college (in %).
- **DegreeSpecialization**: The area of specialization in college (Sci&Tech / Comm&Mgmt / Others).
- **WorkExperience**: Whether the student had previous work experience (Yes / No).
- **EmployabilityTestGrade%**: A test that was made by the university to see if a student will be employed or not.
- **MBASpecialization**: The area of specialization in the MBA (Mkt&HR / Mkt&Fin).
- **MBAGrade%**: The average of grades in the MBA (in %).
- **PlacementStatus**: Whether the student finds a job or not after completing the MBA (Placed / Not Placed).
- **Salary**: The student salary after getting a job (only available if PlacementStatus == "Placed". NaN otherwise).

There are no missing values besides salary when the person is not placed. The dataset does not seem to contain incorrect data, but it has some outliers, like a person receiving a way bigger salary than the other students.

More information can be found in the [dataset page](https://www.kaggle.com/benroshan/factors-affecting-campus-placement).

## References

https://www.kaggle.com/benroshan/factors-affecting-campus-placement
