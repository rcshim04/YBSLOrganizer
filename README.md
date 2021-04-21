# YB Student List Organizer

A simple program to organize the student list for the yearbook team. It sorts through the student list and the online student list for a specified grade and compiles all active students into a new file.

If an online student list is not specified, it will only remove inactive students.

Used for checking portrait names.

## Usage

* Drop off the student list (and online student list) into the data folder.
* In Input.txt, put the grade to organize for, the file name of the student list and (opt) the file name of the online student list.
  * Example:
  	```
	11
	MAC Students byGrade 2020_2021.csv
	Virtual School Students 2020_2021.csv
	```
* Open YBSLOrganizer.exe
* It will create a new file called Student List.csv with all active students.

**Please convert all Excel or spreadsheet files into a .csv file before using this program.

### Headers

This program relies on a specific spreadsheet format to run.

Please ensure that the headers match the ones below:

   Student List: `[Preferred Surname][Preferred First][Status][Grade][Gender][Student No.][Legal Surname][Legal First][Legal Middle]`
   
   Online List: `[Surname][First Name][Grade][Student #]`


