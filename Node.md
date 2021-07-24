---
typora-copy-images-to: upload
---

## Node.js

* HTML/CSS,Java script are used to design front end applications where in the user interacts with the browser at client side. 
* 
* Node.js enables us to interact with the application servers and database servers at the back end
* What is Backend?![2021-05-07 (1)](E:\WhiteHatJr\Module2\Node\2021-05-07 (1).png)
* Backend comprises of servers(http or https ) which renders files to the clients, application /business logic and database servers which have all the data..
* A good Example of this front end and back end is a restaurant
* 
* ![](E:\WhiteHatJr\Module2\Node\2021-05-05.png)

​        In this analogy, the front side of the Restaurant is nothing but our client side(browser ) where they are able to interact with  our website(html,css and java script files)

​        Kitchen where all the recipes are made and served to the front side of restaurant.. similarly all the requests made from browser are sent to server and server sends the responses (files) back to the browser after processing

Finally larder is place where all items required to make the recipe are stored.. similar to the data in our applications(database)

* Usually java script is executed by javascript engines in the browser .. but it exposes business /application logic to the browsers at the client side which is not desirable.. so we can execute some code at the backend and render the pages directly to the browser.. this saves lot of time at the client side , and also does not expose the logic . 

* There are many technologies which are used for backend 

* ![](E:\WhiteHatJr\Module2\Node\2021-05-07 (5).png)

  

  

* We will be using Node.js for the backend. 

* Node is very fast,light weight technology and  also its a java script library.. so we need not learn new technology for the backend.

* Javascript is executed only in the browser but with node.js we can execute it outside the browser in local systems.. and get access to the file systems, networking etc.

* Node.js allows us to use Java script to make desktop applications . We can also make web applications using java script and node.js.. where Java script allows users to interact with websites using drop downs, input boxes  and also get the files from the servers using Node.js

* We can install Node from [Node.js (nodejs.org)](https://nodejs.org/en/)

* Node comes with some native packages  which can be loaded into the application using import/require

* NPM is a node package manager which has modules /packages built by someone and we can use them in our projects. NPM is a large collection of packages or bits of reusable code that saves lot of time. 

* NPM  is bundle with node, so if we install node , we get npm too .. 

* First we should initialize the npm in the location where we want to use the package.. 

  ````````````
  npm init
  This utility will walk you through creating a package.json file.
  It only covers the most common items, and tries to guess sensible defaults.
  
  See `npm help init` for definitive documentation on these fields
  and exactly what they do.
  
  Use `npm install <pkg>` afterwards to install a package and
  save it as a dependency in the package.json file.
  
  Press ^C at any time to quit.
  package name: (karthikeya)
  
  
  ````````````

   this will run a utility and prompts some questions ..  and creates package.json file in the location where the utility is run.

* package.json is a description of all the packages installed . Whenever we install any new package , its entry is added to the package.json file with key name dependencies.. We can install packages using npm

  ``````````````````
  npm install <package name>
  ``````````````````

  

