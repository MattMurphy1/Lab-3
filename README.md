# Lab-3
Executive Summary
Problem one will create an EER model for the guitar database. Problem two will explain how to normalize the student's table into 1st, 2nd and 3rd NF. Problem three will create an EER model for the normalized tables. Problem four will export the script using the forward egineering option. Problem five will write a scipt that ads an index to the zip code field in the guitar databse. Problem six will create a view named customer addresses. 

Problem Two:
To normalize this table in 1ST NF, each cell must contain a single value.  The student’s name will need to divided into the first_name, and last_name categories. The classes column can only contain one value per cell. Two additional columns will need to be added for Joe Smith. The values of ENG1010 and IT1090 will need to be moved to these columns. Sue Brown will also require two additional columns. The values of IT1150 and ITNT2300 will need to be seperated into individual columns. Kate Jones will require one addtional column. The value of IT1050 will need to be seperated into an individual column. The rows must be uniquely identified. Additional students might be added that contain the same name as one of the existing fields. The student's identification number must be added as the primary key.
To be in 2nd NF, all non-key columns must be dependent on the entire primary key. The classes that a student may take, and the advisor that is assinged to a student depends on the major that is delcared. However, multiple students can declare the same major. The student identification number, major, classes and major advisor will need to be moved to a separate table. The composite primary key of the second table will be the student identification number and the major.
To be in 3rd NF, all non-key columns must be dependent only the primary key. All attributes are dependent on the primary key. This table is in third NF.

Conclusion
Normalization is a nescessary tool to reduce redundancy in SQL tables. It also makes the information easier to analyze. 

