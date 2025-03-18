# Django Blog System

## Description
Hello user! This is a blog project.

This is a simple blog system built using Django. Users can create an account, write blog posts categorized by topics, and interact with other users' posts through likes and comments. Additionally, users can edit or delete their own blog posts and log out of their accounts.

## Features
- **User Authentication**: Users can register, log in, and log out.
- **Blog Post Management**: Users can create, edit, and delete their blog posts.
- **Search Functionality**: Users can search for blog posts by title.
- **Category-Based Blogs**: Blog posts are categorized for better organization.
- **Like & Comment**: Any user can like a blog post and leave comments.

## Setting Up

### Prerequisites
- Python 3.x
- Django 4.x or later
- Virtual environment (recommended)

### Steps to Install
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/django-blog.git
   cd django-blog
   ```

2. **Set up the virtual environment**
   ```sh
   source env/source/active  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up the SQLite database**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**
   ```sh
   python manage.py createsuperuser
   ```
   Follow the prompts to set up an admin account.

6. **Run the project**
   ```sh
   python manage.py runserver
   ```
   Open `http://127.0.0.1:8000/` in your browser.

## If you encounter package errors
If you get any errors related to missing packages, install them using:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
- Sign up and log in.
- Create a new blog post and assign it to a category.
- Edit or delete your own blog posts.
- Search for blog posts using the search bar.
- Like and comment on any blog post.
- Log out when done.

## Some Stored Credentials
- **Email**: brian@fast.com
- **Password**: brian123

## Technologies Used
- Django (Backend Framework)
- SQLite (Default Database)
- Bootstrap (Frontend Styling)
- MySQL (If you choose)/Any

## License
This project is licensed under the MIT License.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact
For any inquiries or support, reach out at iamshimantadas@gmail.com.