1. How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by organizing the code into clear sections, using meaningful names, and separating different responsibilities into different parts of the program. In this project, the CRUD Python module helped make the dashboard easier to maintain because the database operations were kept separate from the dashboard code. Instead of writing create, read, update, and delete logic directly inside the dashboard, the dashboard could call the CRUD module when it needed to interact with MongoDB. This made the code easier to read and easier to change later.

The advantage of working this way was that the same CRUD module could be reused in other projects that need to connect to the animal shelter database. In the future, this module could be expanded with more search filters, stronger error handling, or different database collections without having to completely rewrite the dashboard. This kind of structure makes the program more adaptable because one part of the project can be updated without breaking everything else.

2. How do you approach a problem as a computer scientist?

I approach a problem as a computer scientist by first understanding what the client needs, then breaking the problem into smaller steps. For this project, Grazioso Salvare needed a dashboard that could help identify animals that may be good candidates for rescue training. Instead of trying to build everything at once, I focused on the database connection, the CRUD operations, the dashboard layout, the filtering options, and then the visual components like the data table, chart, and map.

This project was different from some previous assignments because it felt more like a real client request. I had to think about how the user would interact with the dashboard, not just whether the code worked. In the future, I would use the same strategy of breaking the project into smaller parts, testing each part as I go, and making sure the final product matches the client’s actual needs.

3. What do computer scientists do, and why does it matter?

Computer scientists solve problems by designing software, working with data, and creating tools that help people or organizations work more efficiently. Their work matters because technology is used in almost every industry, and good software can save time, reduce mistakes, and make important information easier to understand.

For a company like Grazioso Salvare, this type of project could make their work easier by helping them quickly search and filter animal shelter data. Instead of manually looking through records, the dashboard allows users to view animals that match certain rescue training criteria. This helps the company make faster, better-informed decisions and focus more time on training and rescue work rather than sorting through data manually.
