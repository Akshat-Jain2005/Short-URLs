Prerequisites :-
Node.js and npm installed

Tree of my project :-
url-shortener/
├── app.js
├── urls.json
├── views/
│   └── index.ejs
├── public/
│   └── css/
│       └── style.css   
└── package.json        

Sequence of code:-
npm init -y
npm install express
npm i ejs
npm i body-parser

Copy The files as it is 

Start Server by :-
node app.js

Open in Browser :-
Go to: http://localhost:3000

Features of this project:-
This is the Short-URL project
Shortens long URLs: Users can submit any long URL and receive a unique, short link.
Homepage form: Simple form on the homepage for URL submission.
Short URL generation: Each shortened URL uses a unique 6-character alphanumeric code.
404 error handling: Invalid or non-existent short URLs show a custom 404 error page.
Click tracking: Each time a short URL is used, the click count is incremented.
Clean slate on restart : If configured, all shortened URLs are cleared each time the server restarts.
Persistent storage: All URL mappings are saved in a local urls.json file using the Node.js fs module.


This is my very first Node js project, and I have invested a significant amount of time and effort into building it from the ground up. Throughout the development process, I focused on understanding the core concepts of server-side JavaScript, Express.js routing, EJS templating, and file-based data persistence. I hope you will like this project.Your feedback and suggestions are most welcome, as they will help me continue to improve and expand my skills in Node.js and web development!
Thank You 
