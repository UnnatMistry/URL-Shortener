# URL Shortener

## Getting Started:

These instructions will help you set up and run the URL Shortener application on your local machine.

### Prerequisites:

Before you begin, make sure you have the following software installed on your system:

- NodeJS version 14.x.x
- Yarn version 1.22.x

### Installation Steps:

1. **Install Yarn**:
   
   Yarn is a package manager that we'll use to manage dependencies for this project. If you don't have Yarn installed, you can do so by running the following command in your terminal:

   ```sh
   npm i -g yarn
   ```

2. **Install Node Modules**:
   
   Once Yarn is installed, navigate to the project directory in your terminal and run the following command to install the required Node modules:

   ```sh
   yarn install
   ```

### Running the Application:

Now that you have all the dependencies installed, you can run the URL Shortener application on your local machine.

1. **Start the App Locally**:
   
   To start the application, run the following command:

   ```sh
   yarn start
   ```

   This command will launch the application, and you can access it by opening your web browser and navigating to [localhost:4200](http://localhost:4200).

2. **[FOR DEVELOPMENT] Start Dummy API**:

   If you're a developer and need to work with a dummy API for testing purposes, you can start it by running:

   ```sh
   yarn api
   ```

   This will initialize the dummy API, allowing you to interact with it while developing and testing features.

### Killing Port 4200:

If you encounter any issues with the application not starting due to port 4200 being already in use, you can use the following command to kill the process using that port:

```sh
sudo kill -9 $(sudo lsof -t -i:4200)
```

This command will forcefully terminate the process using port 4200.

---
You're now ready to use the URL Shortener application locally on your machine. If you encounter any issues or have questions, feel free to reach out for assistance.

![Design preview for the URL shortening](./design/desktop-preview.jpg)

