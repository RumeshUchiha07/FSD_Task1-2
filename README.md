# FSD_Task1-2
i have uploaded the task given by our staff

Task 1:

  Question 1:
    Overview:
      You have a local server running on localhost:3000 using Express.js.
      The server has different routes like /home and /about that show specific messages.
    Home Page (/home):
      When you go to http://localhost:3000/home, you see "Welcome to the Home Page!".
    About Page (/about):
      When you go to http://localhost:3000/about, you see "This is the About Page."
    Server Functionality: 
      The server responds based on the URL you enter. Different paths (e.g., /home, /about) display different messages.
    Localhost and Port:
      "localhost" refers to your computer. The number 3000 is the port where the server is running.
    Summary:
      Your local server is working as expected, showing simple text messages for different routes like /home and /about when accessed in the browser. The setup is         good for testing before deploying to a public server.

      
  Question 2:
    An Express.js server that serves various pages and includes a greeting route that displays a message based on the query parameter. Your code works by listening 
   on port `3000` and handling different routes (`/home`, `/about`, `/contact`, and `/greet`).
    For the `/greet` route, the query parameter `name` is passed through the URL, like this:
    - Example URL: `http://localhost:3000/greet?name=Rumesh`
    - Output: `Hello, Rumesh!`
    If the `name` parameter is not provided, it defaults to "Rumesh," as in your code:  
    `const name = req.query.name || 'Rumesh';`
    The other routes are simple text responses:
    - `/home`: "Welcome to the Home Page!"
    - `/about`: "This is the About Page."
    - `/contact`: "Contact us at contact@example.com."
    Make sure you run the server with the command:"node server.js"
    Also, the required `express` package can be installed using the following command:"npm install express"

Task 2:


  The PDF file I have uploaded contains a Full Stack Development Task (Task 2). It includes two main programming exercises:
  Basic HTTP Server with Routes and Methods (GET, POST, PUT, DELETE):
  A Node.js server is created using the http module.
  Different routes are defined (/, /about, /api/data) with corresponding HTTP methods:
  GET for retrieving data.
  POST for submitting data.
  PUT for updating data.
  DELETE for deleting data.
  The server checks the incoming requests and responds accordingly, with a "404 Not Found" message for invalid routes.
  File Upload Server using Express and Multer:
  
  An Express server is created for file uploads using the multer middleware.
  The storage engine is configured to save files in an uploads/ directory with a timestamped filename.
  The server handles a POST request at /upload where users can upload image files (restricted to JPEG, JPG, PNG, GIF).
  If the upload succeeds, the server sends back the uploaded file's name, and if it fails, appropriate error messages are sent.
  These tasks demonstrate the use of HTTP servers, file handling, and middleware integration in a full stack environment.
