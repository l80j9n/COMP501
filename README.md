java c
COMP501 – COMPUTING TECHNOLOGY IN SOCIETY
Semester 2, 2024
Assignment 1: ICT Fundamentals
Total Marks: 100      Contribution to the final mark: 40%
Due: 6:00 pm, Friday, 23rd   August 2024
Assignment AimThe assignment has 4 parts:1.   It aims to give students an understanding of how computer systems represent real-life data such as positive numbers, negative numbers, floating point numbers, text, and at the lowest level seen by the programmer, namely binary numbers.2.   It prepares students with the ability to install multiple operating systems using VirtualBox (https://www.virtualbox.org/) and comparatively evaluate the Linux/UNIX   Operating Systems (OS). This assignment also prepares students to understand the basic concepts covering Linux/UNIX file systems, commands, and working environments.3.   It helps students understand the basic idea of contemporary Machine Learning and Deep Learning   using Google Colab (https://colab.research.google.com/).4.   It aims to have students demonstrate an awareness of enterprise information systems, their application in the business environment, and modelling techniques   for systems requirements:a.   It prepares students with the ability to analyse business cases and document the purpose, objectives, data requirements, data flows, input documents and output documents of common business functions and processes expressed in a range of information systems.
Submission Instructions and Academic Integrity
Submission Instructions1.   The assignment must be submitted on CANVAS.2.   Submit a zip file containing all your assignment work:a.   A .docx or .pdf file of your assignment.b.   A folder containing your images.
Compress these to “LAST NAME_Student ID.zip” and submit the zip file only.
Miscellaneous requirements:·   The assignment will not be marked if:o   It contains any form. of malware (e.g., computer virus)o   Not submitted in correct file format·   Keep a backup copy of your assignments to be:o   uploaded to “Turnitin” anti-plagiarism service – if requested.o   submitted as a hard copy – if requested.
Part One: Conversions between Number Systems (25 marks):Note: Remember to show all your workings where possiblePlease fill your ID number in the box here:
   
   
   
   
   
   
   
      ID =Consider A =   the last 2 non-zero digits of your AUT ID number:For example:·   If your ID is 123286 then A = 86.·   If your ID is 123206 then A = 26.A = 
Question 1: Converting Between Number Bases (4 marks) Perform. the following conversions between different number-based systems (3 marks each):Assume the number A is a decimal number (base 10):1.   Convert A10   (from Decimal) to Binary à   call the answer A22.   Convert A10   (from Decimal) to Hexadecimal à   call the answer A16
Question 2: Unsigned Arithmetic Operations (4 marks)Carry out the operations, assume that the numbers are unsigned and unlimited bits to represent:a)   Base 2: A2   + 101010012b)   Base 16: A16   + A716
Question 3: 2’s Complement Conversion (5 marks)
Assume that numbers are represented as signed, 8-bit 2’s complement representation.
If A =   86   then B10   = -86   (Replace with the last 2 non-zero digits of your ID) to get:
B10   =
Work out the following question:Convert B10   to 8-bit 2’s complement Binary; give the answer in 8 bits binary number à   call the answer C2(*) note that the number is negative, so the answer will start with ‘1’.
C2 =

Question 4: 2’s Complement Operations (8 marks)
Assume that you have the number C2   found in Question 3, represented as signed, 8-bit 2’s complement representation.
Carry out the following operations with signed 8-bit 2-s complement binary number   C2   found in Question 3. Indicate whether or not overflow occurs.a)   A2 + C2b)   C2      + 0100 1101
Question 5: ASCII Characters (4 marks)The Appendix gives a table for 7-bit ASCII. Using this table, we can work out the hexadecimal value corresponding to the encoding of this ASCII string “ABBA” (assume each 7-bit code occupies the space of an 8-bit byte with the MSB=0) as: ABBA   = 4142424116Using the Ascii table, find the hexadecimal and Binary values corresponding to your full name   (note that there are spaces in the string your full name). Answer the following:a)   Your full name:Your full name in Hexadecimal (base 16):(2 marks)b)   How many bits (not bytes) are used (do not count the end of string byte) 	(2 marks).
Part Two: Linux Operating System (25 marks):
Question 1: Setting up one Linux operating system 				(5 marks)Take screenshots during installation and when completed. Include screenshots in your          assignment.
Note to Apple Mac Users:   You will have to perform. this section in the lab.
1.       Download and install Virtual box if it isn’t already installed   on your machine.    
   A tutorial on VirtualBox can be found at:
