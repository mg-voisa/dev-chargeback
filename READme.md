:<div id="top"></div>





<!-- ABOUT THE PROJECT -->
### About The Project

A small project which must have functionalities to add information about books and extract them through an API

### Specifications:
1. Users are connected to an account (account has multiple users)
2. Login page, application can be accessed only by logged users
3. A page with a form to add a book (title, author, release date), the insert must be unique by author and title. Inserted book belongs to user account.
4. A page where user can list (only) books added by his account in a table. In table must be a column with “Delete” button, to delete a book - delete action is accessible only first 2 days after book was inserted.
5. API endpoint used by an account to fetch his books. (/api/books)
6. API endpoint to get information of a specific book by id (/api/books/1)
7. API endpoints must be secured by JWT token, every account has a secret key for API
8. Seeder to create demo accounts, users, books

### Requirements: Laravel Policies, Middlewares, Input Validations, Code Style PSR-5
<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Laravel](https://laravel.com)
* [Bootstrap](https://getbootstrap.com)(not implied yet!)
* [JQuery](https://jquery.com)(not implied yet!)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
