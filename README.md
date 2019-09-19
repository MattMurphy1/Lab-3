# Lab-3

Executive Summary

Problem Two:
To normalize this table in 1ST NF, each cell must contain a single value.  The student’s name will need to divided into the first_name, and last_name categories. The classes column can only contain one value per cell. Two additional collumns will need to be added for Joe Smith. The values of ENG1010 and IT1090 will need to be moved to these columns. Sue Brown will also require two additional columns. The values of IT1150 and ITNT2300 will need to be seperated into individual columns. Kate Jones will require oe addtional column. The value of IT1050 will need to be seperated into an individual column. The rows must
be uniquely identified. Additional students might be added that contain the same name as one of the existing fields. The student's identification number must be added as the primary key.

To be in 2nd NF, all non-key columns must be dependent on the entire primary key. The classes that a student may take, and the advisor that is assinged to a student depends on both the major that is delcared and the student identification number. The columns of major, classes and major advisor will need to be moved to a separate table. The primary key of the second table will be the 

To be in 3rd NF, all non-key columns must be dependent only the primary key. All attributes are dependent on the primary key. 
This table is in third NF. 


