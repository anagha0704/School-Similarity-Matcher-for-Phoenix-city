# School-Similarity-Matcher-for-Phoenix-city

### Project Overview
The School Similarity Matcher is a Python-based data analysis tool designed to help users find schools in Phoenix, AZ, that are similar based on various factors such as student enrollment, racial demographics, and other school-related attributes. The project leverages similarity analysis using multiple measures, providing users with data-driven insights to assist in school selection.

### Features
- Data Cleaning and Preprocessing: The data is cleaned and transformed, handling missing values, converting data types, and removing extraneous characters.
- Similarity Analysis: Schools are compared using a variety of features, including:
    - Student Enrollment
    - Racial Demographics (e.g., Asian, Hispanic, White, etc.)
    - Gender Breakdown
    - Lunch Program Eligibility

## Data
The dataset used in this project contains detailed information on schools in Phoenix, AZ, including:
- School name, city, and type (public/private)
- Racial demographic breakdowns
- Student enrollment and teacher-student ratio
- Eligibility for free or reduced lunch programs
- County and geographical data
  
(The dataset was gathered manually, as an academic project, using reference:
- https://azreportcards.azed.gov/
- https://high-schools.com/directory/az/cities/phoenix/
- https://nces.ed.gov/GLOBALLOCATOR/
- https://www.usnews.com/education/best-high-schools
)

## Usage
- Data Preprocessing: The first step is cleaning the data, including removing invalid characters, converting data types, and filling missing values.
- Similarity Calculation: Once the data is prepared, the next step is to calculate the similarity between different schools using measures such as Euclidean distance or cosine similarity.


