# Jobkhujo - Online Job Portal Website

**Jobkhujo** is a simple and user-friendly job portal website which is built using PHP, MySQL, HTML, and CSS. It helps job seekers find and apply for jobs, while allowing employees to post job openings and manage application which can be obtained from one platform.

## Features

### For Job Seekers (Employees):
- Easy registration and login.

- Search for jobs by catagory or location.

- Apply for jobs directly from the dashboard.

- Create and manage resume.

- Generate downlodable resume PDFs using TCPDF.

### For Employers:
- Registration and create a company profile.

- Post new job openings.

- View and manage application from job seekers.


### Common Features:
- Smart chatbot to guide users and answer FAQs.

- Secure login system with session handling.


## Technologies Used
- **Frontend**: HTML, CSS.

- **Backend**: PHP.

- **Database**: MySQL.

- **PDF Resume Generator**: TCPDF.

- **Testing Tool**: Selenium (Black Box Testing).

- **Server**: XAMPP (for local development).


## Installation Process
**Prerequisites**
Ensure the following software is installed:
- XAMPP (Apache, PHP, MySQL).

**Steps**
 
  1. Clone the repository:

     ```bash
       git clone https://github.com/tasfina008/Online_Job_Portal.git


  2. Unzip the Online Job Portal file.  
  
  3. Move the folder to the XAMPP -> htdocs directory.
  
  4. Import the databse:
  
     - Open phpMyAdmin.
     
     - Create a new database named jobportal.
     
     - Import the JobPortal.sql file.

 
5. Start Apache and My SQL from the XAMPP control panel.
     
6. Open your browser and go to:
      http://localhost/OnlineJobPortal/System/


## Usage

**Employees:**
Register or login, complete the profile, create resume, and apply for jobs. Employees can also generate a PDF version of their resume.

**Employer:**
Register or login, create job posts, and view applicants from the dashboard.

**Chatbot:**
Ask question to get instant help.


## Troubleshooting
**If the PDF doesn't generate**
  - Make sure the TCPDF library is correctly included.
  - Check file permissions and paths in the resume generation script.

