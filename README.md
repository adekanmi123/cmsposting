# Symfony Blog

I started to get familiar with the `Symfony` framework.

As a starting point, I decided to create a simple blog starting from scratch.

I will be using the latest MySQL 5.7, PHP 7.2, Symfony 5.4 for now.

Implementation steps:
- Install the framework `Symfony` and start the server
- Separation front and admin area, each with its own a skeleton template
  - front: [Bootstrap 5](https://getbootstrap.com)
  - admin: [SB Admin](https://startbootstrap.com/template/sb-admin)
- Registration, authentication, authorization (separate forms for front and admin areas)
- Users with roles: `ROLE_USER`, `ROLE_ADMIN`, `ROLE_SUPER_ADMIN`

### In the admin area
- Dashboard
- Blog management
  - Posts
  - Categories
  - Tags
- Page management
- User management

---


```

composer install
yarn install
yarn encore dev
make db-seed

To run the program
Cd to cms
Php bin/console server:run to produce 
http://127.0.0.1:8000/
Insert it to browser it

Go to admin
username:adekanmi
password:password

To create post,edit,delete
