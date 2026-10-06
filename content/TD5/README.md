# TD5 : Programmation orientée objet

**Exercise 1 :**

We want to create a virtual farm with animals and functions that allow you to
and discover the farm.
1. Create a Farm class that must be initiated with the farm's name and that
automatically creates an empty list for storing animals.
2. Create a variable that initiates at 0 during creation and counts the number of animals.
3. Create an Animal class that initiates with the animal's name and age.
4. Add a str method to display the animal's name and age.
5. Add the add animal method to the Farm class.
6. Add the str method to the Farm class, displaying the farm name, number of animals
and each animal.
7. Add two classes, Sheep and Duck, which inherit from Animal and have a cryfunction, which returns the animal's cry, and a str function, which returns the same thing as the animal class, but with the cry of the Sheep and the Duck.

**Exercice 2 :**

We are studying data on patients admitted in 2021 to two hospitals in Bordeaux. The
"patients.csv" file contains patient data and the "visits.csv" file contains data on patient visits
(in this file, ID is the identifier of the patient concerned by the visit; in question 4, you'll see
that the visit identifier will be generated automatically).
1. Create a Hospital class taking as parameters the hospital location, a directory of its
patients, and a directory of its patients' visits. Add the functions :

- add_patient adds the patient to the directory.
-  remove_patient removes the patient from the directory.
-   add_visit adds a visit to the hospital.
-  et_patient_id which returns the patient corresponding to the given id.
-  get_visites_patient which returns a patient's visits by ID.
-   get_visite_by_date which returns visits that took place on a certain day.
-  tr of hospital should display the hospital location and number of patients.
-  len should display the number of patients in the hospital.

2. Create a Patient class taking as parameters the patient's identifier, date of birth, a list
of visits and gender. Add the functions :

- add_visit, which adds a visit to the patient.
-  str of Patient, which displays the patient's ID, date of birth and gender.Master PHDS

4. Open the "patients.csv" file in read mode and for each line create a patient and add it
to a patient directory.
5. Create a Visit class which takes as input a patient, hospital, reason for visit, date and
which has an ID. The visit ID must increase each time a Visit object is created.
6. Create a VisiteUrgente class, which is a subclass of Visites. These visits have 4
additional pieces of data for assessing the patient's situation: whether he's bleeding,
his heart rate, his blood pressure and whether he's conscious when he arrives at the
emergency room. (O for No and 1 for Yes)
7. From the "visits.csv" file, create hospitals and visits associated with patients.
Hospitals must contain patients and visits that took place only in that hospital.
8. Display the number of patients for each gender.
9. Display the number of visits for each reason for each hospital.
