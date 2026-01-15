# React:
- Is a JS library for building dynamic and interactive UIs4
- currently mostly used front-end development 
- When a webpage is loaded, browser takes the HTML code and converts it into tree like structure called DOM
- This allows us to use Javascript and change page content
- We can use plain java script(vanilla js), with this it will be quite complex to manage
- Using React we can write small reusable components, then react will take care of creating and updating DOM.
- Components help us to write reusable, managable and better organized code.
- App is the root component, we can create more components
-  Vite+React then Next+React
- ### Project Structure:
1. Index.html - Entry point of our application
2. Package.json - dependencies, title and packages etc
- For react componenets the entensions is tsx -> TS + TSX(HTML like structure means "const element = <h1>Hello World</h1>;") 
- Most react developers are using Pascal case(always first letter starts with Captial letter)
- JSX -> Js + XML
- Vite under the hood always monitors the code, when ever we make any change in the code it will automatically refresh the page and updates the DOM.
- ### How React works:
- With the Componenets we have in the prj, React creates a Virtual DOM which is diff from actual DOM
- It creates VDOM with the componenst, each component as a node in VDOM
- When we make a change in the React component, it will updates the corresponding node in the VDOM.
- Then it compares with the actual browser DOM and updates those nodes only in actual DOM.
- ### React Eco System:
- React - Library -  like a tool
- Angular and Vue - Frame work- like a tool set
- Diff b/w Library and Frame work:
-  ![alt text](image-5.png)
- ### Building Components:
- The react component can only return one element
- So instead of adding a new element to wrap everything we can use some thing called Fragment which is an Fragment tags(<Fragment><Fragment/>), this tag will not be added into the DOM.
- Instead of Fragment we can also use an EMPTY tags means a fragment only
- #### Rendering Lists:
- ![alt text](image-6.png)
- If we wanted to dynamically add the data in component, we can use js right but we need to wrap it in {} braces in JSX.
- In a list or any items or tags, react needs a unique key to keep track of the element 
- ![alt text](image-7.png)
- We can add a unique Key like above
- ###### Conditional Rendering:
- ![alt text](image-8.png)
- ![alt text](image-9.png)
- We can use conditional 'AND' for conditional rendering.
- #### Handling Events:
- 




----------------------------------------------------------------
- Componenets: Building blocks of every react app and they are reusable
- ![alt text](image.png)
- Every components is Js function that returns markup(means Js + XML)
- They don't return HTML markup, return JSX markup means 
- JSX stands for JavaScript XML.
- Js fn retuns one thing
- ![alt text](image-1.png)
- ### To pass Data to other elements:
- using Prop we can pass the data to another component.
- ![alt text](image-2.png)
- ### Renering on Webpage:
- React uses Virtual DOM (VDOM) for rendering
- DOM: Document Object MOdel
- ![alt text](image-3.png)
- ![alt text](image-4.png)

---------------------------------------------------------
- ## Folder structure
app/
  layout.tsx             ← Root layout, wraps the whole app (all pages)
  page.tsx               ← Homepage `/`
  about/
    page.tsx             ← About page `/about`
  projects/
    layout.tsx           ← Layout specific to `/projects` route and its children
    page.tsx             ← Projects page `/projects`


- 1. app/layout.tsx — Root Layout

This is the main wrapper for your entire website.

Anything you put here (like a header, footer, or global styles) will appear on every page of your website.

It’s like the outer frame holding all your pages inside.

Think of it like the main skeleton of your website.



------------------------------------------------------------------
# 👩‍💻 Full-Stack Developer

## 🌟 About Me

I’m a passionate **Full-Stack Developer** with a strong foundation in both **frontend and backend development**, focused on building scalable, user-friendly, and reliable web applications.

I enjoy turning real-world problems into clean, efficient solutions using modern JavaScript frameworks and backend technologies. I’m especially interested in building end-to-end products, working with APIs, and continuously learning new tools that improve performance, security, and user experience.

I’m excited to collaborate on impactful projects and grow as a software engineer in a fast-paced, product-driven environment.

---

## 🛠️ Technical Skills

### 💻 Languages
- JavaScript  
- TypeScript  
- HTML  
- CSS  
- SQL  

### ⚙️ Frameworks & Libraries
- React.js  
- Next.js  
- Angular  
- Node.js  
- NestJS  

### 🗄️ Databases
- MongoDB  
- DynamoDB  
- PostgreSQL  

### 🧰 Tools & Platforms
- Git & GitHub  
- Postman  
- Swagger  
- Jest (Unit Testing)  

**Focus Areas:** Full-Stack Development, REST APIs, Authentication & Authorization, Clean Code, Testing

---

## 📌 Projects

### 🔹 Credit Underwriting Platform (CUP)
**Tech Stack:** NestJS, MongoDB  
**Type:** Training / Enterprise-style Project  

**Description:**  
A backend-focused platform built to support administrative workflows and secure financial operations.

**Key Contributions:**
- Designed and developed APIs to retrieve and download admin lists with filtering capabilities  
- Implemented OTP-based verification with validation, lockout conditions, and mobile verification checks  
- Fixed wallet-related issues including balance calculation, sorting, formatting, and paisa-to-rupee conversion  
- Wrote and executed unit tests using Jest, covering both positive and negative scenarios  
- Improved code quality and ensured secure user access  

---

### 🎬 Movie Ticket Booking Website
**Tech Stack:** Angular, Node.js  

**Description:**  
A full-stack movie ticket booking application with role-based access for admins and users.

**Key Features:**
- Separate admin and user modules  
- Authentication and authorization system  
- Movie management and booking functionality  
- Clean UI with structured workflows  

---

### 📝 Quiz Website
**Tech Stack:** React.js, Node.js  
**Type:** Training Project  

**Description:**  
An interactive quiz platform designed to evaluate users and display results in real time.

**Key Features:**
- Users can select one answer per question  
- Displays score with correct answers  
- Integrated scoring logic and leaderboard system  

---

### 🍽️ Recipe Cookbook Website
**Tech Stack:** Angular  
**Type:** Training Project  

**Description:**  
A recipe management platform for browsing and managing cooking recipes.

**Key Features:**
- Recipe categorization with detailed ingredients and instructions  
- Users can add, edit, and manage their own recipes  
- Clean and user-friendly interface  


---

## ✨ Tagline Ideas
- **Full-Stack Developer building scalable web applications with modern JavaScript**
- **Turning ideas into clean, reliable, and user-focused web solutions**
- **Full-Stack Developer | React | Angular | Node.js | NestJS**
