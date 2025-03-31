## OCI HELPER

**Cover Letter Generator - User Guide**

Let me know if you want me to add other cities :)

**Note to Mac Users**  
The executable files (.exe) are for Windows only. To run the program on a Mac, you must download Wine and Wine Bottler (free).  
- Link here: https://winebottler.kronenberg.org/
- See video instructions here: https://www.youtube.com/watch?v=xTsuAKkaur8


I also create an **OCI Tracker** that I found useful in helping me keep organized through the process (Create copy to your drive) 
- Link here: https://docs.google.com/spreadsheets/d/1VZIOgAQZAfTfsn78PIqvQXCOFdRAdJLM0eMgSDP4w3c/edit?usp=sharing


**OCIHelper.exe** Description:  
- This tool automates the creation of personalized cover letters using firm-specific data
- It is based on the official Peter A. Allard School of Law Cover Letter and Resume template, but you can change the format however you like

***Important Sidenote:*** Your cover letter header formate and resume header format should match.

Usage Instructions:  
(1) Update the Template:  
   - Edit your cover letter template as needed.  
   - Use the official Peter A. Allard School of Law template.  
   - Copy and paste the required placeholder fields (e.g., «Short_Name») as you edit.

------------------------------------------------------------------------------------------------------------------------------------     
   -   **«Firm»**: Full name of firm. e.g., Agee, Poe & Epps LLP
   -   **«Short_Name»**: Short name of the firm that will be referenced for the remainder of the cover letter e.g., APE
   -   **«Salutations»**: Honourifics; e.g., Mr., Ms.
   -   **«Contact»**: Name of the Hiring Manager e.g., Kyle McAvoy
   -   **«Title»**: Title of the Hiring manager e.g., Director, Student Programs and Legal Recruitment
   -   **«Street»**: Firm street e.g., 000 King Street West, Suite 000
   -   **«City»**: City, Province Postal Code e.g., Toronto, ON Q1Q 1Q1
------------------------------------------------------------------------------------------------------------------------------------

(2) Run the Executable:  
   - Double-click the executable file to launch the Cover Letter Generator.  
   - When prompted, select your updated Word template.

(3) Generate PDFs:  
   - The program reads firm information from the accompanying Excel file.  
   - It generates personalized cover letters and outputs them as PDF files.  
   - The PDFs are organized into separate folders for each group of firm information.
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------
The **FirmSearch.exe** program lets you quickly look up addresses and Student Hiring Managers for the firms listed in Firm_List.xlsx. 

(1) It will first prompt you to choose between Toronto and Vancouver. 

(2) The program opens a browser tab for each selected firm (Firm_List.xlsx) for the selected city so you can verify the address from the Excel file. 

(3) Next, it will ask if you wish to search for the Student Hiring Manager; if you click 'Yes', it opens additional tabs searching for each firm along with "Student Hiring Manager."

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

## Downloading the Repository on macOS

If you're using macOS and want to download the OCI-Helper repository using the command line, follow these steps:

1. **Open Terminal:**
   - Open the Terminal app. You can find it via Spotlight or in `/Applications/Utilities/Terminal.app`.

2. **Navigate to Your Downloads Folder:**
   - In Terminal, run:
     ```bash
     cd ~/Downloads
     ```

3. **Clone the Repository:**
   - Run the following command to clone the repository into your Downloads folder:
     ```bash
     git clone https://github.com/davidhklim/OCI-Helper.git
     ```
   - This command will create a folder named `OCI-Helper` in your Downloads folder containing all the repository files.

4. **Verify the Download:**
   - To verify that the repository was cloned correctly, navigate into the folder and list its contents:
     ```bash
     cd OCI-Helper
     ls
     ```

5. **Reminder to Run the EXE File:**
   - macOS does not natively support Windows executable files (.exe). To run the EXE file included in this repository, please download and install [Wine](https://www.winehq.org/) and [WineBottler](https://winebottler.kronenberg.org/).
   - Once installed, you can use these tools to execute the EXE file on your macOS system.

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

## Downloading the Repository on Windows

If you're using a Windows PC and want to download the OCI-Helper repository using the command line, follow these steps:

1. **Open Command Prompt or Git Bash:**
   - **Command Prompt:** Press `Win + R`, type `cmd`, and press Enter.
   - **Git Bash:** Right-click on the Desktop or search for Git Bash in the Start menu.

2. **Navigate to Your Downloads Folder:**
   - In **Command Prompt**, run:
     ```bash
     cd %HOMEPATH%\Downloads
     ```
   - In **Git Bash**, run:
     ```bash
     cd ~/Downloads
     ```

3. **Clone the Repository:**
   - Run the following command to clone the repository into your Downloads folder:
     ```bash
     git clone https://github.com/davidhklim/OCI-Helper.git
     ```
   - This command will create a folder named `OCI-Helper` in your Downloads folder containing all the repository files.

4. **Verify the Download:**
   - To verify that the repository was cloned correctly, navigate into the folder and list its contents:
     - In **Command Prompt**:
       ```bash
       cd OCI-Helper
       dir
       ```
     - In **Git Bash**:
       ```bash
       cd OCI-Helper
       ls
       ```

You're all set! The repository is now downloaded to your Downloads folder.



