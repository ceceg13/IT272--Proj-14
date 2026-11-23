PROJECT 14-1 - CREATE AN INDEXED STUDENT MASTER FILE

Files in this package
---------------------
PROJECT14_1_JDOODLE.cobc  - GnuCOBOL/JDoodle source program
stumast(1).dat             - supplied sequential input file

JDoodle setup
-------------
1. Create a COBOL project in JDoodle.
2. Paste PROJECT14_1_JDOODLE.cobc into the source editor.
3. Upload stumast(1).dat to the project without changing its name.
4. Run the program.
5. A successful run displays:
      PROJECT 14-1 COMPLETED.
        229 STUDENT RECORDS WRITTEN TO STUMASTI.
6. Download stumasti.dat from JDoodle's output/My Files area. Depending on
   JDoodle's GnuCOBOL indexed-file handler, an additional index companion
   file may also appear. Keep all generated STUMASTI files together.

File paths used by the program
------------------------------
Input:  /uploads/stumast(1).dat
Output: /myfiles/stumasti.dat

The output file is indexed with SI-STUDENT-ID as its primary record key.
Its logical student record is 104 characters and is compatible with the
student-master layout used in the later indexed-file update project.

Troubleshooting
---------------
Status 35 means the input filename or upload path does not match. Confirm
that the uploaded file is named exactly stumast(1).dat. If JDoodle renamed
it, change the first ASSIGN path in the program to match the uploaded name.
