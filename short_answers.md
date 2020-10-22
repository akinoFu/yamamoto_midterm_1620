# Short Answer Questions
Akino Yamamoto
A01037367
midterm for 1620 October 2020
BCIT


## Q1. Explain what Git and GitHub are. How are they different?
Git is a version control tool that manages source codes while GitHub is a cloud service that provides developers to store code histories and share them using Git. The difference between them is that Git is software and Github is one of the services that host Git repositories. 


## Q2. What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for?
A branch is a Git's feature that allows users to create a copy of a single project and to marge it to the original after modifying. We can create a new branch using commands such as "git branch BRANCH_NAME" or "git checkout -b BRANCH_NAME" when we would like to modify codes without affecting other project members' works.

## Q3. What is the http status code you get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent?
When a resource is not found, the return code is 404 not found, that belongs to 400 client error responses. This code does not mean the status is permanent.


## Q4. What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why?
The h2 element is styled by the internal css with id, but also styled by the style attribute in the h2 element. The h2 will be red because style is overridden in the order of definition.


## Q5. List and briefly describe the parts of a URL
- **Protocol**: displays the protocol used (ex. "http, https")
- **Domain name**: indicates the domain name of requested web server
- **Port**: shows the port used, but not mandatory when the protocol is http or httpd
- **Path to file**: provides the path to the file requested
- **Parameters**: allows webservers to do extra stuff before returning the resource
- **Anchor**: allow viewrs to jump a specific location of a page using #


## Q6. What is an http header? Provide examples of three http header fields and briefly describe what each does
An http header is additional information sent with http request or response. Examples of three http header fields are as follows:
- from: provides an email address of a user who controls the requesting user agent
- host: contains the domain name of the server, used in a request context
- refer: holds all the URLs that were used when the current web page is requested


## Q7. Describe the CSS box model? From inside to outside what are the different parts of the box model?
The CSS box model is a concept that every element is displayed as a rectangular box.
The differnt parts are content, padding, border and margin, from inside to outside. 


## Q8. Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each
- **descendant selectors**: selects the elements that is descendent of a specific element (ex. p a {}) 
- **parent-child selectors**: selects the directly child elements of a specific element (ex. p > a {})
- **adjacent sibiling selectors**: selects the sibiling elements that directly next to a specific element (ex. h1 + p {})
- **general sibiling selectors** : selects all the sibiling elements of a specific element (ex. h1 ~ p {})


## Q9. Will these two paragraphs appear on two separate lines? Why?
Yes, they appear on two separate lines because a p element is a block level element.


## Q10. Identify and explain two of the errors that exist in the code snippet below. 
The text for hyperlink should be placed between <a href="....."> and </a>.
In addition, an "a" element does not have "title" attribute.
