# ICSA-HR
Open Source. Fork me.
A I Can See Analyser tool for Human Resource Professionals. To help in recruitment events.
Any Help is appreciated. Busy with stuff but do raise issues if any of importance.

It is a software built on :

Legacy Python - 2.7.1.4,
Computer Vision Library - OPENCV 2.x and later,
GUI library - Tkinter,
Spreadsheet Writing library - XLRD at the moment, may use other functions if they achieve the same result.
Cascades - HAAR and LBP. I prefer HAAR. Using pre-trained Classifiers for the initial tests. Final RC will have Custom Trained Classifiers.

Objectives - The software basically does the following :

1. Takes in the input of a video and then splits the file into a set of many pictures/frames per time unit we specify.
(i know this is doable in OPENCV)

2. Provides an analysis of the emotion of the person in each of the photos as : HAPPY, SAD, SURPRISED, ANGRY.

3. Writes the results per frame/picture analysed to a spreadsheet with time of the picture.
(XLRD should help me here is assumed.)

(I plan to use cascades and ML algos to label and identify and classify the person and the features and the emotions many ways come to mind VIOLA JONES, YOLO...)

4. Calculates the mean emotion. 

5. Also the most prevalent emotion. Tells the emotion if we set the time of the emotion we need.

6. Writes the Output of the Cells after the formula has been applied to calculate mean emotion and Prevalent emotion in a time period defined by the user.

7. Writes the data to a word file with a preset template. Data insertion takes place in a sequence to form a report.


Need - 

1. Create a EQ report of a person being interviewed.

2. Create a easy to use tool to help HRs do their job using AI and CV.

3. Provides a Free and Open Source tool to ease the Pain of reportage for entry level HR roles.

4. May even help in doing remote evalution of emotions in the future.

5. Create a easy to use GUI tool (Tkinter) for a lay person to use.

6. This tool though made for HRs can be used by small business owners and practically anyone hiring someone.


* if all the above are met i plan to add aa hireability score and also a text to voice option that shall read out the result to the HR.(TTS) libs will come in handy.


Any additions are appreciated. Will commit and push initial design and files, ASAP.