https://www.youtube.com/watch?v=sB_5fqiysi4.
Remember   to submit   at least 2 screenshots   of installing Virtual box.2.   Download and install a Linux Operating System.
Obtain a copy of a mandatory Linux   distribution such as Puppy-5.0. Download Puppy from AUT here: https://cv.aut.ac.nz/files/comp501/lucid-puppy-5.00.isoOR
You can download any ISO or VDI files from the Internet at:    http://linuxlookup.com/linux_iso   or
http://virtualboxes.org/images   or   
Puppy Linux | VirtualBoxes - Free VirtualBoxreg; Images).
Once you download a copy of the ISO file, you can install it on Virtual Box.
Remember   to submit   at least 2 screenshots   of installing Linux.
Question 2: Manipulate directory structures in Linux (20 marks – 2 marks each)
Note to Apple Mac Users:   You can use Terminal to complete this question.
You will use the CLI (command-line interface) and provide:a.   The text or screenshots of command(s) that you type   to perform. a task.b.   The text or screenshots of any console output   from those commands (the output from a directory listing, for example).c.   Make sure that you include ALL the commands you use to do a task. This includes any commands you have to type to move to a specific directory. Make sure your pasted texts   or screenshots   are clear enough to show where you are or have moved to.
Use any OS that you set up in Question 1 (Puppy is recommended).

