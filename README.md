# Mongodb_Practical
<p>Mongodb Practicals</p>
<p>Practical: 1.Creating database employee 
Create collections emp_personal_details with emp_id, emp_name, emp_address, 
emp_DOB, emp_age, emp_mobilenumber</p>

<p>Practical:2 Create another collection emp_professional_details with emp_id, emp_name, 
designation , salary , incentive, working hours</p>

<p>Practical:3 Insert 10 records in collection emp_personal_details and 
emp_professional_details 
2. Show all the employees having designation manager 
3. Show all the employees having salary 6000</p>

<p>Practical:4 Update the collection emp_personal_details , add field status and set it to retired 
where age is greater than 60. 
2. Update collection emp_professional_details, give incentive 5000 to employees 
whose working hours is greater than 45 per week 
3. Add 1000 to the salary employee whose designation is accountant </p>

<p>Practical:5 Create index on emp_id in collection emp_professional_details  
2. Create multiple index on emp_id,emp_name in collection emp_professonal 
details </p>

<p> Practical:6 1. Find sum of salaries of employees having designation clerk. 
2. Filter the employees having the designation software engineer and find the 
minimum salary.</p>

<p>Practical:7 Use unwind command and show the employees whose mobile number is stored in 
array 
2. Use skip command to skip first 3 records and display rest of records 
3. Use limit command to show only first four records of collection</p>

<p>Practical:8 Create replica set of employee database and insert records in primary node and 
display the same records in secondary nodes </p>

<p>Practical:9 Create a MongoDB collection named restaurants to store the following 
information about restaurants: 
Building number 
Street name
Zip code 
Coordinates (longitude and latitude) 
Borough 
Cuisine type 
Grades (each grade includes: date, grade (A/B/C), and score) 
</p>

<p>Practical10: 1.Write a MongoDB query to display all the documents in the collection 
restaurants 
2. Write a MongoDB query to display the fields,restaurant_id, name, borough and 
cuisine for all the documents in the collection restaurant </p>
<p>Practical:11 1.Write a MongoDB query to display the fields restaurant_id, name, borough and 
cuisine, but exclude the field _id for all the documents in the collection restaurant 
2. Write a MongoDB query to display all the restaurant which is in the borough 
Bronx</p>
<p>Practical:12 1. Write a MongoDB query to display the first 5 restaurants which are in the 
borough Bronx. 
2. Write a MongoDB query to display the next 5 restaurants after skipping first 5 
which are in the borough Bronx</p>
<p>Practical:13 1.Write a MongoDB query to find the restaurants who achieved a score more than 
90 
2.Write a MongoDB query to find the restaurantsthat achieved a score, more than 
80 but less than 100 </p>

<p>Practical:14 Write a MongoDB query to find the restaurants which do not prepare any cuisine 
of 'American ' and achieved a grade point 'A' not belonging to the 
boroughBrooklyn. The document must be displayed according to the cuisine in 
descending order </p>

<p>Practical:15 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which contain 'Wil' as first three letters for its name </p>

<p>Practical:16 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which contain 'ces' as the last three letters for its name.</p>

<p>Practical:17 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which contain 'Reg' as three letters somewhere in its name </p>

<p>Practical18: Write a MongoDB query to find the restaurants which belong to the borough 
Bronx and prepared either American or Chinese dish </p>

<p>Practical:19 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which belong to the borough Staten Island or Queens or Bronx 
or Brooklyn.</p>
<p>Practical:20 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which are not belonging to the borough Staten Island Or Queens 
or Bronxor Brooklyn. </p>
<p>Practical:21 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which achieved a score which is not more than 10</p>
<p>Practical:22 Write a MongoDB query to find the restaurant Id,name, borough and cuisine for 
those restaurants which prepared dish except 'American' and 'Chinese' or 
restaurant's name begins with letter 'Wil'</p>
<p>Practical:23 Write a MongoDB query to arrange the name of the restaurants in descending 
along with all the columns </p>
<p>Practical:24 Write a MongoDB query to arranged the name of the cuisine in ascending order 
and for that same cuisine borough should be in descending order.</p>
<p>Practical:25 Write a MongoDB query to know whether all the addresses contains the street or 
no</p>
<p>Practical:26 Write a MongoDBquery which will select all documents in the restaurants 
collection where the coord field value is Double </p>
<p>Practical:27 Write a MongoDBquery which will select the restaurant Id, name and grades for 
those restaurants which returns 0 as a remainder after dividing thescore by 7. </p>
<p>Practical:28 Write a MongoDB query to find the restaurant name, borough, longitude and 
attitude and cuisine for those restaurants which contains 'mon' as three letters 
somewhere in its name</p>
<p>Practical:29 Write a MongoDB query to use sum, avg,min max expression</p>
