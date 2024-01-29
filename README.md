Q7. Create a sample Angular Application that makes an API call to 'https://jsonplaceholder.typicode.com/posts'  API
and share the data received from the API with different components(present the idea of data sharing between components). 
(Also data needs to be displayed as a grid in UI.)

# Angular Practice Project - "practice"

This Angular project, named "practice," is intended for hands-on learning and exploration of essential Angular concepts. The application showcases the following features:

- Making API calls to 'https://jsonplaceholder.typicode.com/posts'
- Implementing data sharing between components
- Displaying retrieved data in a grid format in the user interface

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Prasamshaaaa/QN.7.git

2. Navigate to the project directory:

   open your command prompt or Windows powershell and navigate to the project directory as:
   
   C:\Users\prasamsha\Desktop>cd practice

3. Install dependencies:
   npm install
   

### Usage
1. Run the application:
    ng serve
2. Open your browser and navigate to http://localhost:4200/ to view the application.


### Features
**API Call**
The application makes an API call to 'https://jsonplaceholder.typicode.com/posts' to fetch sample data.

**Data Sharing Between Components**
The project structure includes distinct components, such as a service '(DataService)' responsible for API interactions, 
a main component '(AppComponent)' handling application initialization, and separate components for data fetching and grid display.

**Display Data as a Grid**
The retrieved data is presented in a grid format in the UI.

**Project Structure**
- src/app/data.service.ts: Angular service for making API calls and sharing data.
- src/app/app.component.ts: Main component that initializes the application and fetches data.
- src/app/app.component.html: HTML template for the main component.
- src/app/app.component.css: CSS styles for the main component.

  **Styling**
  The application includes basic styling for the data table. You can customize the styles in the 'app.component.css' file.


   

