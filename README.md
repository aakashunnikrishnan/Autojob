# AutoJob - Automated Job Application System
AutoJob is an automated job application system that helps you search for job opportunities, filter them based on your resume, and automatically apply to suitable positions in the top 100 IT companies. This project combines web crawling, resume analysis, filtering algorithms, and application automation to streamline the job search process.

## Features
Web Crawling: AutoJob uses web crawling techniques to extract job listings from the career websites of the top 100 IT companies. It visits these websites on a weekly basis to gather the latest job opportunities.

Resume Analysis: The system includes a resume parser that extracts key information from resumes, such as skills, experience, education, and other relevant details. It utilizes natural language processing techniques to analyze the resume data.

Filtering and Recommendation: AutoJob matches the extracted resume data with the requirements mentioned in the job listings. It applies a set of criteria to filter the job listings and identifies the opportunities that best match the candidate's profile.

Application Automation: The system integrates with the application submission systems of the target companies, if available. It automatically fills in application forms with the relevant information from the resume, streamlining the application process.

Notification and Tracking: AutoJob provides notifications to the user about the applied jobs, including success or failure notifications. It also tracks the application status for each job, allowing users to monitor their progress.

## User Interface: The project includes a user interface (UI) that allows users to input their resume, view recommended job listings, and manage the application process. The UI provides an intuitive and user-friendly experience.

## Installation
Clone the repository: git clone https://github.com/your-username/autojob.git
Install the required dependencies: pip install -r requirements.txt
Configure the system by updating the necessary settings and credentials in the configuration file (config.py).
Run the application: python app.py
Access the AutoJob UI by visiting http://localhost:5000 in your web browser. 

## Usage
Sign up or log in to your AutoJob account.
Upload your resume to the system.
Wait for the weekly crawl to complete, fetching the latest job opportunities.
View the recommended job listings based on the match between your resume and the job requirements.
Apply to suitable positions by selecting the jobs and initiating the application process.
Monitor the application status and receive notifications about the progress of your applications.

## Contributing
Contributions to AutoJob are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute new features, please submit a pull request. Make sure to follow the established coding style and include tests for any new functionality.

## License
AutoJob is licensed under the MIT License. Feel free to modify and distribute the project as per the terms of the license.

## Acknowledgments
We would like to thank the open-source community for their contributions, as well as the creators of the libraries and tools used in this project.

## Contact
For any inquiries or questions, please contact the project maintainer at aakashunnikrishnan1998@gmail.com

