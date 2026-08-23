<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/1a85ec37-18a5-4583-94b5-3e4bcb338b07">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/a257e650-9b8e-4def-8c3c-40519c38f275">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://github.com/user-attachments/assets/a257e650-9b8e-4def-8c3c-40519c38f275">
</picture>

## About me

Hello, I am Seth Sharp. I'm a developer interested in web apps, open source projects, and learning new technologies.

## Technology & Tools
  
| Tools | Technology |
|-----:|-----------|
|     Languages     | JavaScript, Java, Python, C++, HTML, SQL |
| Stack Components | Node.js, Angular, Express, MongoDB, Postman |
| Version Control  | Git, GitHub |

<details>
<summary>Professional Self-Assessment</summary>


Through the coursework I completed, while attending Southern New Hampshire University's computer science online classes, I learned many valuable skills and processes, as well as refined my talents in critical thinking, problem solving, adaptability, and attention to detail. To begin, one of the projects I worked on for a course was a rudimentary purchase analyzer for a corner grocery store, in order for the relevant people to find out the most popular items. This was a C++ based project that required me to develop stronger attention to detail and more robust problem solving, as it required nested loops that could easily get too convoluted. One way I worked around making this mistake was to implement switch-case statements to create a responsive UI for user inputs. This project gave me invaluable skills in software engineering, along with data structures, algorithms, and analysis, because I had to iterate through a list of purchased items, store it in a hash map with distinct goods and purchase counts, and display the data as a histogram to users upon request. To fulfill this, I had to increase my understanding of object-oriented programming, software design, and the C++ language itself. Additionally, I learned secure coding practices and a secure coding mentality from my Secure Coding and Software Security classes respectively. In the former, I created code to protect against buffer overflow and SQL injection attacks. Though, I still have a lot more to learn in this field to gain more familiarity. In the latter of the two classes, I performed vulnerability assessments using OWASP and developed remediation procedures after performing a security code review, which allowed me to gain a deep appreciation for the breadth of knowledge needed in risk assessment. This experience in security gives me an ability to think of many methods for exploitation that need to be defended against, so that I can create defensive measures that anticipate mistakes and malicious actors. However, I have limited experience with collaborating in a team environment and communicating with stakeholders. That being said, I am eager to learn new things and have an aptitude to learn quickly. What experience I do have comes from communications to mock stakeholders that did not provide feedback, and class discussions with other students providing feedback on approaches, techniques, and bugfixes. 


The technical artifact I have chosen to demonstrate my talents and abilities is called *travlr*. It is a MEAN full-stack web application that has a customer facing site on port 3000 with rudimentary navigation across every tab. There is also an administrative SPA that allows users to view trips, as well as login to an admin account to edit and created trips. The newest version  of the web app was finished 21 August 2026, and it contained several bug fixes with navigation, authorization, and API communication. Its inclusion in my ePortfolio demonstrates my ability to work with robust codebases, as well as within a MEAN stack application to add functionality and improvements. The specific components that showcase my abilities are in the travel, rooms, meals, and contact pages on the port 3000 site, wherein I had to build and route these pages myself in the original project. Although this was not particularly difficult, I learned to problem solve and adapt to a new development project quickly. The contact page was completely developed by me, with success and error pages to redirect to accordingly and I applied data validation to stop attacks. As for the port 4200 site, the components that showcase my abilities are the column and row creation of the trip cards, due to the original pattern not displaying in a visually pleasing way. Along with this, the admin contacts page was created, and contains a text based search with a prefix search as the fallback. Over the course of my capstone, I have been working on various improvements to the travlr codebase that have improved the experience of both websites. The first was to implement a page redirect after a user has successfully logged into the SPA site, as well as removing the name field from the login page to conform to modern login form standards. Along with this, I have made it so that the add and edit trip buttons correctly stay hidden until admin users have logged in. Continuing, I fixed the routing and selection fields for the header and footer of the port 3000 site, so that the static sites cannot be accessed and the current page selection is properly reflected. Finally, I created a method for users in the port 3000 site to send messages to the database to be accessed, search, read, and deleted by administrative users, after logging in.


