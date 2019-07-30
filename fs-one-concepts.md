# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?

My answer:
 - Enzyme is a testing library for React that adds methods for testing functionality.

Google's answer:
 - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components’ output.
 - Enzyme, created by Airbnb, adds some great additional utility methods for rendering a component (or multiple components), finding elements, and interacting with elements.
 - It must be installed in addition to tools already bundled with CRA.
 - Both Jest and Enzyme are specifically designed to test React applications, Jest can be used with any other Javascript app but Enzyme only works with React.
 - Jest can be used without Enzyme to render components and test with snapshots, Enzyme simply adds additional functionality.
 - Enzyme can be used without Jest, however Enzyme must be paired with another test runner if Jest is not used.

#### 2. What is the difference between dynamic and a static routes?

My answer:
 - A static route never changes, a dynamic route changes based upon the params that compose it.

Google's answer:
 - Static routes render pages that have a hard coded path connected to them. Dynamic routes will render different data based on the parameters passed to the route.

#### 3. What is a JSON API?

My answer:
 - JSON stands for JavaScript Object Notation. API stands for Application Programming Interface and represents the interface through which applications pass data. A JSON API therefore is an API that passes JSON data.

Google's answer:
 - JSON (or JavaScript Object Notation) is a lightweight, easy and popular way to exchange data. ... A lot of the services we use everyday have JSON-based APIs: Twitter, Facebook and Flickr all send back data in JSON format.

#### 4. What is a migration and why would you use one?

My answer:
 - A migration in rails updates the database and schema.

Google's answer:
 - Migrations are a convenient way for you to alter your database in a structured and organized manner. You could edit fragments of SQL by hand but you would then be responsible for telling other developers that they need to go and run them. You’d also have to keep track of which changes need to be run against the production machines next time you deploy.
 - Active Record tracks which migrations have already been run so all you have to do is update your source and run rake db:migrate. Active Record will work out which migrations should be run. It will also update your db/schema.rb file to match the structure of your database.
 - Migrations also allow you to describe these transformations using Ruby. The great thing about this is that (like most of Active Record’s functionality) it is database independent: you don’t need to worry about the precise syntax of CREATE TABLE any more than you worry about variations on SELECT * (you can drop down to raw SQL for database specific features).

#### 5. Explain how to set up a route in React.

My answer:
 - First install the react-router-dom dependencies, then import the necessary react-router components to the component that will use them. Then use the route component with a "to" attribute and specify the path.

Google's answer:
 - The path attribute defines the route URL and component attribute defines the component for this route.

#### 6. When would you use a generate resource over a generate controller?

My answer:
 - Generate resource adds a lot more than just a controller. You would most likely use it when all of the associated functionality is required. Generate controller will just add a controller.
Google's answer:
 - The code from the resource generator will build out the base setup required for the new feature, but it will let you control the implementation.


#### 7. Explain the difference between a controller spec and a request spec.

My answer:
 - A controller spec is specific to testing the functionality of a controller. A request spec is broader and tests not only the controller but also the data being sent.

Google's answer:
 - Request specs allow you to focus on a single controller action, but unlike controller tests involve the router, the middleware stack, and both rack requests and responses.

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?

My answer:
 - React component lifecycle refers to when components in the application are created and called.
 - componentDidMount()
 - componentDidUpdate()
    
Google's answer:
 - When developing in React, every Component follows a cycle from when it’s created and mounted on the DOM to when it is unmounted and destroyed. This is what we refer to as the Component lifecycle, broadly categorized into three parts: Mounting, Updating and Unmounting.
 - constructor()
 - render()

#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?

My answer:
 - JavaScript. I'd like to improve my skills in programming patterns using vanilla JavaScript.
