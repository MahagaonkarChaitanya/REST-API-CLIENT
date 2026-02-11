# REST-API-CLIENT

**COMPANY**: COTECH IT SOLUTIONS

**NAME**: Mahagaonkar Chaitanya Chandrakant

**INTERN ID** : CTIS3602

**DOMAIN**: JAVA PROGRAMMING

**BATCH DURATION** 4 WEEK

**MENTOR NAME**: NEELA SANTOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS
In this task, I developed a Java-based REST API client application that interacts with the public GitHub REST API to retrieve and display user profile information in a structured format. The main objective of the task was to demonstrate how to send HTTP requests, handle HTTP responses, and process JSON data within a Java application using built-in libraries.

The application uses the java.net.http.HttpClient class, which is available in Java 11 and above, to create and send an HTTP GET request to the GitHub API endpoint. The program dynamically constructs the API URL by appending a specific GitHub username (in this case, "JakeWharton") to the base URL https://api.github.com/users/. After building the request with the appropriate headers (including the Accept header for GitHub API versioning), the client sends the request and receives the response as a string.

The program checks the HTTP status code to ensure that the request was successful (status code 200). If successful, the JSON response body is passed to a custom method called parseAndDisplay. Instead of using an external JSON parsing library, I implemented a simple manual parsing approach using string manipulation techniques. A helper method named extract retrieves specific values such as login, name, bio, public repository count, followers, and following by splitting the JSON string based on predefined patterns.

Finally, the extracted data is displayed in a clean and formatted console output, making the information easy to read. Basic exception handling is included to manage potential runtime errors such as network failures or parsing issues. Overall, this task demonstrates practical knowledge of REST API consumption, HTTP communication, JSON data handling, and structured output presentation in Java.

# OUTPUT OF THE TASK

