 ## 1. Provide an overview and description of a standard source control process for a large project 

The standard source control process refers to the process of tracking and managing code within a project. 

This process is beneficial because it allows users to edit code stored on their personal computer while the same code remains unaltered in their repository.

 Large groups utiliizng standard source are best served using the Gitflow design which consists of a branching system in which  master and the develop branch are the central branches, and  feature, release, and hotfix branches are supporting branches. 

 The master branch reflects the official release history of the project. 
 
 The development branch is a complement to the main branch that reflects the latest changes of a project. A member from the project would create this branch, and the rest of the team would individually clone the branch and make their own changes.  The creation of the development branch is needed so the original code in master branch can remain untouched and depoloyable as  developers expirement with the development branch. 
 
The feature branch is the child branch of the latest develop branch.Feature branches do not directly interact with the master branch and are only merged into the develop branch when a feature is complete. 

After the feature branch receives a sufficient amount of features required for release, a release branch is then forked from the develop branch. The release branch is essentially to support preparation of a new production release. Tasks related to production release such as bug fixes and documentation generation go into this branch. 

The hot fix branch is used in preparation of new production releases and forks directly off of the master branch. When bugs are identified, a hot branch is created so a team can quickly fix and patch the bug then merge the branch back into master. By creating a dedicated branch for bug fixes, a team can handle bugs without interfering with the Git workflow.


Source: 
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow 

https://nvie.com/posts/a-successful-git-branching-model/
 

## 2. What are the most important aspects of quality software? 


The seven aspects of quality software are:
Reliability
Understandibility
Modifiability
Usability
Testability
Portability
Eficiency
 
These seven aspects are key in order for any software program or source code to be deemed high quality.  

Reliability entails a program should behave as expected and consist throughout each use.Software should be reliable and errors should be nonexistent or scarce.Additionally,users should have confidence the product they're using will work correctly.  

Understandibility encompasses the structure of source code. Code should always be clear, well organized, and simple. At first glance, it should be easy to acertain what the code is doing and clear code is a reflection of the developers' understanding. In addition to this, a developers' source code performance should be predictable and not deviate from its original purpose.  

Modifiability refers to the modification of a system. A program should be easy to edit and/or change without having to change many lines of code. Plug in points where an application can be used with different elements is also expected. 

Usability entails the use of the software product. The product must be must be easy to set up and use, and users should have a seamless experience when using the program. Users should also be able to navigate through the program without needing outside sources for clarification on functionality. 


Testability of software must be easy and verifiable and testing metrics should be observeable, controllable and deployable. 


Software should be able to be used in different operating systems and reused across different programs and environments. Reusability is key. 


Efficiency attests to the speed and efficency of a program. The program must be fast, conscious of memory usage, battery efficient, and self reliant.  



 
Source: 
https://www.silasreinagel.com/blog/2016/11/15/the-seven-aspects-of-software-quality 

 

 
## 3. Outline a standard high level structure for a MERN stack application and explain the components 

The Mern stack is a tier of 4 technologies - MongoDB, Express, React, and Node, that come together to create a full stack application. 


React.js is a powerful Javascript library that allows users to build complex interfaces using simple components. React also updates and renders data in HTML as data in an application is changed.  Essentially, React is the view layer of an MVC application. 


MongoDB is a document database that stores data such as user profiles, comments, uploads, and more.  

Express is a Node.js web application that provides features for mobile and web applications and also handles HTTP requests and responses. 

Node.js is Javascript runtime environment in which Express is run from.  

React is at the top of the MERN stack tier and handles forms, error handling, events, lists, and more. The user of a MERN stack application interacts with React UI components while in the back end, Express JS runs on Node.js and handles HTTP requests and responses. Any changes made to data is sent through an HTP request to the Express server, which is then acquired from the MongoDB server if necessary. The data is then returned through to the front end to React, which is then viewed by the user. 


