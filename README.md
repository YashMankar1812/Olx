# OLX Clone

A web application inspired by OLX, a platform for buying and selling items locally.

## Introduction

This project is a clone of the OLX website, built to provide a platform for users to buy and sell items within their local area. The application includes features such as user authentication, item listings, search functionality, and more.

## Features

- User authentication (login, signup, logout)
- Create, read, update, and delete (CRUD) operations for items
- Search functionality
- Responsive design for mobile and desktop
- Image upload for item listings
- Category filtering
- Location-based search

## Technologies Used

- **Frontend**: HTML, CSS, 

## Header
![Screenshot 2024-07-25 214435](https://github.com/user-attachments/assets/dd6997e8-98ca-46e2-82d2-03af660f793e)

## Categories 
![Screenshot 2024-07-25 214451](https://github.com/user-attachments/assets/5876acb1-2997-4fd7-92d4-21b254e640b7)

## Some Links 
![Screenshot 2024-07-25 214503](https://github.com/user-attachments/assets/61a9c1ca-b26d-426f-9829-6b2cef16c79e)

## Footer 
![Screenshot 2024-07-25 214512](https://github.com/user-attachments/assets/7cd328b4-70ba-43fe-ac16-ebdcc7450816)


## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    
    cd olx-clone
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the root directory and add the following variables:
    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_uri
    SESSION_SECRET=your_session_secret
    ```

4. **Run the application**:
    ```bash
    npm start
    ```

    The application will be running at `http://localhost:3000`.

## Usage

- **Home Page**: View a list of all items available for sale.
- **Search**: Use the search bar to find specific items.
- **Categories**: Filter items by categories.
- **Item Details**: Click on an item to view its details.
- **User Authentication**: Sign up or log in to create, edit, or delete your listings.
- **Create Listing**: After logging in, create a new item listing by filling out the form.
- **Edit Listing**: Edit your existing listings.
- **Delete Listing**: Delete your listings if they are no longer available.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository**:
    Click the "Fork" button on the top right of the repository page.

2. **Clone your forked repository**:
    ```bash
    git clone https://github.com/YashMankar1812/Olx.git
    cd olx-clone
    ```

3. **Create a new branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```

4. **Make your changes**:
    Add your feature or fix a bug.

5. **Commit your changes**:
    ```bash
    git add .
    git commit -m "Add your commit message here"
    ```

6. **Push to your forked repository**:
    ```bash
    git push origin feature/your-feature-name
    ```

7. **Create a pull request**:
    Go to the original repository and click on "New Pull Request" to submit your changes for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
