# reading-13 #

**Why would a developer use local storage for a web application?**
Developers use local storage in web applications primarily for its ability to store data locally within the user's browser. This allows for persistent data storage even after the user closes the browser or navigates away from the page. Local storage provides a convenient way to save user preferences, settings, or other application-specific data without relying on server-side storage. It can improve performance by reducing the need for frequent server requests and can also enhance offline capabilities by enabling the application to work offline and synchronize data later when connectivity is available.

**What information should not be stored in local storage?**
While local storage is convenient for storing small amounts of data, developers should be cautious about what information they store due to security and privacy concerns. Sensitive information such as passwords, authentication tokens, and personal identification information (such as social security numbers, credit card numbers, or personally identifiable information) should not be stored in local storage. Storing such information in local storage could make it vulnerable to unauthorized access or theft, especially if the user's device is compromised.

**Local storage can store what type of data? How would you convert it to that type before storing?**
Local storage can store data in the form of strings. To store other types of data such as objects, arrays, or numbers, they need to be converted to strings first. This conversion can be done using methods such as JSON.stringify() for objects and arrays, or simply using the toString() method for numbers. When retrieving the data from local storage, it needs to be converted back to its original type using methods such as JSON.parse() for objects and arrays, or parseInt() or parseFloat() for numbers.


## Things I want to know more about ##