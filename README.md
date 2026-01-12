# Lab 12.1 

By Uchenna Williams 

## Relection

res.send vs res.sendFile: res.send() is used to send data such as strings or JSON directly in the response, while res.sendFile() is specifically for sending files. When serving HTML pages, res.sendFile() is the better choice because it handles file delivery properly.

Why the path module is necessary: The path module ensures file paths work correctly across different operating systems. Using a relative path like public/index.html can break if the server is started from a different directory.

Adding a third page: To add a menu page, I would create a menu.html file inside the public folder and add a new GET route (e.g., /menu) in server.js that uses res.sendFile() to serve it.

https://github.com/unw10181/lab12.1