Replace XXX   below with your first name. If your first name is John, XXX = John.
Assume you have started in your home   directory.1.   Perform. a command that displays the absolute path of your home   directory   (your current location). Create   a new directory inside your home directory and name it XXX.2.   Now navigate   to the XXX   directory and create directory   ASSIGNMENT   and change your current working directory to ASSIGNMENT.3.   Create   three new subdirectories called XXXDirA, XXXDirB, and   XXXDirC   in ASSIGNMENT   directory.4.   Create   a new file called “MyInfo.txt”   using the touch   command and insert   three lines into the file (you may use echo   command and >>   command).a.   The first line should contain your name   and ID   number.b.   The second line should be the name   of your favourite movie.c.   The third line should be the first   sentence   of your favourite song.And display the contents of the file “MyInfo.txt”   to the standard output screen (you may use cat   command).5.   Display   the number   of words   in the file “MyInfo.txt” (you may use wc   command).6.   Copy   the file “MyInfo.txt”   to directory “XXXDirA”   and rename it to “MyInfoCopy.txt”.Make another copy of “MyInfoCopy.txt” and name it “MyInfoCopy2.txt”   (also store in the same directory “XXXDirA”).Then, display the contents of the directory “XXXDirA” using the long format.7.   Change the current working directory to ASSIGNMENT   if you are not there already. Create   10 new files (in directory ASSIGNMENT) named as follows:a.   FICTION.bakb.   unix.dakc.   thistest.bakd.   Zumbology.bake.   more.wootf.   doodah.filg.   Thiscourse.dath.   Test-1.txti.   File-1.batj.   Assignment1.fileAnd display   a listing of all the files and directories in long format in the current working directory ASSIGNMENT.8.   Display   a listing of all the files in the current working directory starting with ‘T’ and ending with ‘t’   using one command, e.g. Test-1.txt.9.   Move   all files containing letter ‘t’   to the directory XXXDirC using one command.10.   Display   a listing of the contents of the current directory ASSIGNMENT. All files with names that contain letter ‘t’ should now be gone.
Note:   Ensure your screenshots are clear and neat; Also look through your work in this section and resize screenshots such that question and answer are on the same page. 
Part Three: Machine Learning and Deep Learning (代 写COMP501 – COMPUTING TECHNOLOGY IN SOCIETY Semester 2, 2024 Assignment 1Python
代做程序编程语言25 marks)
This part of the assignment will help you to understand the basic idea of Machine Learning and Deep Learning using Google Colab (https://colab.research.google.com/   ). You will experiment with running a YOLO Python file on Google Colab and evaluate the results of your experiment.
Here you will test a fast version of an available object detection system - YOLO (https://pjreddie.com/darknet/yolo/). You will submit photos (taken by yourself) to YOLO; YOLO will try to identify the objects in the photos and will tag the objects and produce accuracy percentages of the detection/prediction. You will analyse the results to conclude if the tool is good enough for your task.
In the following section, we provide an overview of the process, followed by the questions you need to work through.
An overview – Using YOLO with Google Colab1)   Download the attached file: Assignment_1.ipynb   from the Assessment page.2)   Open Google Colab: https://colab.research.google.com/   and login (using a gmail account).   3)   Click File >> Upload Note Book to upload the .ipynb   file   4)   You will see only two cells of code. Click Run cell   (see figure below) to run each cell. You will   need to run the first cell once, and the last cell many times to finish the assignment):·   1st   cell: where you can get the Yolo repo, pre-trained weights and set up the python environment (you only need to run this cell once)·   2nd   cell: where you upload the necessary photos/images (.jpg) from your local drive to achieve prediction with YOLO      5)   When you run cell 2, the program waits for you to upload a file. Click on Choose a file   and select a file from your dataset of photos.6)   YOLO will then try to identify the objects in the photo and will give you the prediction results and percentage of accuracy of the prediction.
The output could be something like this:test.jpg: Predicted in 18.271086 seconds.
truck: 92%
truck: 75%
truck: 68%
car: 97%
car: 96%
car: 87%
car: 78%
car: 65%
car: 59%
car: 59%
car: 50%
Prediction is done in 25.13233256340027 seconds.
   
