Creating a Web-development application using NodeJs.

Node Farm is a web-based application which simply lists and tracks the availabilites of various vegetables and farm-based products along with their prices imported from different locations. This project aims to provide a convenient and efficient solution for farmers, distributors, and consumers to monitor the availability of vegetables and farm products.


To start, I set up a server on the local host at 127.0.0.1:8000 to handle incoming requests from clients. Next, I used the readFile module in Node.js to import the data available in JSON format into variables. This data includes information about vegetables and farm-based products that are available in the Node-Farm, such as their prices and the countries they are imported from.
With the server set up and the data imported, I proceeded to create an overview page on the server. This page provides a summary of all the items available in the Node-Farm, giving visitors a quick glimpse of the product offerings. Additionally, I implemented a separate page that displays detailed information about a specific product/item. Users can access this detailed page by clicking on the "details" button or link associated with each product on the overview page.
By structuring the server and web pages in this manner, I aimed to provide an intuitive and user-friendly experience for visitors to the Node-Farm website.

I used a lot of predefined modules and also created some user defined modules/packages which is then imported to our main javascript file.
Modules Name :
1. fs module : It stands for File System module. It allows us to read, write, rename, delete and update any file.
2. http module :The http module in Node.js is a core module that provides functionality to create HTTP servers and make HTTP requests. It allows us to handle incoming HTTP requests, send HTTP responses, and interact with HTTP clients.
3. url module: The url module in Node.js is a core module that provides utilities for working with URLs (Uniform Resource Locators). It allows you to parse URLs, extract their components, and perform various operations on them.
4.Slugify :The slugify module is not a built-in module in Node.js, but it is a popular npm package that can be used to convert a string into a URL-friendly slug. A slug is a URL-friendly version of a string that typically contains only lowercase alphanumeric characters, dashes, or underscores.


