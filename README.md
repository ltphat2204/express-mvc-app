# Express MVC App Template
This is a template for an Express app following the Model-View-Controller (MVC) architectural pattern. It provides a starting point for building web applications with Express.

## Getting Started
To use this template, follow these steps:

Clone this repository to your local machine:

    git clone https://github.com/ltphat2204/express-mvc-app.git

Navigate to the project directory:

    cd express-mvc-app

Install the required dependencies:

    npm install

## Usage
### Models
To add a new model to your application, follow these steps:

1. Create a new folder inside the models directory.
2. Place your model files inside the newly created folder.
> Due to the variety of databases and their distinct syntaxes, I can not put any models as an example for this app

### Views
This template uses Pug as the view engine template. To add stylesheets or scripts to your views, modify the `layout.pug` file located in the `views` folder. You can link your CSS or JS files within this layout file, and they will be applied to all views.

### API Routing
To add more API routes to your application, follow these steps:

1. Create a new file for your route in the `controllers` directory.
2. Define your API routes within the new file.
3. Import and use the new file in the `index.js` file located in the routes directory.

### Environment Variable
You should create a `.env.development` file to store the necessary variables for development, while there is no need for it in production mode.

## Running the App
To run the app in development mode, use the following command in Window:

    npm run dev-win
    
In Mac/Linux:

    npm run dev-unix

To run the app in production mode, use the following command in Window:

    npm run start
    
In Mac/Linux:

    npm run start-unix

Make sure you have installed the required dependencies before running the app.

🎉 Thank you for using this Express MVC App Template! We hope it serves as a helpful starting point for your web application development. If you have any questions or need assistance, feel free to reach out to me. 🚀

You can find me on [Facebook](https://www.facebook.com/ltp.2204) for more updates and news about my projects.
