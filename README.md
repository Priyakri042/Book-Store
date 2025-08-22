# Book Store

A web application for browsing, searching, and managing books, built with Angular.

## Features

- User authentication (login, signup, forgot password)
- Browse books with detailed information
- Add books to cart and wishlist
- Place orders and view order history
- Admin dashboard for managing books and orders
- Responsive UI with reusable components

## Project Structure

- `src/app/components/` — Angular components (book card, cart, admin, etc.)
- `src/app/services/` — Services for data, user, book, cart, and HTTP operations
- `src/app/pipes/` — Custom pipes (e.g., search)
- `src/assets/` — Images, icons, and static assets
- `src/environments/` — Environment configuration files

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm (v6 or higher)
- Angular CLI (`npm install -g @angular/cli`)

### Installation

1. Clone the repository:
	```sh
	git clone https://github.com/Priyakri042/Book-Store.git
	cd Book-Store
	```

2. Install dependencies:
	```sh
	npm install
	```

### Running the Application

Start the development server:
```sh
npm start
```
Navigate to `http://localhost:4200/` in your browser.

### Running Tests

To execute unit tests:
```sh
npm test
```

## License

This project is licensed under the MIT License.