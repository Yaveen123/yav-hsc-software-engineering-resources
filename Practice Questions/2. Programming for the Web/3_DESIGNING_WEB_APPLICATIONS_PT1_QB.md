# **Practice Questions: Designing Web Applications (Part 1)**

## **Multiple Choice Questions**

**1.** *(1 mark)* What is the primary function of the **World Wide Web Consortium (W3C)**?  
   - A) Regulating internet service providers  
   - B) ➡️ Developing standards for web accessibility, security, and compatibility  
   - C) Designing hardware for web servers  
   - D) Controlling domain name registrations  

**2.** *(1 mark)* Which of the following is a goal of the **Web Accessibility Initiative (WAI)**?  
   - A) Restricting certain users from web applications  
   - B) ➡️ Enhancing accessibility for people with disabilities  
   - C) Increasing web page loading speed  
   - D) Encrypting user data  

**3.** *(1 mark)* What is the purpose of **Content Security Policy (CSP)** in web security?  
   - A) To prevent unauthorized redirections  
   - B) ➡️ To block cross-site scripting (XSS) attacks  
   - C) To ensure responsive design  
   - D) To allow all external scripts to load without restriction  

---

## **Short Answer Questions**

**4.** *(3 marks)* Explain the importance of **internationalisation** in web development, and how developers can implement it in their applications.  
> Internationalisation (i18n) in web development refers to the aspect of which web content is designed and developed in a way that's flexible to requirements that may arise from different regions and languages, like accounting web design for possibly longer text in German or RTL/LTR layouts. The goal of i18n is to reduce the chances of having to re-engineer an entire site to make it accessible to others.


**5.** *(3 marks)* Describe the key differences between **client-side programming and server-side programming** in web development.  
> Client side programming refers to code that will be rendered on the client-side. This refers to anything that the user will  see, with emphasis on the user's browsers and ui/ux, for example on phones, laptops, etc. Server-side programming refers to programming that occurs on the server, for example database connections, endpoint management, etc. Server-side code is not directly accessible to client-side code.

**6.** *(3 marks)* How do **developer tools in web browsers** help developers debug and optimize web applications? Provide examples.  
> Developer tools in web browsers refer to the specific set of tools provided by browsers to help debug most client-side issues and (to a limited extent) some server-side issues. Developer tools give a comprehensive overview of everything that is sent to and occurs on the client, for example the javascript that is executed on the client, how it affects the html, applicable network traffic incl. connections to api endpoints, etc. This coherent overview gives developers a holistic method of debugging a website, as they can track down specific problems directly on the client side. Developer tools in browsers, such as lighthouse, also are able to analyse client performance for optimisation purposes, giving an overview to the developer of specific bottlenecks in speed, problems with accessibility, and possible security vulnerabilities.

---

## **Extended Response Questions**

**7.** *(4 marks)* Discuss the role of **databases in web applications**, comparing SQL and NoSQL databases and their advantages in different scenarios.  
> Databases in web applications refer to a system which stores data for future reference in a persistent, and organised format. Through this, databases facilitate a readily accessible read and (potentially) write system for a web applicatoin. SQL (structured query language) databases are a type of databases that are able to form relationships between attributes within a database. SQL databases facilitate the storage of structured datasets. Contrary, NoSQL (not only sql) refers to databases that do not follow the traditional, structured SQL format. NoSQL databases enable the persistent storage of semi-structured and unstructured datasets. While in an e-commerce platform with rigid sales, stocks, and customer view history which would benefit from structured data, social media platforms with constant flows of user watch history, engagement history, content delivery networks, etc. a NoSQL database would work better.


**8.** *(4 marks)* Explain how **CSS frameworks and preprocessors** impact the development and maintenance of modern web applications. Provide examples.  
> CSS frameworks, like tailwind and boostrap, provided pre-written, somewhat customisable CSS components which developers can use in their applications. CSS frameworks exist to ensure that developers do not need to build their CSS from scratch, and offers components like buttons and textboxes which have pre-written CSS. CSS preprocessors, like SASS, create new stylesheets which are then translated into CSS when required. These CSS preprocessors are often syntactically easier to use than normal css, and offers time saving features like setting variables for colours. When designed right, CSS frameworks and preprocessers significantly reduce the production time and increase the scalability in web apps. They also facilitate consistent web design, reducing load on both the developers and the designers.


**9.** *(4 marks)* How do **security standards set by W3C** help protect user data and enhance trust in web applications? Provide real-world examples.  
> Security standards by the W3C refer to the guidelines that ensure that that data remains safe and secure in 



























