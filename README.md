# notes-careertrack-28.md 
## Architectural Styles and Architectural Patterns
* Architectural and design patterns are similar but architectural pattern have strategies for components and properties. 
* Architectural patterns solves a recurring Architectural problem.
* Architectural Styles doesn't exist to solve a problem. 
* Idiom is a low-level usually language specific solve.
* Layer Types- 1. Presentation 2. Application 3. Business logic 4. Data access
* Event-Driven- (EDA) Emmiter is an event and Consumers consume the event. Usually adaptable to complex environments.
* Domain Driven design-(DDD) design software based on Business Domain. Not about the code but way of looking at things
* Pipes and Filters-A filter transforms the data, pipers act to connect that data.
* Microservice- create a lots of small programs to work as a larger one. They act independently of each other. 
## Container and Presentation 
```
my-app
└── src
    ├── assets
    │   └── myImg.png
    ├── components
    │   ├── ComponentName
    │   │   ├── ComponentName.css
    │   │   ├── ComponentName.jsx
    │   │   └── ComponentName.test.jsx
    ├── containers
    │   ├── ContainerName
    │   │   ├── ContainerName.jsx
    │   │   └── ContainerName.test.jsx
    ├── services
    │   └── myService.js
    └── index.jsx 
```
## Functional vs Class-Components in React
* Syntax is the main difference. 
* Cannot use setState in functional without using hooks. 
* Hooks now make functional the same as class. 
* Functional is what more developers prefer.
## Container Component Details
* Container hooks looks awesome and I'm excited to use them. 
## Presentation Component Details
* This what we did in class yesterday. It was great and I'm sure we will see again a lot. 
