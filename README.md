A.	Setting Up / Running the App
1.	Download the Repo.

2.	Unzip the file then open the folder and the following files should be shown.

3.	From the File Explorer Window, click the address bar.
 
4.	Type “cmd” in the keyboard and press enter.
 
5.	(One time only) If this is the first time using the application do this step. Type the following command in the window: “pip install -r requirements.txt” and press Enter.It will install all the necessary packages for the system to run. If you already did this step prior to this or if all the packages are installed proceed to the next step. 

6.	Type the following command in the window: “python app/server.py serve” and press Enter. The line: “Uvicorn running on http://0.0.0.0:80 (Press CTRL+C to quit)” means that the application is already up and running.

7.	Open a web browser and type “localhost” in the address bar and press Enter. You should be directed to the home page of the application.

8.	You may proceed to use the application.

9.	After using the application and before closing the windows. Go back to the cmd window and press “Ctrl + C” to terminate the server.
 

B.	How to Use the Application
1.	The user can select an image which be analyzed by the application. Note that the image must be in JPEG format otherwise it would not be accepted by the application.
 
2.	After clicking “Analyze” the app shows the result of the analysis (demented or nondemented) as well as accompanying probability.
 
3.	The user can also opt to save the result as a PDF File and view it.
 
C.	System Requirements
•	Operating systems: Windows 7 or later, macOS, and Linux
•	Processor: 1 gigahertz (GHz) or faster processor or SoC
•	RAM: 4 gigabytes (GB) 
•	Hard disk space: 16 GB for 32-bit OS or 20 GB for 64-bit OS
•	Graphics card: DirectX 9 or later with WDDM 1.0 driver
•	Display: 800 x 600 (minimum)
•	Python versions: 2.7.X, 3.6.X
•	JavaScript version: 1.5 or later
•	Additional Packages: see requirements.txt file
