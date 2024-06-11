# Project 1: Library Management System

## Classes

### Book

- **Attributes**:
  - `title`: Title of the book
  - `author`: Author of the book
  - `isbn`: ISBN number of the book
  - `copies`: Number of copies available

### Patron

- **Attributes**:
  - `name`: Name of the patron
  - `patron_id`: Unique ID of the patron
  - `borrowed_books`: List of books borrowed by the patron

### LibraryCRUD

- **Attributes**:
  - `books`: List of books in the library
  - `patrons`: List of patrons registered in the library

## Methods

### add_book

- **Description**: Adds a book to the library.
- **Parameters**:
  - `book`: An instance of the `Book` class.

### view_books

- **Description**: Displays all books in the library.

### update_book

- **Description**: Updates details of a book.
- **Parameters**:
  - `isbn`: ISBN number of the book to be updated.
  - `title`: (Optional) New title of the book.
  - `author`: (Optional) New author of the book.
  - `copies`: (Optional) New number of copies.

### delete_book

- **Description**: Deletes a book from the library.
- **Parameters**:
  - `isbn`: ISBN number of the book to be deleted.

### add_patron

- **Description**: Adds a patron to the library.
- **Parameters**:
  - `patron`: An instance of the `Patron` class.

### view_patrons

- **Description**: Displays all patrons in the library.

### update_patron

- **Description**: Updates details of a patron.
- **Parameters**:
  - `patron_id`: Unique ID of the patron to be updated.
  - `name`: (Optional) New name of the patron.

### delete_patron

- **Description**: Deletes a patron from the library.
- **Parameters**:
  - `patron_id`: Unique ID of the patron to be deleted.

### borrow_book

- **Description**: Allows a patron to borrow a book.
- **Parameters**:
  - `patron_id`: Unique ID of the patron borrowing the book.
  - `isbn`: ISBN number of the book to be borrowed.

### return_book

- **Description**: Allows a patron to return a book.
- **Parameters**:
  - `patron_id`: Unique ID of the patron returning the book.
  - `isbn`: ISBN number of the book to be returned.

### save_to_file

- **Description**: Saves the library data to a file.
- **Parameters**:
  - `filename`: Name of the file to save the data to.

### load_from_file

- **Description**: Loads the library data from a file.
- **Parameters**:
  - `filename`: Name of the file to load the data from.

# Project 2: Football Team Management System

## Classes

### Player

- **Attributes**:
  - `name`: Name of the player
  - `age`: Age of the player
  - `position`: Position of the player

### Team

- **Attributes**:
  - `team_name`: Name of the team
  - `team_id`: Unique ID of the team
  - `players`: List of players in the team

### FootballTeamManagementSystem

- **Attributes**:
  - `players`: List of players
  - `teams`: List of teams

## Methods

### add_player

- **Description**: Adds a player to the system.
- **Parameters**:
  - `player`: An instance of the `Player` class.

### view_players

- **Description**: Displays all players in the system.

### update_player

- **Description**: Updates details of a player.
- **Parameters**:
  - `name`: Name of the player to be updated.
  - `new_name`: (Optional) New name of the player.
  - `new_age`: (Optional) New age of the player.
  - `new_position`: (Optional) New position of the player.

### delete_player

- **Description**: Deletes a player from the system.
- **Parameters**:
  - `name`: Name of the player to be deleted.

### add_team

- **Description**: Adds a team to the system.
- **Parameters**:
  - `team`: An instance of the `Team` class.

### view_teams

- **Description**: Displays all teams in the system.

### update_team

- **Description**: Updates details of a team.
- **Parameters**:
  - `team_id`: Unique ID of the team to be updated.
  - `new_name`: (Optional) New name of the team.

### delete_team

- **Description**: Deletes a team from the system.
- **Parameters**:
  - `team_id`: Unique ID of the team to be deleted.

### assign_player_to_team

- **Description**: Assigns a player to a team.
- **Parameters**:
  - `player_name`: Name of the player to be assigned.
  - `team_id`: Unique ID of the team.

### remove_player_from_team

- **Description**: Removes a player from a team.
- **Parameters**:
  - `player_name`: Name of the player to be removed.
  - `team_id`: Unique ID of the team.

### save_to_file

- **Description**: Saves the system data to a file.
- **Parameters**:
  - `filename`: Name of the file to save the data to.

### load_from_file

- **Description**: Loads the system data from a file.
- **Parameters**:
  - `filename`: Name of the file to load the data from.

# Project 3: E-commerce System

## Classes

### Product

- **Attributes**:
  - `product_id`: Unique ID of the product
  - `name`: Name of the product
  - `price`: Price of the product
  - `stock`: Stock quantity of the product

### Customer

- **Attributes**:
  - `customer_id`: Unique ID of the customer
  - `name`: Name of the customer
  - `cart`: List of products in the customer's cart

### Order

- **Attributes**:
  - `order_id`: Unique ID of the order
  - `customer`: The customer who placed the order
  - `products`: List of products in the order
  - `total`: Total price of the order

### EcommerceSystem

- **Attributes**:
  - `products`: List of products in the system
  - `customers`: List of customers in the system
  - `orders`: List of orders placed

## Methods

### add_product

- **Description**: Adds a product to the system.
- **Parameters**:
  - `product`: An instance of the `Product` class.

### view_products

- **Description**: Displays all products in the system.

### update_product

- **Description**: Updates details of a product.
- **Parameters**:
  - `product_id`: Unique ID of the product to be updated.
  - `name`: (Optional) New name of the product.
  - `price`: (Optional) New price of the product.
  - `stock`: (Optional) New stock quantity of the product.

### delete_product

- **Description**: Deletes a product from the system.
- **Parameters**:
  - `product_id`: Unique ID of the product to be deleted.

### add_customer

- **Description**: Adds a customer to the system.
- **Parameters**:
  - `customer`: An instance of the `Customer` class.

### view_customers

- **Description**: Displays all customers in the system.

### update_customer

- **Description**: Updates details of a customer.
- **Parameters**:
  - `customer_id`: Unique ID of the customer to be updated.
  - `name`: (Optional) New name of the customer.

### delete_customer

- **Description**: Deletes a customer from the system.
- **Parameters**:
  - `customer_id`: Unique ID of the customer to be deleted.

### place_order

- **Description**: Places an order for a customer.
- **Parameters**:
  - `customer_id`: Unique ID of the customer placing the order.
  - `product_ids`: List of product IDs to be ordered.

### view_orders

- **Description**: Displays all orders in the system.

### save_to_file

- **Description**: Saves the system data to a file.
- **Parameters**:
  - `filename`: Name of the file to save the data to.

### load_from_file

- **Description**: Loads the system data from a file.
- **Parameters**:
  - `filename`: Name of the file to load the data from.