Some benefits of the MERN stack is that  all code across the tiers are written in Javascript,  which eliminates the need for context switching and has the added bonus of being the sole language users need to learn in order to operate the stack.

Other benefis include the reusability of React components, easy scalability of Node js, MongoDBs' powerful data manaagement system, and Express js' flexibility and performance.  

Source: 
https://www.mongodb.com/mern-stack 

https://blog.hyperiondev.com/index.php/2018/09/10/everything-need-know-mern-stack/#:~:text=The%20Benefits%20of%20the%20MERN,no%20need%20for%20context%20switching.
 

## 4. A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project? 

Members of the team must have both hard and soft skills in order to succesfully decelop the website for the small business. 

Hard skills, or technical abilities, needed to complete the website are at minimun, HTML, CSS, and Javascript. HTML is the standard markup language used to create pages/page structure in the browser, and CSS is used to style the HTML structures and dictates how HTML should displayed within a page. Javascript is needed to turn the small businesses's website from a static website to a dynamic one. Javascript will allow customers to interact with features while navigatinh through a smooth experience making bookings, inquiries, and more. 

A front end framework such as Angular, React, or View is a required hard skill if the small business intends to store user information. 


In the Agile methodology, members of a team are expected to work harmoniusly on a project within small incremenets and must have the ability to quickly respond to change. Thus, soft skills such as team work, creativy, adaptability, open communication,  organizational skills, and trust are soft skills required to deliver high quality services to clients within a quick time frame. 

However, there are caveats. If a team is lacking in tech skills such as Javascript, but are creative, they can use certain CSS properties to handle user interaction. Likewise, if creativiy is a lacking soft skill, React components that have been created by other developers can be reused in order to make the application more appealing. 

Source:
https://www.atlassian.com/agile/teams 

 


## 5. With reference to one  of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges 
My portfolio assignment was a project that required knowledge of CSS and HTML. Knowledge of JS was optional, as the portfolio website only needed to be a static website that rendered CSS and HTML to the screen. HTML was used to build the basic structure of the website  and CSS was used to style elements and dictated how HTML should displayed within the portolio page. 

In order for the project to successfully finish within the deadline, soft skills such as time and project management, adaptability, and  and communication were crucial. 

Time and management skills were vital inorder to complete my project before the deadline. I needed to allocate a certain amount of to dedicate to each tech stack as well as documentation required for submission. Without these soft skills, I could have easily spent too much time on one area of my project such as CSS, while failing to fulfil other requirements such as documentation. 

Adaptability is a soft skill that complemented my time management skills. Once the deadline became close, I needed to adapt my expectations and abandon oroginal styling plans so  I could focus on docunentation and code organiation. Had I not been able to adapt, my projects' deadline would not have been met. 

Creativity was also a soft skill needed in order to create a portfolio that was orginal and reflective of my personal brand. 

Lastly, open communication was important when navigating through hurdles and roadblocks I faced when coding. I needed to be able to openly communicate with my instructor as well as cohort when I needed help so that I could use my time wisely instead of spending large amounts of time solving a problem.  
 

## 6. With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature 

For my rails application, hard skills neeeded to succesfully build  my application were Ruby, HTML, CSS, and PostgresQL, and Ruby on Rails. 


Knowledge of Ruby on Rails was required to build the model, view, and controller layers of my application. My application heavily relied on the MVC model in order to define essential components in the application, display information to the user, and persist data to the database.

Ruby was needed to define classes,methods, forms, string interpolation, and more. 

HTML and CSS were needed in order to design the front end of the application. 

Postgresql or knowledge of of a database was a hard skill needed to be able to create, persist, and retrieve user info from the database. 

In reference to soft skills, time and project management were again essential skills, perhaps even more so because there was a heftier workload to complete. Communication was also important, especially at the beginning of the project because of the learning curve necessary to work with Rails. 

