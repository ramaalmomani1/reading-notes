# Express, NPM, TDD, CI/CD

---

#### A. _Express:_
1. Explain middleware, answer as though I were a non-technical recruiter.

>Middleware is a software that acts as an intermediary between two applications or services to facilitate their communication.

2. Express the most popular __ __ ____.

>Node web framework

3. Express is “unopinionated.” What does that mean?

> Unopinionated means that there are no strict rules and it doesn't decide for you a lot of aspects of what tool you use for each specific task. You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure.

4. What is a module and why is modularity useful to us as developers?

>Module is a discrete piece of code which can be independently created and maintained to preformed a specific  functionality and to be used in different systems. A module is a JavaScript library/file that you can import into other code using Node's require() function. 

- Advantages of Modularization in Programming:
>1. Easier to Debug 
 >2. Reusable Code
>3. Reliability 
>4. Manageability

---

#### B. _Node Package Manager (NPM):_

1. What version of npm are you running on your machine?

> command line (npm --version)  9.5.0


2. What command would you type to install a library/package called ‘jshint’ into your node project?

> npm i jshint

---

#### B. _Test-driven development (TDD):_

1. Explain why tests are important. Please explain as though I were your non technical elder.

>To identify defects, reduce flaws in the component or system, increase the overall quality of the system and leads to improved design qualities.

2. What are three expected benefits of testing

>  i. The testing is important since it discovers defects/bugs before the delivery to the client, which guarantees the quality of the software.
ii. It makes the software more reliable and easy to use.
iii. Thoroughly tested software ensures reliable and high-performance software operation.

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

> *  Individual pitfalls: 
>>1. writing too many tests at once
>> 2. writing tests that are too large or coarse-grained

> *  Team pitfalls: 
>>1. partial adoption – only a few developers on the team use TDD
>> 2. poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

---

#### B. _Continuous Integration (CI), Continuos Delivery/Continuous Deployment (CD):_

1. What are three benefits of Continuous Integration?

>CI is a development process where team members are integrating their work frequently

> 1. Risk Mitigation and quality assurance
> 2. Early troubleshooting possible
> 3. Accurate recording of changes


2. What is the difference between Continuos Delivery and Continuous Deployment?

> Continuous delivery automates deployment of a release to an environment for staging or testing. Continuous deployment automatically deploys every release through your pipeline (including testing) and to production. While they are different, continuous deployment is an extension of the continuous delivery concept.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

>GitHub serves as a collaboration platform. Allows developers to integrate their work, test and deploy software.

---

## Reflection

What are your learning goals after reading and reviewing the class README?

> * Node Modules
> * Code Modularization
> * Express Middleware
> * HTTP Status Codes
> * TDD and Testing