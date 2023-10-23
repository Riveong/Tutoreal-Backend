# Tutoreal-Backend
repository of Backend Development for Tutoreal  
Stack we are using:  
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
  
### How to Use  
> pip install -r requirements.txt  
> uvicorm main:app --reload

### Prioritized Gateway
|#|Gateway|Response|
|--|-------|--------|
|1|GET: user|Name, PhoneNumber, Gender|
|2|GET: tutor|Name, Pekerjaan, PricePerSession, Description, Speciality, SkillAndExperience, Image|
|3|GET: History Session|SessionName, TutorName, Date, Status
|4|GET: SurveyResults|TutorName, TutorOccupation, PricePerSession, Image, Precentage|
