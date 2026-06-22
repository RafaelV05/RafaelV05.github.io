Enhancement One: Software Design and Engineering

Artifact Description

I selected for this enhancement is the Travlr Getaways full-stack web application that I originally developed in CS-465 Full Stack Development. The project uses MongoDB, Express, Angular, and Node.js to provide both a customer-facing travel website and an administrative portal for managing trips and reservations.
I chose this project because it is the largest application I created during the program. It combines frontend development, backend services, database management, authentication, and administrative functionality, which makes it a strong candidate for demonstrating software design and engineering improvements.
Enhancement Description
For this enhancement, I focused on improving the overall structure, maintainability, and security of the application. The original project was functional, but there were several areas where the code could be organized more effectively and made easier to maintain.
One of the biggest changes was moving authentication logic into a dedicated middleware file. Originally, authentication responsibilities were mixed into the route definitions, which made the code harder to manage. Separating that functionality into its own module helped improve the overall organization of the application and made the authentication process reusable across multiple routes.
I also created a role-based authorization middleware to handle access control for administrative features. Before this change, admin checks were repeated inside multiple controller methods. By moving that logic into a reusable middleware component, I reduced duplicated code and made permissions easier to manage.
Another improvement involved standardizing error handling throughout the backend. I created a shared API response utility so controllers could return consistent error messages. This made the code cleaner and improved communication between the frontend and backend.
Finally, I spent time improving documentation throughout the project. I added descriptive headers, comments, and section labels to important files such as controllers, middleware, models, routes, and the main application configuration file.

Alignment to Course Outcomes

This enhancement supports Course Outcome 3 because it focuses on improving the design and structure of an existing software solution. By separating responsibilities into dedicated middleware and utility files, I made the application more modular and easier to maintain. These changes follow common software engineering practices and help support future development.
The enhancement also supports Course Outcome 5 because it improves the security architecture of the application. Authentication and authorization are now handled through dedicated middleware, making security responsibilities easier to manage and reducing the chances of inconsistent access control throughout the application. The project also continues to use secure password hashing and JWT-based authentication to protect user information.
Progress Toward Planned Outcomes
My original goals were to improve the application's organization, strengthen authentication and authorization, improve error handling, and make the codebase easier to maintain. Through the creation of reusable authentication and authorization middleware, standardized API error handling, improved documentation, and the removal of duplicated logic, I was able to accomplish the objectives outlined in the enhancement plan. At this time, I do not anticipate making significant changes to my outcome-coverage plan because the completed enhancements align well with the original goals.

Reflection

This enhancement helped me better understand the difference between writing code that works and writing code that is designed to be maintained over time. The original application already met its functional requirements, but there were several opportunities to improve how the code was organized behind the scenes.
The most valuable change was separating authentication and authorization into reusable middleware. Not only did this reduce duplicated code, but it also made the application easier to understand. If I need to make changes to authentication or permissions in the future, I now have a single place to manage that functionality.
I also gained a greater appreciation for documentation. Adding meaningful comments and file headers forced me to think about the purpose of each file and how different parts of the application interact with one another. Even though documentation does not add new features, it makes the project much easier to maintain and understand.
Overall, this enhancement allowed me to improve the quality of the application without changing its core functionality. The result is a more organized, maintainable, and secure project that better reflects the software engineering skills I have developed throughout the Computer Science program.

