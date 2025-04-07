**Practice Questions: Designing Web Applications (Part 2)**

## **Multiple Choice Questions**

**1.** *(1 mark)* What is the primary function of **version control** in web development?  
   - A) To improve website loading speeds  
   - B) ➡️ To track code changes and enable collaboration  
   - C) To manage API security  
   - D) To optimize CSS styling  

**2.** *(1 mark)* Which of the following is an example of a **front-end framework** used for web development?  
   - A) Flask  
   - B) ➡️ React.js  
   - C) MySQL  
   - D) Django  

**3.** *(1 mark)* Why is **lazy loading** used in web applications?  
   - A) To ensure all content loads before a user interacts with the page  
   - B) ➡️ To reduce initial load times by only loading content as needed  
   - C) To encrypt user data during transmission  
   - D) To improve database performance  

---

## **Short Answer Questions**

**4.** *(3 marks)* Explain the importance of **branching and merging** in version control systems like Git.  
> Version control systems like git employ systems like branching and merging to facilitate effective, non-destructive, and time friendly development practices. A main code base represents the trunk of the project. When changes to the main code base are requested, the developer can create a branch, forking the repo. Edits can be made in the branch to not affect the trunk adversely. Once the branch has been tested thoroughly, the branch can be merged into the trunk. The merging process ensures that the merged code has no issues with integrating into the trunk, and no existing features and functionality are compromised. Hence, collaborators can work on multiple feautres without adversely affecting one another, reducing the risks associated with adding/removing/editing existing featuers. 


**5.** *(3 marks)* Describe the differences between **template engines, predesigned CSS classes, and front-end frameworks** in web development.  
> Template engines refer to engines that compile HTML by taking a blueprint and inserting dynamic information into areas necessesary. Predesigned CSS classes refer to classes of CSS that can be applied in bulk to any class of HTML objects. Predesigned CSS classes often follow the `.xyz{ }` format. Predesigned CSS classes are only for visual purposes. Front end frameworks like tailwind and bootstrap package HTML, CSS, javascript functionality, and other logic into one system. While template engine input dynamic content into a blueprint, and predesigned css classes motivate visual consistency, front end frameworks offer a broader set of tools that enable the creation of entire UIs. All three implement reusuability through abstration but at different levels. 


**6.** *(3 marks)* What are some **common methods used to optimize web application load times**? Provide examples.  
> Web application load times can be optimised through multiple techniques. One method is lazy loading, where contentis only loaded on demand. For example, a news app will only load the first 10 articles until the user scrolls down. Then the app loads the next 10, etc. Another method is compressing images to their minimum viable resolution before transmitting to client and/or painting. For example, an image in the news app is originally 2000x2000px, but will only be displayed in a 100x100px container, so the image can be compressed to an appropriate resolution accordingly, reducing the size of the image and the resources it takes to paint the image.


---

## **Extended Response Questions**

**7.** *(4 marks)* Discuss the advantages and disadvantages of using **open-source software** in web development. Provide examples.  
> Open source software refers to when the source code of a distributed software is available to the public under a specific license. This means that anybody from the public can implement a feature, fix a bug, or make any other modifications to a software system directly at the source code. For example, a fictional open source linux distribution, Doors, has a bug in it's settings app where text is green instead of blue. A developer from the public can fork the source code of Doors, change the text from green to blue, and then open a pull request for their branch to be merged with main. By opening software to the public, developers can reduce the amount of time they spend implementing a feature, handling bugs, or making any other changes to a software system, dramatically reducing initial investment costs. Open source software also enables public scrutiny, enabling transparency and security.
>
> However, open source software also typically means that anyone from the public is able to compile the software on demand, for free. The implication of this is open source software is typically not monetizable, as anyone can freely run the software. For example, as Doors is open sourced, anyone can download the source code for Doors and run it. This also means that if Doors has a security vulnerability, bad actors can exploit it before it gets patched. Even worse, patches may never roll out due to the typical lack of commercial support; open sourced software almost entirely relies on community support. 


**8.** *(4 marks)* How do **web content management systems (CMS)** simplify web development, and what are their limitations?  
> Web CMS (content management systems) are systems that provide the entire suite of tools to host content on a web platform. This can include something like weebly, shopify, or wix. By providing all the tools necessesary to complete an entire web content system, CMS. 



**9.** *(4 marks)* Explain the role of **Progressive Web Apps (PWAs)** in modern web development, including their benefits and key features.  
> Progressive Web Apps (PWAs) are a method of designing a web software system which can be ran in a browser, and be 'installed' from that browser onto a user's system. PWAs are dynamic in nature, setting them apart from the static website. The dynamicness of PWAs means that PWAs can display a wider variety of content compared to websites, and these can be customised to the user. PWAs also can reduce development times as one PWA can run on every device with a browser. Through service workers, PWAs can run offline or in poor network conditions. PWAs have access to push notifications, home screen icons, app like interfaces and more. These all benefit a software system.































