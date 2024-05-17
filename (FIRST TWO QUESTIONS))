# roadmap-assignment-ONE

# QUESTION 1 :  BLOG ON DIFFERENCE BETWEEN HTTP1.1 VS HTTP2 :

HTTP, or Hypertext Transfer Protocol, is the protocol used for transferring data over the web. It's the foundation of any data exchange on the Web, and its evolution has been crucial in improving the performance of websites and web applications. Two major versions of HTTP are widely used today: HTTP/1.1 and HTTP/2. In this blog we will explore the key differences between these two versions.

# HTTP/1.1: The Traditional Approach
HTTP/1.1 has been the primary protocol for the World Wide Web for over a decade. While it has served the web well, it comes with some limitations, especially in today's highly dynamic web environment. Here are some of the key characteristics of HTTP/1.1:

 # Connection Handling:
 In HTTP/1.1, each request and response is handled over a separate TCP connection. This means that for each resource (like an image, script, or stylesheet) that a webpage needs to load, a new connection has to be established. This can lead to a high number of connections per page, known as the "head-of-line blocking" problem, where one slow-loading resource can delay the loading of other resources on the page.

 # Header Compression: 
 HTTP/1.1 does not support header compression. This means that for each request, the headers containing information about the request (like cookies, user-agent, etc.) are sent in plaintext, leading to higher bandwidth usage and slower performance, especially on high-latency networks.

# Multiplexing:
In HTTP/1.1, only one request can be outstanding on a connection at a time. This leads to a phenomenon known as "head-of-line blocking," where subsequent requests have to wait for earlier requests to complete, even if they could be served faster.

# Server Push: 
HTTP/1.1 does not support server push. Server push allows the server to send resources to the client before the client requests them, which can improve the performance of web applications by reducing the number of round trips needed to fetch resources.


# HTTP/2: The Next Generation
HTTP/2 was developed to address the limitations of HTTP/1.1 and to improve the performance of web applications. It introduces several key features that make it more efficient than its predecessor:

# Multiplexing: 

One of the most significant improvements in HTTP/2 is the introduction of multiplexing. With multiplexing, multiple requests and responses can be sent and received on the same connection simultaneously. This eliminates the head-of-line blocking problem and allows for more efficient use of network resources.

# Header Compression:

HTTP/2 uses HPACK for header compression, which reduces the overhead of sending headers with each request. This results in lower bandwidth usage and faster page loads, especially on high-latency networks.

# Server Push: 
HTTP/2 supports server push, which allows the server to push resources to the client before the client requests them. This can improve the performance of web applications by reducing the number of round trips needed to fetch resources.

# Stream Prioritization:
HTTP/2 introduces the concept of stream prioritization, which allows the client to specify the priority of each resource. This allows for more efficient resource allocation and can improve the overall performance of the web application.


# Conclusion
In conclusion, HTTP/2 represents a significant improvement over HTTP/1.1 in terms of performance and efficiency. By introducing features like multiplexing, header compression, and server push, HTTP/2 allows for faster and more efficient web applications. While HTTP/1.1 is still widely used, especially in legacy systems, the adoption of HTTP/2 is growing, and it is quickly becoming the standard for web communication.





# QUESTION 2 :  BLOG ON OBJECTS AND INTERNAL REPRESENTATION IN JAVASCRIPT:

JavaScript is a versatile and powerful programming language used extensively in web development. One of its core features is the ability to create and manipulate objects. Objects in JavaScript are fundamental to understanding how data is stored, accessed, and manipulated. In this blog , we will delve into the concept of objects in JavaScript and explore their internal representation.

In JavaScript, an object is a collection of key-value pairs. These key-value pairs are often referred to as properties, where the key is a string (or a symbol) and the value can be any valid JavaScript data type, including another object, function, array, string, number, or boolean. Objects allow developers to group related data and functionalities together, making code more organized and modular.

# Internal Representation of Objects
To understand how JavaScript objects work under the hood, it's important to know about their internal representation. JavaScript engines, such as V8 (used in Google Chrome and Node.js), implement objects using various optimization techniques. Here are some key concepts:

# Property Attributes

Every property in a JavaScript object has associated attributes that control its behavior. These attributes comprise of:

# Value: The data stored in the property.
# Writable: A boolean indicating if the property's value can be changed.
# Enumerable: A boolean indicating if the property can be enumerated in a for...in loop.
# Configurable: A boolean indicating if the property can be deleted or if its attributes can be modified.

# Hidden Classes and Inline Caching
JavaScript engines use optimization techniques like hidden classes and inline caching to improve the performance of objects.

# Hidden Classes: 
When an object is created, the JavaScript engine generates a hidden class (similar to a blueprint) for that object. As properties are added or removed, the hidden class may change. Objects with the same structure share the same hidden class, allowing the engine to optimize property access.

# Inline Caching: 
When a property is accessed frequently, the JavaScript engine can use inline caching to speed up the process. The engine remembers the location of the property in the hidden class, allowing for faster lookups in subsequent accesses.

# Prototypes and Inheritance
In JavaScript, objects can inherit properties and methods from other objects through prototypes. Every JavaScript object has a prototype, which is another object from which it inherits properties. This forms a prototype chain.


# Conclusion
Understanding objects and their internal representation is crucial for writing efficient and optimized JavaScript code. Objects are the backbone of JavaScript programming, allowing developers to structure data and functionality in a logical and modular way. By leveraging property attributes, hidden classes, inline caching, and prototypes, JavaScript engines ensure that object operations are fast and efficient.

As we continue to work with JavaScript, keeping these concepts in mind to write better-performing and more maintainable code. Whether we are building simple applications or complex systems, mastering objects will enhance the ability to create robust and scalable JavaScript programs.
