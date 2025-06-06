# Flutter Store Demo

A mobile application built with Flutter that demonstrates a simple e-commerce experience. Users can browse a list of products, view product details, and update product information. The application fetches data from the free `https://fakestoreapi.com`.

## Features

* **Product Listing:** Displays products in a grid view on the home page, showing product images, titles (substring), prices, and a favorite icon.
* **Update Product:** Allows users to navigate to a separate page to modify product details such as name, description, price, and image URL.
* **API Integration:** Interacts with `https://fakestoreapi.com` to:
    * Fetch all products.
    * Fetch all categories.
    * Fetch products within a specific category.
    * Add a new product.
    * Update an existing product.
* **User Feedback:**
    * Displays a loading indicator (`ModalProgressHUD`) during asynchronous operations like product updates.
    * Uses snack bars to show success or error messages.
* **Navigation:** Uses named routes for navigating between screens.

## API Used

This project uses the [FakeStoreAPI](https://fakestoreapi.com/) for product data.

## Tech Stack & Dependencies

* **Flutter & Dart**
* **HTTP:** For making API requests.
* **Font Awesome Flutter:** For icons.
* **Modal Progress HUD NSN:** For displaying loading indicators.

## Screenshots

* *Home Page (Product Grid)*
  ![Screenshot_٢٠٢٥٠٥٢٨-١٤٥١٢٨](https://github.com/user-attachments/assets/c018b93d-c75d-4e7e-9d2a-d86082b48afa)

* *Update Product Page*
  ![Screenshot_٢٠٢٥٠٥٢٨-١٤٥١٥٥](https://github.com/user-attachments/assets/92a15016-0a23-4494-90ef-8e785280e599)


## Setup

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd YOUR_REPOSITORY_NAME
    ```
3.  Get dependencies:
    ```bash
    flutter pub get
    ```
4.  Run the app:
    ```bash
    flutter run
    ```

## Project Structure

The project is structured as follows:

* `lib/`: Contains the core Dart code.
    * `main.dart`: Entry point of the application.
    * `models/`: Contains data models (e.g., `ProductModel`).
    * `screens/`: Contains UI screens/pages (e.g., `HomePage`, `UpdateProductPage`).
    * `services/`: Contains services for API calls and business logic.
    * `widgets/`: Contains custom reusable UI widgets (e.g., `CustomCard`, `CustomButton`, `CustomTextField`).
    * `helper/`: Contains helper classes/functions (e.g., `Api` helper, `showSnackBar`).
* `test/`: Contains unit and widget tests.
* `android/`, `ios/`, `web/`, `windows/`, `linux/`, `macos/`: Platform-specific code.
* 

This project was created as a part of learning and demonstrating Flutter development skills.
