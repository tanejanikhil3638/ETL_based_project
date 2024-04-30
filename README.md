# Multithreaded ETL System

Welcome to the Multithreaded ETL System! This project is built using HTML, CSS, and Flask to provide a user-friendly interface for performing ETL (Extract, Transform, Load) operations on CSV files.

## Methodology

1. **Extract**: Load data from CSV files (source and target).
2. **Transform**: Add constraints to match source data with target data.
3. **Load**: Append source data to target data.

## Description

This project aims to simplify the process of data transformation for users. By providing an intuitive web interface, users can easily upload their CSV files and apply a variety of transformations according to their requirements. The multithreaded architecture ensures efficient processing, allowing for quick transformation even with large datasets.

## Input/Output

### Input
- Users provide input in the form of CSV files.
- The system accepts CSV files of any size, ensuring flexibility for users.
- User selects the transform functions.

### Output
- The transformed CSV file is generated based on the selected transformations.
- Users can download the transformed CSV file for further analysis or use.

## How to Use

1. Clone this repository:
```shell
   git clone https://github.com/tanejanikhil3638/ETL_based_project.git
```

2. Navigate to the project directory:
```shell
   cd ETL_based_project
```

3. Install dependencies:
```shell
   pip install -r requirements.txt
```

4. Run the Flask application:

```shell
   python app.py
```

5. Access the application in your web browser.

6. Upload your CSV file, select desired transformations, and click on the 'Transform' button.

7. Once the transformation is complete, download the transformed CSV file.

Feel free to contribute by forking the repository and submitting pull requests.

## Screenshot of User Interface

![cc463a56-f5f6-49c1-bd5f-c489ee30606b](https://github.com/tanejanikhil3638/ETL_based_project/assets/98747035/344916eb-653c-45a0-ac5c-5741dd61073b)


