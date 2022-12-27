# Covid-19 Patients Information System 

Since the covid virus has been present in a long period of our lives, as a database systems project, we have established a hospital system on the management and information of covid tests.

Developed in 2020.

## Table of contents
* [General info](#general-info)
* [Technologies-Tools](#technologies-tools)
* [Modules](#modules)
    -   [Patient](#patient)
    -   [Doctor](#doctor)
    -   [Examination](#examination)
    -   [Hospital](#hospital)
    -    [City](#city)
* [Setup](#setup)
* [Contact](#contact)


## General Info


In the project, there are 5 modules and tables to organize the covid informations for patients, doctors, hospitals or cities. Fifth and the last table includes the examination- covid test result depending on all the 4 modules. Project provides to filter any of the modules by module's attribitues or by other modules.  
	
![Base Page](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/base-page.png?raw=true)
	
![ER Diagram](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/er-diag.png?raw=true)
## Technologies-Tools
Project is created with:
* Java 15
* PostgreSQL - PgAdmin
* Intellij Idea

## Modules
	
### Patient
Here, in this module, you can view, filter and sort the patients  by the attribitues that you want. Also you can create, update, delete the patient informations.
![Patients-Table](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/patients-table.png?raw=true)
	![Patients-Base-Page](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/patients_base.png?raw=true)
	![Patients-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/patients.png?raw=true)
### Doctor
Here, in this module, you can view, filter and sort the doctors by the attribitues that you want. Also you can create, update, delete the doctor informations.
![Doctors-Table](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/doc-table.png?raw=true)

![Doctors-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/doctors_base.png?raw=true)
![Doctors-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/doctors.png?raw=true)
### Examination
Here, in this module, you can view, filter and sort the examinations by the attribitues that you want. Also you can create, update, delete the examination informations.
![Examination-Table](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/exam-table.png?raw=true)

![Examination-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/covid_examination.png?raw=true)

### Hospital
Here, in this module, you can view, filter and sort the hospitals by the attribitues that you want. Also you can create, update, delete the hospital informations.
![Hospital-Table](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/hospital-table.png?raw=true)

![Hospital-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/hospitals.png?raw=true)
![Hospital-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/new_hospital.png?raw=true)
### City
Here, in this module (the VIEW in sql) , you can view, filter and sort the cities by the attribitues that you want. Also you can create, update, delete the city informations.

![Doctors-Modules](https://github.com/alibariszengin/Ashamed-Patients-Information-System/blob/main/images/cities.png?raw=true)

## Setup
To run this project, open the project with your IDE and change the database connect configurations in DbConnection class. 

You can find the queries in the base path of the repo as "queries.txt". Do not forget to run these queries in your db.


## Contact

Ali Barış Zengin  -  [alibariszengin@gmail.com](mailto:alibariszengin@gmail.com)

Project Link:  [https://github.com/alibariszengin/Ashamed-Patients-Information-System](https://github.com/alibariszengin/Ashamed-Patients-Information-System)

