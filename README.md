The Inventory App was developed to meet the needs of warehouse employees, managers, and logistics staff who require a simple and reliable way to track stock 
levels throughout the workday. The primary goal of the app is to provide users with an intuitive tool for adding, updating, deleting, and viewing inventory items 
while also offering optional SMS alerts when stock reaches zero. This supports real world warehouse workflows by reducing errors, preventing stockouts, and giving 
users quick access to essential information. The app’s requirements centered on secure login functionality, persistent data storage through SQLite, a grid based 
inventory display, and SMS notifications tied directly to inventory changes.
To support these user needs, the app includes three main screens: a login screen, an inventory dashboard, and an SMS permission screen. The login screen allows 
both returning users and first time users to securely access the system. The inventory dashboard displays all items in a clear grid layout and provides controls 
for adding, updating, and deleting entries. The SMS permission screen ensures users understand and control whether the app can send low inventory alerts.
When coding the app, I approached the process by breaking the project into clear functional components: authentication, database operations, UI behavior, and 
SMS permissions. I used modular Java classes, consistent naming conventions, and in line comments to keep the code organized and readable. These techniques will 
be valuable in future projects because they support maintainability, reduce debugging time, and make complex tasks more manageable.
Testing played a critical role in ensuring the app was functional and reliable. I tested login behavior with both valid and invalid credentials, verified that 
inventory items could be created, updated, and deleted, and checked that the database persisted data after closing the app. I also tested both outcomes of the 
SMS permission request to confirm that the app behaved correctly whether permission was granted or denied.
Throughout the full design and development process, I encountered challenges that required creative problem solving. One key challenge was ensuring that SMS 
notifications were logically tied to inventory updates rather than existing as a separate, isolated feature. Another challenge involved configuring the manifest 
correctly so that all activities launched without crashing. Overcoming these issues required careful debugging, reviewing documentation, and restructuring parts of 
the code to create a more cohesive and functional app.
The component where I was most successful in demonstrating my skills was the integration of the SQLite database with the RecyclerView inventory grid. This part of 
the app required combining UI design, database logic, and dynamic data binding to create a smooth and responsive user experience. Implementing full CRUD 
functionality and ensuring that the grid updated in real time showcased my ability to connect multiple layers of the application and produce a user centered, fully 
functional feature.