</details>

<details>
<summary>Featured Projects</summary>

This is one of the projects I helped to build through my coursework at SNHU.

[MEAN Full-Stack Web App](https://github.com/ssharp/cs465-fullstack)

</details>

<details>
<summary>Full-Stack App: Enhancement One</summary>


The course outcomes I planned to meet with this enhancement included creating an additional customer page for sending contact messages to the database, as well as a new SPA page for retrieval and viewing of these messages in a table. This outcome has been met with an additional improvement in the form of a redirect page after a contact form has been submitted. This was done after testing the page initially resulted in nothing happening, which would cause confusion for users and allow for malicious attacks. In this, users were erroneously held on the page with a completed form, so a rational user may assume the form was not submitted and continuously resubmit the form. As for a malicious user, they could automate an attack to rapidly fill the database with messages and potentially crash the SPA site.


As I was enhancing and modifying the artifact I learned that a lot of the HTML pages could be reused, or had implementations that would guide me on formatting additional pages. The fact that the contact page itself was already created and set up for quick implementation of data capture made the process significantly easier. A challenge I faced with this was catching errors in the developer tools built into my web browser, as they contained more descriptive errors for various problems I faced. Among these issues, I erroneously routed my developer server to the wrong backend route, forgot to manually detect changes to initialize the views on the SPA pages, and did not the expected enforce tag formatting when initially developing the contact page. Overcoming these challenges required me to think of different ways of achieving the same goal, like creating a routing file exclusively for use with the contact component and service to avoid possible authorization header errors being thrown.


[MEAN Full-Stack Web App: v1.5](https://github.com/ssharp/cs465-fullstack/tree/milestone2)

</details>


<details>
<summary>Full-Stack App: Enhancement Two</summary>


The course outcomes I planned to meet with this enhancement included creating an additional customer page for sending contact messages to the database, as well as a new SPA page for retrieval and viewing of these messages in a table. This was completed with more modifications being required because the outcome goals were not completely met. One claim made was that the submission had an optimized search algorithm, but instead contained an unoptimized prefix search that existed solely in the HTML file. While it was dynamic, it would have been computationally costly for a large database.


As I was enhancing and modifying the artifact I learned a lot about how dynamic HTML pages could be. A challenge I faced with this was not having any changes registers upon typing when I first implemented my solution. The cause ended up being improper initialization of the HTML search method. The particular method for fixing this saw me use a quick fix by the VS Code compiler that properly initialized the search method for use. I also had to restart my program for proper execution, due to my user facing site not auto-updating in the same way as the SPA.

</details>


<details>
<summary>Full-Stack App: Enhancement Three</summary>


The course outcomes I planned to meet with this enhancement included creating an additional customer page for sending contact messages to the database, as well as a new SPA page for retrieval and viewing of these messages in a table. This outcome has been met with an additional improvement in the form of a an enhanced search method, with a tag based filter included as well. From the feedback received after milestone two regarding an incomplete course outcome, due to my HTML prefix search not being robust enough to match the established expectations, I opted to rework my project to implement a more robust search method that functions similarly. The main difference was utilizing an optimized search algorithm, as originally promised. The indexed, weighted search changed the performance from an O(n) time complexity to O(log n). My outcome-coverage plan can be updated to reflect the completion of all enhancements. 


As I was enhancing and modifying the artifact I learned a lot about project structure when search methods are used. My initial attempts at implementation were still using the old methods to retrieve every contact from the database, which caused an excessive use of browser storage. I reconfigured the project to not rely on this method and removed it entirely. After, I setup my search as the main data retrieval method, which had the intended effect of simplifying my use of the search method and reducing internal dependencies that may cause issues when interacting.


[MEAN Full-Stack Web App: v1.5](https://github.com/ssharp/cs465-fullstack/tree/milestone2)

</details>

---
> I am the wisest man alive, for I know one thing, and that is that I know nothing. - Plato
