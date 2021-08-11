# John Robison's Portfolio

## Overview
John Robison's Portfolio is a full-stack application with the goal of effectively communicating my skills to potential employers. The application will have the following features:
<ul>
  <li>Successfully incorporate CRUD for the Book Screens</li>
  <li>Utilize React-Bootstrap to create a smooth, minimalist design</li>
  <li>Full functional and deployed front-end and back-end</li>
  <li>13 screens, according to the following specifications</li>
  <ul>
    <li>Home Screen: Introduce John Robison and the general application to the user</li>
    <li>Projects Screen: List my relevant projects, including the following: </li>
    <ul>
      <li>Community Table</li>
      <li>Heal U</li>
      <li>Velocity</li>
      <li>Drone Wars</li>
    </ul>
    <li>Selected Writing Samples Screen: List key relevant writing samples to demonstrate my ability to communicate complex ideas</li>
    <ul>
      <li>On the Origin of Evil</li>
      <li>Prime Numbers and Post-Modern Art</li>
      <li>Rational Dragons</li>
    </ul>
    <li>Favorite Books</li>
    <ul>
      <li>Examine Book</li>
      <ul>
        <li>Edit Book</li>
      </ul>
      <li>Add New Book</li>
      <li>Filter by:</li>
      <ul>
        <li>Mathematics and Physics</li>
        <li>Computer Science</li>
        <li>Social Sciences</li>
        <li>Science Fiction</li>
        <li>Entrepreneurship and Finance</li>
        <li>Other Forms of Media (films, televsion shows, etc.) </li>
      </ul>
    </ul>
  </ul>
</ul>

The greatest challenges I expect to face will be using Ruby on Rails; we only just started learning rails, so I admit I have certain trepidations about building a full-stack application with this framework. That being said, I'm super excited to use this project as an opportunity to really understand the nuts and bolts of rails and determine exactly how I can most effectively use this tool to process data! Given my concern with Ruby, I also think time will pose a significant issue. With only four days to actually build this application, it isn't enough to simply "work harder." Rather, I will need to be <em>meticulous</em> in my planning to ensure no moment is wasted.

## MVP

### Server (Back-End)
The server will have the following minimal functionality:
<ul>
  <li>Have a <strong>RESTful JSON API</strong></li>
  <ul>
    <li>Build a Ruby on Rails server, exposing RESTful JSON endpoints</li>
    <li>Build a database with at least 3 tables</li>
    <ul>
      <li>There must be at least one association between your tables (1:m <em>or</em> m:m)</li>
    </ul>
    <li>Utilize <strong>Rails</strong> to define models for interacting with the database.</li>
    <li>Implement working generic controller actions for Full CRUD (index, show, create, update, delete) between your non-User tables</li>
  </ul>
</ul>

### Client
The front-end will have the following minimal functionality:
<ul>
  <li>Have a working, interactive <strong>React</strong> app, built using npx create-react-app</li>
  <ul>
    <li>Have at least 8 separate, rendered components in an organized and understandable React file structure.</li>
    <li>Utilize functional or class React components appropriately</li>
    <li>Utilize state and props in your components efficiently</li>
    <li>Use <em>only</em> React (no vanilla js)</li>
  </ul>
  <li>Consume data from <strong>Ruby on Rails API</strong> and render this data within the components.</li>
  <li>Utilize <strong>React Router</strong> for client-side routing</li>
  <li>Demonstrate Full CRUD actions (index, show, create, update, and delete) on the front end.</li>
</ul>

### Styling 
<ul>
  <li>Be styled with CSS.</li>
  <li>Use Flexbox or Grid in layout design.</li>
  <li>Implement 2 media queries for responsive design on 2 screen sizes (including desktop).</li>
</ul>

### Linting
<ul>
  <li>Indent properly.</li>
  <li>Utilize high-quality, semantic variable names.</li>
  <li>Follow camelCase, snake_case, or kebab-case convention.</li>
  <li>Remove unnecessary boilerplate React files and code.</li>
  <li>Remove all console.log() statements and commented out code that are not direct comments on present code blocks.</li>
</ul>

### Deployment
<ul>
  <li>Deploy fully-functional front-end via Netlify.</li>
  <li>Deploy back-end via Heroku.</li>
  <li>Deploy early and often.</li>
</ul>

### Procedural
<ul>
  <li>Initialize a <strong>git repo on Github</strong>, with a link to the hosted project.</li>
  <li>Have <strong>frequent commits</strong>, making a <em>robust</em> commit history at least every day (75 commits minimum).</li>
  <li>Use effective and safe <strong>branching and merging</strong> processes.</li>
</ul>


### Libraries and Dependencies
| Libraries | Dependencies |
| ------ | ----------- |
| React | A front-end JavaScript UI for building a component-based architecture  |
| React Router | A standard library for routing components in React |
| React Bootstrap | A library for styling react components using the Bootstrap design philosophy |
| Axios | A standard library used to import data from an API |
| Rails | A web-application framework which allows you to create a database using the MVC pattern |

## Client (Front End)
### Wireframe
https://www.figma.com/file/yQY4X4qz7VjwdeVKydyjHp/Project-4---Robison-Portfolio?node-id=0%3A1
### Component Tree
This is how I expect my React file structure to look:
```

client
|__ screens/
  |__ Homepage.jsx
  |__ Projects.jsx
  |__ Writing.jsx
  |__ Books.jsx
    |__ScienceFiction.jsx
    |__Mathematics.jsx
    |__SocialScience.jsx
    |__SocialScience.jsx
    |__Business.jsx
    |__OtherMedia.jsx
  |__ BookDetail.jsx
  |__ BookEdit.jsx
  |__ BookNew.jsx
|__ layout/
  |__ Header.jsx
  |__ Footer.jsx
|__ services
  |__filter.js
  |__apiConfig.js
  |__books.js
 
```
### Component Architecture

## Server (Back End)
### ERD Model
https://app.diagrams.net/#HrobisonJohn%2Fcoursera-test%2Fmain%2Fsite%2FERD%20Diagram%20Robison%20Portfolio.drawio

## Time Estimates
| Task | Priority | Estimated Time (Hours) | 
| ------ | ----------- | --------- | 
| Planning and Ideation | H | 6 |
|  | N | N |
| N | N | N |
| N | N | N |
| N | N | N |

