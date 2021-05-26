# Week 11 | Day 2 Daily Journal

Afternoon Project: contractor/jobs API: https://github.com/MichaelaBickish/contractor

Read Dotnet WebAPI's > Relationships, and answer the following questions

## *What is the difference between a primary key and a foreign key*
Primary key is the unique identifier i.e. the id of that thing- not repeated. A foreign key is a unique identifier of something else being referenced- this is how be build relationships in sql.

## *What is an Alias?*
A shortened version of our table names, kind of like a variable, that can be used in place of writing the full table name to condense the code.

## *Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:*

SELECT
d.name as doctorName,
p.*,
dp.id as doctorsPatientId,
dp.doctorId as doctorId,
dp.patientId as patientId
FROM
doctors_patients dp
JOIN patients p on p.id = dp.patientId
JOIN doctors d on d.id = dp.doctorId
WHERE
dp.doctorId = 1

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

CREATE TABLE doctors_patients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)