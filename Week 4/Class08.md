# Access Control (ACL)

----

**_5 steps to RBAC_**

1. What is Role Based Access Control (RBAC) and why do we care?

> RBAC is a security model provides a structured and efficient approach to managing access control, and ensuring compliance within organizations.role-based access control, is a framework built around defined roles, each with associate permissions. Users are then assigned to one of these roles, to determine which actions they can take within the app.
assigns permissions and access rights to predefined roles rather than individual users. RBAC simplifies access control management by centralizing permissions, making it easier to control and track user privileges.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.

 > Superadmin: Have complete control, allowing them to manage roles, assign permissions, and perform system-wide configurations. They have access to all resources and functionalities.
> Administrator: Responsible for managing user accounts and system configurations within specific departments or divisions, they do not possess system-level configuration privileges.
 > Manager: Have the ability to oversee and manage teams or departments, they do not have access to system configurations or user management capabilities.
  > Team Lead: Have limited administrative capabilities and can manage their respective teams, they do not possess access to system configurations or user management functionalities.
  > User: They have limited permissions based on their specific job roles and responsibilities, can access and modify data relevant to their work.

3. What approach might you take to implement RBAC?


 * Inventory the systems: Find out what resources for which you need to control access. Like email system, customer database etc. 

 * Analyze the workforce and create roles: You need to group your workforce members into roles with common access needs.  Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible.

* Assign people to roles: After having a  list of roles and their access rights, determine which roles each employee belongs 

* Never make one-off changes: Change the roles as required or add new ones when really necessary. 

* Audit: Periodically review your roles, the employees assigned to them, and the access permitted for each. If anyone had unnecessary access to a particular system adjust it.

----

**_wiki - RBAC_**


1. If Authentication is “you are who you say you are,” what is Authorization?

> If you have the permission to access certain resources, perform specific actions, or use particular functionalities within a system or application.

2. Name three primary rules defined for RBAC.

 * Role Assignment 
 * Role Authorization
 * Role Hierarchy

3. Describe RBAC to a non-technical friend.

> RBAC (Role-Based Access Control) is a system that assigns permissions to roles rather than individual users. It ensures that users only have access to what they need based on their roles, simplifying access management and enhancing security.

----

**_RBAC tutorial_**

1. What Are access rights Associated with? The User? or The Role? Explain.

>User-based access rights mean that each individual user is assigned specific permissions directly. This allows for precise control over who can do what in a system.

> Role-based access rights mean that permissions are assigned to predefined roles instead of individual users. Users are then assigned to these roles, inheriting the permissions associated with them. This simplifies access management, especially in larger systems or organizations.
 


2. Access Rights, or Authorization, is activated after a user successfully does what?

> After a user has successfully authenticated

3. Explain how RBAC might benefit a business.

> RBAC benefits a business by simplifying access management, improving security, ensuring compliance with regulations, increasing productivity, and providing scalability and flexibility. It streamlines user access by assigning permissions to roles, reduces the risk of unauthorized access, facilitates compliance audits, enhances productivity by granting appropriate access, and allows for easy adaptation as the business grows.