And here, there are 11 cars/trucks successfully detected in the image.
Question 1:   Collect dataset / photos (10 marks)·   Take at least 10 photos that include animals, people or other objects. Use pictures that have a mix of objects. You may use your cell phone to take the pictures or find them on the internet.·   Save all the pictures to a folder called Images.·   You may wish to resize the images so that each is 500 KB or less in size.
Question 2: Test the prediction performance of YOLO object detection system using your images as the inputs (10 marks)·   Start by running the first cell to set up the environment (you only need to run it once).
·   Run the second cell and click “Choose Files” to upload a jpg   image. 
·   Next you will first see the weights being downloaded and then the object detection system will search for all objects in the image and return output with bounding boxes and annotations of detected objects   as in the following image:   ·   You will need to report on three things   for each image from your experimentation:i.   how many object types (cars/animals/people) you see on the original image (left), (ignore very tiny ones),ii.   how many object types (cars/animals/people) YOLO recognized in the image on the right,iii.   the accuracy in percentage between the two (e.g. 0% - if none of the animals/people/objects is identified, 50% - if there are 10 animals/people/objects, but only 5 animals/people/objects are identified in bounding boxes, 100% - if all are identified.·   Repeat running the second cell to upload all your photos one by one and save all the prediction results.·   Copy and paste   the original photos (left column) and the predicted photos (right column) in Table 1 below. Replace the images below with your images. Also collect the processing time, and the accuracy, e.g. 2/2 = 100% for each photo. 		(1 mark each photo).
Table 1: Experiment Results
Original images (Replace with yours)
AI detected images (Replace with yours)
   
   
Processing Time:
Accuracy:
Your 2nd   original image here
Replace with your AI detected image here
Processing Time:
Accuracy:
   
   
   
   
   
   
   
   
   
   
   
   
   
   

Question 3: Evaluation (5 marks)
Analyse the prediction results and write your evaluation summary. Please summarise the prediction accuracies by completing Table 2 (10 marks). Feel free to edit the Object Types column and add the objects detected in your photos (e.g., you may have dogs in your photos).
Table 2: EvaluationObject typesTotal number appeared in all imagesTotal number accurately detected in all imagesAverage accuracy(%)Cars000Persons000   000                           000Total000
Part Four: Analyse a Business Case and document using Modelling Techniques        (25 marks)This part of the assignment presents the case study for this assignment. Please read the Rodney Gas Billing System case study below carefully before attempting the Questions that follow.    Students may ask for additional clarification of the case study or assignment on the discussion board on Canvas.
The Process Modelling Workbook   (see footnote) will be used as a resource for this assignment.
Tools  TemplatesFor this assignment, here are some options for the creating the diagrams:•   You may type in your answers,•   You may also use a drawing program to draw the Data Flow Diagrams and paste them into the assignment; drawing programs such as (i) Visio or (ii) Visual-paradigm with the Gane-Sarson modelling templates are an option you could use.Here is the link for Visual-paradigm that may be helpful:Gane Sarson Diagram | Visual Paradigm Online (visual-paradigm.com)•	Neatly handwritten diagrams with legible text will also be acceptable.NOTE:   The symbols in Visio or the symbols in the online Visual-paradigm tool, which are less explicit about naming and duplicates than those used in ‘The Process Modelling Workbook’, are acceptable.      
Case Study - Rodney Gas Billing   SystemRodney has just begun to provide gas to a limited number of customers. It is expected that   the   number   of   customers   will   increase   as   further   gas   pipes   are   installed.   Currently the   billing   is   done   manually,   but   it   is   planned   to   computerise   the   system   in   anticipation of increased volumes of users. You have been requested to investigate the system and prepare a system   proposal.
This is what you have found out from your information gathering:The meter reader visits the gas customers every six weeks in order to read their gas meter. When all readings have been logged for the period, the meter reader brings   the   log   into   head   office   where   the   accounts   clerk   copies   the   readings   into   a “Customer Gas Meter Readings” file which contains, for each customer, details   of their previous   readings.To   produce   the   bills   for   the   customers,   the   accounts   clerk   subtracts   the   customer’s previous meter reading from their current reading, in order to find the total volume   of   gas   used   for   the   period.   This   is   multiplied   by   the   gas   charge   rate   which   the clerk finds in a “Gas Charge Rates” file. If this is the first bill for the customer,    a charge for installation may be added, and sometimes there are maintenance charges. These extra charges are supplied by the Maintenance Department. The gas   charge   rates   are   set   annually   by   management.   All   charge   amounts   are   added to   any   previous   amounts   owed   which   are   found   for   the   customer   in   the   “Outstanding Bills” file. The current bill is posted to the   customer.Customers post their payments to the Rodney offices. The payments are banked, and a “List of Deposits” is returned by the bank. This list is compared to the “Outstanding Bills” and paid bills are placed in the “Paid Invoices” file. Partial payments are recorded on the matching bill which remains in the “Outstanding Bills” file.Refer to this Case Study and answer the questions on the following pages.   

Case Study QuestionsFor the Rodney Gas Billing System given on previous page:1.   Produce a System outline (refer to page   2 of Litchfield(2017))		(10 Marks)
System OutlineTitleSystemDocumentNameSheetInputProcessesFiles (Datastores)OutputsExternal EntitiesAuthorDateFigure 1.1: Rodney Gas Billing System Outline.2.   Produce a Context Diagram.							(5 Marks)3.   Produce a Top Level Dataflow   Diagram.						(10 Marks)
   
   
   
   



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
