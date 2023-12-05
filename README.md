# Online Course Platform

The Online Course Platform is a Django-based web application that facilitates user registration, course enrollment, exam submissions, and includes an administration panel for managing course-related entities.

## Features

- **User Registration:** Allow users to register for an account with a unique username and password.

- **User Authentication:** Enable users to log in and log out securely.

- **Course Listing:** Display a list of available courses, ordered by total enrollment.

- **Course Detail:** Provide detailed information about a specific course, including enrollment status.

- **Course Enrollment:** Allow users to enroll in courses, updating the total enrollment count.

- **Exam Submission:** Enable users to submit exam answers and record their choices.

- **Exam Result:** Display exam results, showing the total grade and individual question outcomes.

- **Admin Panel:** Administrators can manage the following entities through the Django admin panel:
  - Courses
  - Lessons
  - Instructors
  - Learners
  - Questions
  - Choices
  - Submissions

## Installation

To run the Online Course Platform locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/online-course-platform.git
    cd online-course-platform
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

4. Create a superuser account to access the admin panel:

    ```bash
    python manage.py createsuperuser
    ```

5. Start the development server:

    ```bash
    python manage.py runserver
    ```

Visit `http://127.0.0.1:8000/` in your web browser to access the application and `http://127.0.0.1:8000/admin/` to access the admin panel.

## Usage

1. Register for a new account or log in with existing credentials.

2. Explore the list of courses and view detailed information about each course.

3. Enroll in a course to access its content.

4. Submit exam answers through the exam submission feature.

5. Check exam results to see your total grade and individual question outcomes.

6. Access the admin panel by logging in with the superuser account created earlier.

## Screenshots

Include some screenshots of your application to provide a visual representation of its interface.

### 1. Admin Panel
![admin](https://github.com/SarmadNaroo/online-course-app-Django-Project/assets/87594636/96e48f1c-d1eb-458a-8a11-96d260113d33)

### 2. Courses list
![courses](https://github.com/SarmadNaroo/online-course-app-Django-Project/assets/87594636/93eb10c6-f127-4c8a-be79-28d6362f4320)

### 3. Quiz
![Quiz](https://github.com/SarmadNaroo/online-course-app-Django-Project/assets/87594636/24e22dcd-3ee0-4627-b447-bbe99a81d6e0)

### 4. Result
![result](https://github.com/SarmadNaroo/online-course-app-Django-Project/assets/87594636/382752d4-940c-4fd0-af3c-88c00a4880a5)



## Contributing

We welcome contributions to enhance the Online Course Platform. Follow these guidelines:

1. Fork the repository and create a new branch.

2. Make your changes and ensure the code follows PEP 8 style guidelines.

3. Submit a pull request, providing details about the changes made.
