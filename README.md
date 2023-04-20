README.md FILE


**CASSANDRA_CRUD**
Cassandra Query Language (CQL) CRUD Operations


Cassandra Query Language (CQL) is a language that allows users to interact with the Cassandra database. It is a SQL-like language that is used to create, update, and delete data from the Cassandra database.


This README file provides a brief guide on how to perform CRUD (Create, Read, Update, Delete) operations using CQL in Cassandra.


**In the Database tables are created name clinical_trails**


CREATE TABLE  clinical_trials.trials ( 



id  PRIMARY KEY,
    name text,
    description text,
    phase text,
    start_date date,
    end_date date,
    status text,
    sponsor text,
    location text
);
In the "clinical_trails" table, we have columns for id, name, description,phase,start_date,end_date,status,sponsor,location .The primary key is set to the "id" column


.



**Create Operation**


**To create a new row in a table in Cassandra, you can use the INSERT statement.
**

INSERT INTO clinical_trials.trials (id, name, description, phase, start_date, end_date, status, sponsor, location)
VALUES (1, 'Trial 1', 'Description for Trial 1', 'Phase 1', '2023-03-01', '2023-06-01', 'In Progress', 'Sponsor 1', 'Location 1'); 


INSERT INTO clinical_trials.trials (id, name, description, phase, start_date, end_date, status, sponsor, location)
VALUES (2, 'Trial 2', 'Description for Trial 2', 'Phase 2', '2023-04-01', '2023-08-01', 'Recruiting', 'Sponsor 2', 'Location 2');


INSERT INTO clinical_trials.trials (id, name, description, phase, start_date, end_date, status, sponsor, location)
VALUES (3, 'Trial 3', 'Description for Trial 2', 'Phase 2', '2023-04-01', '2023-08-01', 'Recruiting', 'Sponsor 2', 'Location 3');


INSERT INTO clinical_trials.trials (id, name, description, phase, start_date, end_date, status, sponsor, location)
VALUES (4, 'Trial 4', 'Description for Trial 2', 'Phase 2', '2023-04-01', '2023-08-01', 'Recruiting', 'Sponsor 2', 'Location 4');


INSERT INTO clinical_trials.trials (id, name, description, phase, start_date, end_date, status, sponsor, location)
VALUES (5, 'Trial 5', 'Description for Trial 2', 'Phase 2', '2023-04-01', '2023-08-01', 'Recruiting', 'Sponsor 2', 'Location 5');




To delete a entire table ,use DROP TABLE

DROP TABLE clinical_trails;


**CLINICAL_TRAILS table with its attributes**

**id**	**name**	**DESCRIPTION	** **phase**	**start_date**	**location**	**sponsor**	**End date**	**status**
1       	nantha	  Teeth probem	    2	         25-4-2020	     erode	       agency	    2-4-2022	   In progress
2	        Arun	    checkup	          4	         6-3-2020	       namakkal	     agency	    16-4-2022	   finished
3	        DaviD    	Medicalissue	    1	         8-5-2020	       triuchy	     agency	    4-2-2022	   In progress
4	        Manoj	     skin	            3	         28-7-2020      	erode	       agency	    23-4-2022	   finished
5	        Priyanka	 stomach	        2	         18-2-2020	      karur	       agency	    15-4-2022	   In progress


**Conclusion**


This README file provided a brief guide on how to perform CRUD operations using CQL in Cassandra.


**LINK FOR GITHUB:
https://github.com/CHANZ12/NoSQL**
