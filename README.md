# Digital_Health_Hackathon_Challenge2
Submission for Quarterfinal Round of the 2022 Dr Reddy's Digital Health Hackathon for Challenge 2 - Vital Vision 2.0.

  This repository contains code for the solution of Challenge 2 of Dr. Reddy's Digital Health Hackathon 2022 - Vital Vision 2.0.

  We have hosted a website for UI/UX using Flask.

  To run this code and access our website UI and use the software we created to upload handwritten prescriptions and extract important medical entities 
  from it, do the following:

  1. Download this repository exactly as it is (VERY IMPORTANT). PLEASE MAKE SURE THAT YOU RUN APP.PY IN A DIRECTORY THAT IS EXACTLY THE SAME AS THIS REPO.

  2. Install all the libraries and dependencies as listed in requirements.txt in a new python environment. Please install any other dependencies that 
     may be needed depending on the specific system being used. These will come up as import/dependency errors in the terminal.

  3. IN YOUR TERMINAL, run the following command:

     python3 app.py
        OR
     python app.py

  4. Go to your localhost at PORT 5000. That is, go to the following URL on your local system. This will also be output on your terminal as the 
     URL that's hosting our UI website.

     http://127.0.0.1:5000

  5. Now, follow the steps and cues as visible on our UI to use our system for extraction of medical entities from handwritten prescriptions.
     You can also refer to the sample_outputs folder where screenshots are available to show the step-by-step use and functioning of the UI.

     You can use example handwritten prescriptions from our sample_prescriptions folder to test our software.

  6. The access key and secret keys used in the code to communicate with AWS are from our personal account.

  7. AWS DynamoDB is interfaced in the backend and the extracted data is stored int
