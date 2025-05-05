
# Odin Rails Blog 

A simple Ruby on Rails blog application built as part of [The Odin Project](https://www.theodinproject.com/) curriculum. This project demonstrates the fundamentals of a full-stack web application using Rails' Model-View-Controller (MVC) architecture.

---

##  About

This blog app allows you to:

- View a list of all articles
- Create a new article
- Edit an existing article
- Delete an article
- View each article individually

It's a minimal example designed as/with:

- Rails routing and RESTful conventions
- Controller actions and views
- Form helpers (`form_with`)
- Validations and error handling

>  Note: This project does **not** include authentication, styling, or comment features — it is intentionally kept simple for educational purposes.

---

## Getting Started

### Prerequisites

- Ruby 3.2.x
- Rails 7.1.x
- SQLite (default dev DB)
- Bundler

### Installation

1. Clone the repository:
   git clone https://github.com/Ajbakaric/Odin-rails-blog.git
   cd Odin-rails-blog
````

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Set up the database:

   ```bash
   rails db:create
   rails db:migrate
   ```

4. Start the server:

   ```bash
   rails server
   ```

5. Visit in your browser:

   ```
   http://localhost:3000/articles
   ```
 Tech

* Ruby on Rails
* SQLite3 (development)
* ERB (embedded Ruby views)

 Acknowledgements

* [The Odin Project](https://www.theodinproject.com/)
* [Ruby on Rails Guides](https://guides.rubyonrails.org/)


