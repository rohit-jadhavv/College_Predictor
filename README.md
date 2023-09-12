# College Predictor

This is a Django-based web application that helps users find colleges based on their input percentile. It also provides additional information about each college and allows registered users to rate colleges.

**Website Link:** [College Predictor](https://collagepredictor.pythonanywhere.com/) <!-- Replace with the actual link to your website -->

## Features

- **College Search**: Users can enter their percentile to search for colleges that match their criteria.
- **College Details**: Clicking on a college name displays detailed information about that college.
- **User Registration**: Users can sign up for an account to access the rating feature.
- **College Rating**: Registered users can rate colleges and provide feedback.
- **Responsive Design**: The website is designed to work seamlessly on various devices.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

    ```shell
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Create a virtual environment:

    ```shell
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

        ```shell
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```shell
        source venv/bin/activate
        ```

4. Install the project dependencies:

    ```shell
    pip install -r requirements.txt
    ```

5. Apply database migrations:

    ```shell
    python manage.py migrate
    ```

6. Create a superuser account:

    ```shell
    python manage.py createsuperuser
    ```

7. Start the development server:

    ```shell
    python manage.py runserver
    ```

8. Access the website in your browser at `http://localhost:8000/`.

## Usage

1. Visit the website and enter your percentile to search for colleges.
2. Click on a college to view its details.
3. Sign up for an account to be able to rate colleges.
4. After signing in, you can rate colleges and provide feedback.

## Screenshots

### Landing Page

![image](https://github.com/rohit-jadhavv/College_Predictor/assets/98208763/3cc4144f-14fe-43ef-8b74-c6e803fac25c)

### Home Page
![image](https://github.com/rohit-jadhavv/College_Predictor/assets/98208763/55ba414b-43be-449a-9db7-55239534ca3b)


### Login Page

![image](https://github.com/rohit-jadhavv/College_Predictor/assets/98208763/8f17b3b0-e7e5-47fb-9b46-76cb5393e046)

### College Info Page

![image](https://github.com/rohit-jadhavv/College_Predictor/assets/98208763/2a28c3a8-b983-425a-90b0-b05e7a32e782)


## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.
