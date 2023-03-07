### 1. SPA (Single-Page Application)
A Single-Page Application (SPA) is a web application that functions on a single webpage, rather than requiring the loading of multiple pages. When using a traditional multi-page web application, every time a user clicks a link or performs an action, a new page is retrieved from the server and loaded in the browser. On the other hand, SPA page is usually updated dynamically as the user interacts with it, and a complete page refresh is usually unnecessary.
SPA is implemented by client-side Javascript famework such as Angular, React, or Vue.

### 2. JIT (Just In Time) vs OAT (Ahead of Time)
They are two different ways to compile Angular applications.
### JIT
JIT compilation is the default method for Angular.
The application is compiled on the client-side just before the application runs in the user's browser.
When a user loads an Agular application, the compilation process occurs within the user's browser and in during this process the Angular templates and components are transformed int JavaScript code that can be executed by the browser.

Pros: faster development cycles and simpler deployment processes as developers can make changes to the application and see the result.

Cons: longer initial loading times as the compilation process occurs in the browser.

### OAT 
AOT compilation is a process used in the Angular framework to pre-compile an Angular application before deployint it into server.
It transforms the application's templates and the components into optimized, browser-ready Javascript code that can be served statically.

Pros: It provies a smaller and more efficient application. The pre-compiled code is optimized for performance which can lead to faster load times. Not like JIT, compilation process does not take place in the browser, which also leads to faster load times.

Cons: Longer deployment cycle and more complex deployment process because the compilation is done before deployment, any changes to the application require build and compilation process again.
