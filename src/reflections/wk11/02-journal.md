# keys

## What is the difference between a primary key and a foreign key
Primary key uniquely identify a record in the table. Foreign key is a field in the table that is primary key in another table.

## What is an Alias?
Alias is another name for a lengthy fully qualified names or class names. This can come in handy if there is a long namespace or class name that you do not want to have to keep typing out each time.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

this is my get patients by dr id sql statement: 

SELECT *
FROM patients p
JOIN doctors d ON p.doctorId = d.id
WHERE p.id = @doctorId

afternoon challenge: I was absent due to my husband's injury. I did not complete the afternoon challenge