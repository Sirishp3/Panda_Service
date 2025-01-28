# Project 3

## Description
Our project is a Software as a Service (SaaS) solution designed to streamline order management for restaurants. By prioritizing accessibility and user-friendliness, we aim to serve employees, customers, and managers with diverse technical skills and accessibility needs. This system provides tailored interfaces for each user group, ensuring a seamless experience for everyone involved.

## Key Features

### Accessibility Features:
- **Language Translation**: Supports Spanish translation feature for Spanish speaking users.
- **Screen Reader Support**: Ensures users with visual impairments can navigate the system effectively.
- **Enlarged Text and High-Contrast Visuals**: Provides customizable font sizes and contrast settings for better readability.
- **Intuitive Navigation**: Simple and clear navigation structure designed for ease of use, even for non-technical users.

### User-Specific Interfaces:
- **Cashiers**: POS interface designed for efficient order management and transaction processing.
- **Customers**: Self-service kiosk for independent ordering, enabling quick and easy menu browsing and order placement.
- **Managers**: Dashboard providing business insights, sales analytics, and inventory control features for efficient restaurant management.

### Additional Functionalities:
- **Google Authentication**: Supports Google authentication for efficient registration and log in.
- **Allergen and Nutrition Information**: Display allergen and nutritional details for customer awareness.
- **Chatbot**: Assists customers by answering frequently asked questions and providing support.
- **Weather widget**: Displays interesting weather information in a visually appealling widget.

## Installation
```
  # Install Node.js (includes npm)
  curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
  sudo apt-get install -y nodejs

  node -v     # Check Node.js version
  npm -v      # Check npm version

  cd client     # To start client
  cd client     # To start server
  npm install    # Run to install packages
  npm run dev
```

## Contributing

We welcome contributions to enhance the functionality and accessibility of our SaaS solution. To contribute, please follow the steps below:

### How to Contribute
1. **Fork the Repository**: Start by forking the repository to your own GitHub account.
2. **Clone the Repository**: Clone the repository to your local machine using the following command:
```git clone https://github.com/your-username/project-3.git```
3. **Create a Branch**: Create a new branch for your feature or bug fix:
```git checkout -b feature/your-feature-name```
4. **Make Changes**: Implement your changes. Be sure to follow the project’s coding conventions, ensure proper accessibility features are maintained, and add tests where necessary.
5. **Commit Your Changes**: Commit your changes with a descriptive message:
```git commit -m "Description of changes made"```
6. **Push Your Branch**: Push your changes to your forked repository:
```git push origin feature/your-feature-name```
7. **Create a Pull Request**: Navigate to the original repository and create a pull request from your fork. Provide a clear description of the changes you made and why.
