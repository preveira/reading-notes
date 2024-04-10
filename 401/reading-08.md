# Reading-08 #

1. **What is Role Based Access Control (RBAC) and why do we care?**
   Role-Based Access Control (RBAC) is a method of regulating access to computer or network resources based on the roles of individual users within an organization. In RBAC, access decisions are determined by a user's role, which is typically associated with a set of permissions. We care about RBAC because it offers a structured and efficient way to manage access control in large organizations, ensuring that users only have access to the resources necessary for their roles, thereby reducing the risk of unauthorized access and potential security breaches.

2. **Describe a Role/Permission hierarchy that you might implement using RBAC.**
   In an RBAC system, you might have roles such as:
   - Administrator: with permissions to access and modify all system settings and data.
   - Manager: with permissions to view and manage employees' data but not system settings.
   - Employee: with permissions limited to accessing their own data and performing specific tasks related to their job role.

3. **What approach might you take to implement RBAC?**
   To implement RBAC, you would typically follow these steps:
   - Identify roles within the organization.
   - Assign permissions to each role based on job requirements.
   - Associate users with appropriate roles.
   - Implement mechanisms for enforcing access control based on roles and permissions.

4. **If Authentication is “you are who you say you are,” what is Authorization?**
   Authorization is the process of determining what actions or resources a user is allowed to access after they have been authenticated. In simple terms, it answers the question: "What are you allowed to do now that we know who you are?"

5. **Name three primary rules defined for RBAC.**
   Three primary rules in RBAC are:
   - Role assignment: A user is assigned to one or more roles.
   - Role permission: Users are allowed to access resources or perform actions based on the permissions associated with their roles.
   - Role authorization: Access to resources is granted or denied based on the roles assigned to users.

6. **Describe RBAC to a non-technical friend.**
   RBAC is like organizing a club where each member has a specific role. Depending on their role, they can do different things. For example, the president can access all areas and make big decisions, while regular members can only access certain rooms and do specific tasks assigned to them.

7. **What Are access rights Associated with? The User? or The Role? Explain.**
   Access rights are associated with the role in RBAC. Users are assigned roles, and the access rights are predetermined based on those roles. So, different users with the same role will have the same access rights.

8. **Access Rights, or Authorization, is activated after a user successfully does what?**
   Access rights, or authorization, are activated after a user successfully authenticates themselves, i.e., proves their identity through the authentication process.

9. **Explain how RBAC might benefit a business.**
   RBAC can benefit a business in several ways:
   - Enhanced security: By limiting access to resources based on roles, RBAC reduces the risk of unauthorized access and potential security breaches.
   - Improved efficiency: RBAC simplifies access management by organizing users into roles, making it easier to assign and revoke access rights as employees change roles or leave the organization.
   - Compliance adherence: RBAC helps businesses enforce access control policies, ensuring compliance with regulations and standards regarding data privacy and security.

## Things I want to know more about ##
