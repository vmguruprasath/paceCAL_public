# paceCAL_public
paceCAL is pacing calculating utility developed in Python that would help Performance test engineers and Managers in 
pacing calculation for load modelling

 
Please find attached a simple pacing calculation utility as .exe attachment.
 
Steps to open the utility:
 
1. Download the executable to your local folder
2. Double click on the "paceCal_v1.exe" file
 
Supported Operating System: Windows
 
Steps to run the utility:
 
1. Enter the Concurrent users and
2. Choose Transactions per hour (TPH) rate or Transactions Per Second (TPS) rate as per your project requirement.
3. Click on the Submit button.
4. The pacing value in seconds and minutes will be displayed.
 
The pacing value displayed here is the sum of think times (in between the scripts) and pacing between iterations that need to be configured in our scripts to achieve the required transaction rate for the given concurrent users.
 
Kind Note: 1. Kindly click on clear to clear the existing values before attempting next iteration of calculation
           2. The utility has not been subjected to negative testing.
 
Hope this utility is helpful to the Performance Testing Community.
