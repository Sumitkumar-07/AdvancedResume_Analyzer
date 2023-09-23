# Advance Resume Analyzer
Advance Resume Analyzer is a Streamlit-based web application that allows users to upload their resumes, analyze them, and receive smart recommendations based on the content of the resume. The application provides insights into the user's skills, recommends additional skills, suggests relevant courses, and offers resume writing tips.

# Features

- **Resume Upload:** Users can upload their resumes in PDF format.
- **Resume Analysis:** The application extracts information from the resume, including name, email, contact details, and more.
- **Skills Recommendation:** Based on the skills identified in the resume, the app recommends additional skills relevant to specific job fields.
- **Courses Recommendations:** Users receive course recommendations based on their predicted job field.
- **Resume Writing Tips:** Users get tips for improving their resumes, including suggestions for adding an objective, declaration, hobbies, achievements, and projects.
- **Resume Score:** Users receive a score for their resume writing, encouraging them to make improvements.

## Usage

1. **Select "Normal User"** to analyze your resume or "Admin" to access admin features (username and password required).
2. **Upload your resume** in PDF format.
3. The application will analyze your resume and provide recommendations for skills, courses, and resume writing.
4. You can interact with the recommended skills and courses tags to see details.
5. **View your resume score** and watch bonus videos for resume writing and interview tips.

## Admin Access

- For admin access, use the following credentials:
  - **Username:** machine_learning_hub
  - **Password:** mlhub123

## Database

The application uses a **MySQL database** to store user data. You can find the database configuration in the code.

## Important
- Make sure to write your Mysql credential in the code in place of localhost,user,pass

## Data Visualization

The README file includes data visualization using **Plotly**, displaying pie charts for predicted job fields and user experience levels based on the collected user data.

## Technologies Used

- **Streamlit:** Web application framework for building the user interface.
- **NLTK and spaCy:** Natural language processing libraries for text analysis.
- **PDFMiner:** For parsing and extracting text from PDF resumes.
- **PyResParser:** Python library for parsing resumes.
- **Plotly:** For creating interactive data visualizations.
- **YouTube-DL:** For fetching YouTube video information.
- **pymysql:** Python MySQL client for database interaction.

