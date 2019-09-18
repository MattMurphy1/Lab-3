# Lab-3

Executive Summary

Problem Two:
To normalize this table in 1ST NF, each cell must contain a single value.  The student’s name will need to divided into the first_name, and last_name categories. The classes column can only contain one value per cell. Two additional collumns will need to be added for Joe Smith. The values of ENG1010 and IT1090 will need to be moved to these columns. Sue Brown will also require two additional columns. The values of IT1150 and ITNT2300 will need to be seperated into individual columns. Kate Jones will require oe addtional column. The value of IT1050 will need to be seperated into an individual column. The rows must
be uniquely identified. Additional students might be added that contain the same name as one of the existing fields. The student's identification number must be added as the primary key.

To be in 2nd NF, all non-key columns must be dependent on the entire primary key. Once the student's identification number is added, the attributes of first_name, last_name, address, classes, major and major advisor all depend on the student's the student's indentity and the identification numner. This table is is 2nd NF. 

To be in 3rd NF, all non-key columns must be dependent only the primary key. All attributes are dependent on the primary key. 
This table is in third NF. 


