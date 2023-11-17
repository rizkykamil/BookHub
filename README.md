<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg"
            width="400" alt="Laravel Logo">
    </a>
</p>

<p align="center">
    <!-- laravel version 10 -->
    <a href="https://packagist.org/packages/laravel/framework" target="_blank">
        <img src="https://img.shields.io/packagist/v/laravel/framework?label=laravel&style=flat-square"
            alt="Laravel Version">
    </a>

    <!-- php version 8 -->
    <a href="https://php.net" target="_blank">
        <img src="https://img.shields.io/packagist/php-v/laravel/laravel?style=flat-square"
            alt="PHP Version">
             </a>

    <!-- composer -->
    <a href="https://getcomposer.org" target="_blank">
        <img src="https://img.shields.io/badge/composer-%3E%3D%201.10.0-blue?style=flat-square"
            alt="Composer Version">
             </a>


</p>

## About This Project
BookHub adalah aplikasi manajemen buku tingkat lanjut yang dirancang untuk menyederhanakan pengorganisasian dan
pelacakan koleksi buku Anda. Baik Anda seorang yang rajin membaca, kolektor buku, atau mengelola perpustakaan, BookHub
memberikan solusi komprehensif untuk membuat katalog, mencari, dan berinteraksi dengan buku Anda.


## Learning Laravel
1. **CRUD**
- create data Buku
- Read Buku
- Update Buku
- soft delete Buku
- History
2. **Searching (js)**
- Filter berdasarkan genre buku
- Filter berdasarkan penulis buku
- Pencarian buku berdasarkan judul
- **Fitur Lainnya**
- Role-Based Access Control ([RBAC](https://github.com/itstructure/laravel-rbac))
- Pencocokan Otomatis Penulis dan Genre

## Install Project
1. Clone Project
```bash
git clone
```
2. Install Composer
```bash
composer install
```
3. Install NPM
```bash
npm install
```
4. Copy .env.example to .env
```bash
cp .env.example .env
```
5. Generate Key
```bash
php artisan key:generate
```
6. Migrate Database
```bash
php artisan migrate
```
7. Seed Database
```bash
php artisan db:seed
```
8. Run Project
```bash
php artisan serve
```


## How to Use BookHub

Welcome to BookHub, your comprehensive book management application. This guide will walk you through common workflows and scenarios to help you make the most out of BookHub.

### 1. **User Registration and Authentication:**
   - **Scenario:** New users need to create an account and existing users need to log in.
   - **Workflow:**
      1. Visit the BookHub website.
      2. Click on the "Sign Up" button to create a new account.
      3. Fill in the required registration details.
      4. Verify your email address if required.
      5. Log in using your credentials.

### 2. **Adding a New Book:**
   - **Scenario:** Users want to add a new book to their collection.
   - **Workflow:**
      1. After logging in, navigate to the dashboard.
      2. Click on the "Add Book" button.
      3. Fill in the book details, such as title, author, genre, and other relevant information.
      4. Upload a book cover image if desired.
      5. Click "Save" to add the book to your collection.

### 3. **Updating Book Information:**
   - **Scenario:** Users need to edit or update information about a book.
   - **Workflow:**
      1. Navigate to the book details page.
      2. Click on the "Edit" button.
      3. Modify the necessary information.
      4. Click "Save" to update the book details.

### 4. **Searching for Books:**
   - **Scenario:** Users want to find specific books within their collection.
   - **Workflow:**
      1. Use the search bar to enter keywords like title, author, or genre.
      2. Apply additional filters, such as genre or author, for more refined results.
      3. Review the search results to find the desired book.

### 5. **Viewing Book History:**
   - **Scenario:** Users want to see the history of changes made to a particular book.
   - **Workflow:**
      1. Navigate to the book details page.
      2. Look for the "History" section.
      3. View a log of changes, including timestamps and the user who made the modifications.

### 6. **Managing Loans and Returns:**
   - **Scenario:** Users want to keep track of book loans and returns.
   - **Workflow:**
      1. Navigate to the book details page.
      2. Use the "Loan" or "Return" button to manage the book's status.
      3. Set configurable time limits for loans.

### 7. **Dashboard Analytics:**
   - **Scenario:** Users want insights into their reading habits and collection.
   - **Workflow:**
      1. Visit the dashboard to access visual analytics.
      2. Explore charts and graphs that showcase application usage, book popularity, and reading trends.

### 8. **Notification System:**
   - **Scenario:** Users want to stay informed about relevant activities.
   - **Workflow:**
      1. Receive notifications for activities like book loans, returns, or changes to favorite books.
      2. Adjust notification preferences in the user settings.

### 9. **Role-Based Access Control:**
   - **Scenario:** Administrators need to manage user roles and permissions.
   - **Workflow:**
      1. Access the admin dashboard.
      2. Assign roles and permissions to users based on their responsibilities.

### 10. **Integration with Payment Gateway:**
   - **Scenario:** Users want to make online payments for book sales or premium subscriptions.
   - **Workflow:**
      1. Access the payment section.
      2. Follow the prompts to complete secure online transactions.

Explore these workflows to efficiently manage your book collection and enhance your reading experience with BookHub.




## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

Sebenernya izin aja :)