Problem solving was a reoccuring and necessary soft skill. Error messages are extremely common within the Rails framework and it would would have frustrating to ask for assistance from cohort and my instructor every time I encountered a problem. Utilizing Google, Stack overflow, and Ruby on Rails documentation to fix bugs was  a huge time saver and great learning experience.

Changes and improvements made to similar projects of a similar nature would be to build a more solid foundation of CSS prior to the application. My Rails application was a two way marketplace that was dynamic wuith user interaction. In order to accomodate this, more styling of CSS components and use of more CSS properties were needed in the absence of Javascript. Since I was not yet strong in my CSS skills, it took a week for me to complete the front end of my application, and I was unable to add more features due time restrictions. Having a more solid foundation of CSS would be a major improvement for future projects of a similar nature.


## 7. Explain control flow, using an example from the JavaScript programming language. 

Control flow refers to the order in which a computer executes statements. Below are examples of control examples from the Javascript programming language. 


**Block statemenents** are used to group statements and are commonly used in for, while, and if loops.  

Ex: 

let count = 0 
while (count < 10 ) {
    console.log (count)

prints: 0 1 2 3 4 5 6 7 8 9 



**If else statements** are statements which execute a logical conditon when the if is true,and if false, the else clause is executed. 
Example:

let name = "Linda";

if (name) {
    console.log ("It's true")
}   else {
    console.log ("I's false")
}

prints: true

**Falsy Values** evaluate to fales when 0, undefined, Nan, false, null, or is an empty string. 


if (0) {
    console.log ("It's true)
} else {
    console.log (It's false)
}

Output: It's false



**Switch statement** are another type of if statement that allows users to compare one value to other values. 

Ex:
let favPie = "Pumpkin"

switch
    case "blueberry":
        console.log ("You like blueberry pie.")
    case "pumpkin"
        console.log ("You love pumpkin pie.")
        break  
    default: 
        console.log ("You like some other pie.")
}

prints: You love pumpkin pie. 


**Throw statement** are used to throw an exception. 

Ex:
 throw { {message: "Oops! Something went wrong!"}


**Try catch statments** prevent a user's program from crashing 

Ex:
try {
    throw "minor error"
} catch (error) {
    console.log (error)
}

prints: minor error 




Source:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling

https://developer.mozilla.org/en-US/docs/Glossary/Control_flow 

 

## 8. Explain type coercion, using examples from the JavaScript programming language 

Type coercion is the conversion of one value type to a different type. 
Some examples of this include:
Converting a string to a number.
Converting a number to a string. 
Converting a boolean to an object. 

When type coercion occurs, Javascript complier coerces one value to another.


Implicit coercion occurs when Javascript automatically converts between different different data types. This can become problematic since the concept of truthy and falsy may not always yield a predictable result during implicit coercion.   

For instance, in Javascript, (10 == "10") would print a true value although the string 10 and number 10 are technically not equal values. However, using the  "triple equals operator (====)" rather than the strict equals (==) can solve this issue. For instance, (10 === "10") would be render a false value which is expected, and more accurate. This occurs because the stricter equality operator doesn't trigger implicit type coercion, while the loose equality operator handles both type coercion and comparison. 


Explicit coercion,or type casting, is when a developer convert chooses to convert between types.Javascript has built in methods available for explicit coercion. parseInt() and parseFloat() are global methods given to convert data types to numbers, the string() global methos is used to convert data types to strings, and the Boolean() global is used to convert data types to true or false values. 



https://www.freecodecamp.org/news/js-type-coercion-explained-27ba3d9a2839/ 

https://medium.com/better-programming/implicit-and-explicit-coercion-in-javascript-b23d0cb1a750
 

## 9. Explain data types, using examples from the JavaScript programming language 


Null is a explicit value you give to a piece of data when you want it to have no value. Null is also a primitive type

**Example:** let myData = null 


Undefined is a primitive data type similar to null and indicates theres no value because it not been given an explicit value yet. 
By default, when we declare a variable, it has a value of undefined. 


**Example:** 
let myData

console.log (myData)

Prints: undefined

Interestingly enough, Javascript is the only programming language that has these two concepts. 

 Javascript also has five other primitive data types (an object with no methods):
 **Booleans** have a value of either true or false. 
 
 **Example:** 
let age = 21;

if (age >=18) {
    console.log {"you can drink"}  
}   else {
    console.log("sorry, you can't drink.")
}

prints: sorry, you can't drive. 

 **Numbers** are numeric data types that include integers, floats, doubles, and Bignums.

  **Integer numbers are whole numbers:** 
  5

  10

  200

  4

  **Float are fractions represented as decimal values :** 
 2.5

 10.2

 4.4

 3.6


 **Strings are a sequence of alphabetical characters:**
"occupation"

"age"

"year"

 **BigInt is used to denote arbitrarily large integers and is created by either appending 10n at the end of an integer or calling the Big Int() function.**

const myBigInt = 66759494941n

cont myString = BigInt("66759494941n")

 **Symbols are created by calling the Symbol function and produce an anonymous value.**  

const mySymbol = Symbol('a description')


**Objects are data structures that containers that store data instructions for working the data.  ** 

Example: 
let person = {
    name: "Linda", 
    profession: "Programmer", 
    age: 31
}

console.log (person)


**Functions are a piece of code that can be called on its own or by other code. When calle, functions pass arguments as inputs and have the option of returning a value**


const answer = sum(4,4)
console.log (answer)

function sum(x, y) {
    return x + y 
}

prints: 8 



https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures 


## 10. Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language

In Javascript, arrays have the same behavior as objects. Because of this, arrays also have various methods that can be used to manipulate them. Below are commonly used array methods.

The filter method will return a new array that has contains all elements that have have passed a certain criteria.


 **Example:** 

let numbers = [2,3,5,6,7,8]

let lucky = number.filter(function(number) {
    return number > 8

});

prints: 2, 3, 5, 6, 7


The spread operator method permits access to iterable objects within an array. 

**Example:** 

let lindaColors = ["pink", "grey"]
let samColors = ["blue", "black"]

let allColors = [...lindaColors]

console.log (allColors) 
(Here, im spreading the lindaColors array into the allColors array)

prints: "pink", "grey" 


The spread operator also allows users the option to add element 
**Example:** 
let allColors = ["orange",...lindaColors,"purple"]
console.log (allColors)

prints: "orange", "pink", "grey", "purple"  

The map method creates a new array that contains results from calling a function each element in the array. 

**Example:** 
let myArray = [2, 4, 5, 1];

let map = myarray.map(x => x * 4);

console.log(map);
prints: [8, 16, 20, 4]


The slice method returns a subset of elements beginning from the specifed index number and optionally concluding at a specified index number in the array. 


**Example:** 
const colors = ['red', 'blue', 'orange', 'purple'];

console.log(colors.slice(3));

prints: 'purple'


The split method splits a string into an array of ordered substrings and gives back a new array.

**Example:** 

document.cookies.split (;)-  canb be used to seperates the key value pairs with a colon. 



In Javascript, it is common to create a copy of data so the original data data can stay in its original, unchanged, state while a copy can be changed without affecting it. In order to do this, a user must initiate a new variable with the same value by using either deep or shallow copying. A shallow copy's sub values can stull be connected to its original, whereas a deep copy contains values of the new variable that are removed from the original variable. The slice method is an example of the shallow copy process.



https://www.freecodecamp.org/news/copying-stuff-in-javascript-how-to-differentiate-between-deep-and-shallow-copies-b6d8c1ef09cd/#:~:text=A%20deep%20copy%20means%20that,into%20how%20JavaScript%20stores%20values. 

https://alligator.io/js/filter-array-method/
 

 

## 11. Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language 

 
In Javascript, objects can be manipulated through object declarations, constructors, and methods such as the key, value, entry, and assign method. 

Object declarations can be used to create an empty object by using either of the two syntax below: 

let member = new Object(); 
let member = {};

Objects can by using a constructor function and the instance variable new: 

function Member (name, age, occupation) 
    {
    this.name = Juan;
    this.age = 35;
    this.occupation = doctor;
}

console.log(Member)
prints: 
Member 1 = {
    name: "Juan",
    age: 35,
    occupation: "Doctor"
}


The key method allows users to access object properties using either dot or bracket notation. 

**Bracket notation example:** 
console.log (Member["name"]) 
prints: "Juan"


**Dot notation example:** 
console.log (Member.name) 
prints: "Juan"


The value method allows users to return values of an object in the form of an array. 

**Example:** 

let member = {
    name = "Juan",
    age = 35,
    occupation = "Doctor",
}

let member = Object.value(member);

console.log(member)

prints: 
["Juan, 35,"Doctor"]


The Object.entries() method allows user to create an array that holds the key/balue pairs of their object.

**Example:** 

let member = {
    name = "Juan",
    age = 35,
    occupation = "Doctor"
}

let member = Object.entries(member);
console.log(member)
prints:
[["name" = "Juan", "age" = 35, "occupation" = "Doctor"]]



The Object.assign() method is quite similar to the spread operator and allows the user to combine objects together. 

let member = {
    name: "Juan",
    age: 35,
    occupation = "Doctor"
}

let memberNewInfo = {
    city: "Houston",
    state: "Texas"
}


let combineObj = Object.assign(member,memberNewInfo)
console.log(combineObj)

prints: 
{
    name: "Juan",
    age: 35,
    occupation: "Doctor,"
    city: "Houston", 
    state: "Texas"
}




https://medium.com/infancyit/javascript-object-manipulation-5d1145cf06ef#:~:text=An%20object%20can%20be%20created,and%20value%20can%20be%20anything.

## 12. Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language 

JSON (Javascript Notation)is an object that can be manipulated using the Javascript helper method JSON.parse(). This method takes a string and converts it into to a Javascript object. This method is helpful because anything stored in local storage gets serialized( converted into a string), and in order to deserialize from string to object a user would need to use the JSON.parse method. 


 **Example:**  

let me = '{"name": "Linda", "age": 31, "country": "Australia "}';

 {console.log(JSON.parse(me)}
 prints: 

name: Linda
age: 31 
country: Australia
 
 

## 13. For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and clas 

 class Car {  // a declared class named Car 
  constructor(brand) { // defines the object type, brand
    this.carname = brand; // creates a new instance 
  }
  present() // calls the present method to see if a function exists. 
    return 'I have a ' + this.carname; // returns "I have a brand"
  }
}

class Model extends Car {  // a declared class named Model that inherits the car attributes. 
  constructor(brand, mod) //defines the object type, brand and mod
    super(brand); //calls the parent function of brand
    this.model = mod; //creates a new instance 
  }
  }
  show() { // calls the show method.
    return this.present() + ', it was made in ' + this.model; 
  }
}

let makes = ["Ford", "Holden", "Toyota"] // defines a variable names make 
let models = Array.from(new Array(40), (x,i) => i + 1980) //defines a new class named models and uses the array method from to create a copy 
 
function randomIntFromInterval(min,max) { // min and max included // creates a new function named  randomIntFromInterval that takes two arguments of min and max
    return Math.floor(Math.random()*(max-min+1)+min);// returns a floating point after finding a product. 
}

for (model of models) { //iterates through the models 

  make = makes[randomIntFromInterval(0,makes.length-1)]//  leaves off the last element in an arrray 
  model = models[randomIntFromInterval(0,makes.length-1)]// leaves off the last element in an arrray 
    
  mycar = new Model(make, model);
  console.log(mycar.show())
}


