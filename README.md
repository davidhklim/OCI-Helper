# OCI HELPER

**Cover Letter Generator - User Guide**

Welcome to OCI Helper, a tool designed to automate the creation of personalized cover letters using firm-specific data. This guide provides instructions on how to use the tool, download the repository, and run the executable files. If you have suggestions (e.g., adding other cities), please let me know!

---

## Important Note for macOS Users

macOS does not natively support Windows executable files (.exe). To run the EXE file included in this repository, please download and install:

- [Wine](https://www.winehq.org/)
- [WineBottler](https://winebottler.kronenberg.org/)

After installation, use these tools to execute the EXE file. For step-by-step instructions, see [Video Instructions](https://www.youtube.com/watch?v=xTsuAKkaur8).

---

## Additional Resource: OCI Tracker

I created an [OCI Tracker](https://docs.google.com/spreadsheets/d/1VZIOgAQZAfTfsn78PIqvQXCOFdRAdJLM0eMgSDP4w3c/edit?usp=sharing) to help keep you organized during the application process. 

**Make a copy to your drive** for personal use.

---

## OCIHelper.exe Overview

**Description:**
- Automates the creation of personalized cover letters using firm-specific data.
- Based on the official Peter A. Allard School of Law Cover Letter and Resume template (customizable to your needs).

> **Important:** Ensure that your cover letter header format matches your resume header format.


### Selecting Firms
The `Firm_List.xlsx` file houses all the firm information that the program uses to populate the placeholder fields in your cover letter template. 

The information is up to date as of **March 31, 2025**. **Quickly double-check that the information is correct** (see `FirmSearch.exe` below).


- The spreadsheet includes separate sheets for **Vancouver** and **Toronto**. (Let me know if you want me to add other cities!)
- To generate cover letters for specific firms, check the boxes next to the firms you are interested in under the **'AP'** column.
- **Note:** The `FirmSearch.exe` program refers to this sheet and will only open browser tabs for the firms that are selected.

### File Naming Convention
- The generated cover letter files will be named using the following convention: [Template Cover Letter Name] + " (Short_Name)"
- **Example:**  
If your template is named `ElleWoods_Cover Letter` and you applied to **BLG**, the resultant files will be:
- `ElleWoods_CoverLetter (BLG).docx`
- `ElleWoods_CoverLetter (BLG).pdf`

**Usage Instructions:**
1. **Update the Template:**
   - Open the cover letter template.
   - Customize the template as needed while keeping the following placeholder fields intact. These fields will be automatically filled with firm-specific information from `Firm_List.xlsx`:
     - **«Firm»**: The full name of the firm (e.g., Agee, Poe & Epps LLP)
     - **«Short_Name»**: A shortened name for subsequent references (e.g., APE)
     - **«Salutations»**: Appropriate honourifics (e.g., Mr., Ms.)
     - **«Contact»**: The name of the Hiring Manager (e.g., Kyle McAvoy)
     - **«Title»**: The Hiring Manager’s title (e.g., Director, Student Programs and Legal Recruitment)
     - **«Street»**: The firm’s street address (e.g., 000 King Street West, Suite 000)
     - **«City»**: The city, province, and postal code (e.g., Toronto, ON Q1Q 1Q1)

2. **Run the Executable:**
   - Double-click `OCIHelper.exe` to launch the Cover Letter Generator.
   - When prompted, select your updated Word template.

3. **Generate PDFs:**
   - The program reads firm information from the accompanying Excel file.
   - It generates personalized cover letters and saves them as DOCX and PDF files.
   - The DOCX and PDFs are organized into separate folders based on the firm data groups.

---

## FirmSearch.exe Overview

**Description:**
- Quickly looks up addresses and Student Hiring Managers for the firms listed in `Firm_List.xlsx`. (Kind of janky)

**Usage Instructions:**

1. **City Selection:**
   - The program prompts you to choose between Toronto and Vancouver.

2. **Address Verification:**
   - For each firm (as listed in `Firm_List.xlsx`), the program opens a browser tab for the chosen city so you can verify the firm's address.

3. **Student Hiring Manager Search:**
   - If you opt to search for the Student Hiring Manager, additional browser tabs will open with a search for each firm combined with "Student Hiring Manager."

---
## Downloading the Repository on macOS

1. **Open Terminal:**
   - Press `Cmd + Space`, type `Terminal`, and press `Enter` to open the Terminal app.

2. **Navigate to Your Downloads Folder:**
   - In Terminal, run the following command to navigate to the Downloads folder:
     ```bash
     cd ~/Downloads
     ```

3. **Clone the Repository:**
   - To clone the repository, run the following command:
     ```bash
     git clone https://github.com/davidhklim/OCI-Helper.git
     ```

4. **Install Git LFS (Large File Storage):**
   - If you don’t have Git LFS installed, run the following command to install it:
     ```bash
     brew install git-lfs
     ```

5. **Initialize Git LFS:**
   - After installation, initialize Git LFS by running:
     ```bash
     git lfs install
     ```

6. **Download the Large Files:**
   - Once the repository is cloned, navigate into the cloned directory:
     ```bash
     cd OCI-Helper
     ```
   - Run the following command to download the large files using Git LFS:
     ```bash
     git lfs pull
     ```

7. **Verify the Download:**
   - To verify that the repository and large files were downloaded correctly, list the contents:
     ```bash
     ls
     ```

8. **Reminder to Run the EXE File:**
   - macOS does not natively support Windows executable files (.exe). To run the EXE file included in this repository, please download and install [Wine](https://www.winehq.org/) and [WineBottler](https://winebottler.kronenberg.org/).
   - Once installed, you can use these tools to execute the EXE file on your macOS system.


## Downloading the Repository on Windows

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

4. **Install Git LFS (Large File Storage):**
   - If you don’t have Git LFS installed, download and install it from [here](https://git-lfs.github.com/).
   - After installation, run the following command to set up Git LFS:
     ```bash
     git lfs install
     ```

5. **Download the Large Files:**
   - Once the repository is cloned, navigate into the cloned directory:
     ```bash
     cd OCI-Helper
     ```
   - Run the following command to download the large files using Git LFS:
     ```bash

You're all set! The repository is now downloaded to your Downloads folder.




