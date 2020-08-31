# __Asmas__
## Student Information System 
### Windows Desktop Software (Vb.net)

This repo contains the setup file of ASMAS software. Find the source code here. https://github.com/amWRit/Asmas


Three roles: 
* Admin
* Class Teacher
* Viewer

__ADMIN__ can:
* Add/Delete/Edit School
* Add/Delete/Edit School Year
* Add/Delete/Edit User
* Add/Delete/Edit Class
* Add/Delete/Edit Student
* Assign class teacher to class
* View Results
* Print Results
* Print Character Certificate of a student
* View the student database
* Search the database
  * class, by ID/name
  * student, by ID/name
  
__Class Teacher__ can:
* Add/Delete/Edit student to his/her own class
* Edit information of the students of his/her classes
* View his/her own assigned classes
* Add/Edit/Delete Results of his/her classes
* View Results of his/her classes
* Print Results of his/her classes
* Print Character Certificate of a student
* View the student database
* Search the database
  * class, by ID/name; only his/her assigned classes are available
  * student, by ID/name
* View result analysis of all the subjects that he/she teachers

__Viewer__ can:
* Search the database
  * class, by ID/name; only his/her assigned classes are available
  * student, by ID/name

__Result features__ 
* Can be added 
  * Student wise
  * Subject wise
* Calculations can be updated later
* Rank can be updated later
* Analysis of each subject result of a specific terminal
  * Average
  * High
  * Low
  * LOCOS (Lowest Cutoff Score)
    *Students under the LOCOS can be obtained
    
__Result Printing features__
* Result can be printed
  * of a specific student
  * in Batch (start and end page numbers can be provided)
  
__Setting up New Database__

To set up a completely fresh new database, you will need to import a blank Database file. You will see a file named _"Database - blank.accdb"_ inside the original folder of the software; not in the installed path.
* Log in as Admin.
* Go to- Admin Tools > Database > Import > Select the _"Database - blank.accdb"_ file from that original folder.

_PS: This will completely renew your database. So be careful before using the Database Import/Export feature. A backup of the current database will be created nevertheless._
