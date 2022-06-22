# Read: 08 - Access Control (ACL)

## Reading

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1. **What is Role Based Access Control (RBAC) and why do we care?** RBAC is assigning system access to users based on their role within an organization. Roles are defined and grouped based on the needs of a given workforce based on common job responsibilities and system access needs.
2. **Describe a Role/Permission hierarchy that you might implement using RBAC.** Most software platforms have RBAC capabilities that allow a company to easily assign roles to employees based on their job responsibilities. For example, there could be roles for marketing/content, technical admins, product managers, operations, and finance - with each role defined for what they have access to, what information they can modify, and what tasks they can perform based on the role they are assigned in the platform.
3. **What approach might you take to implement RBAC?**
   * Inventory your systems
   * Analyze your workforce and create roles
   * Assign people to roles
   * Never make one-off changes
   * Audit

[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1. **If Authentication is “you are who you say you are,” what is Authorization?**
   1. Authorization allows for specific role functions.
2. **Name three primary rules defined for RBAC.**
   1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
   2. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
   3. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.
3. **Describe RBAC to a non-technical friend.**
   1. RBAC - Role Based Access Controls allows for an organization to setup roles based on various job functions. Each role has a predefined set of permissions to perform certain operations. Each employee is assigned a role and is granted the access permissions based on the role.

### Videos

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1. **What are access rights Associated with? The User? or The Role? Explain.** Access rights for RBAC are associated with The Role. Each role has a predefined set of access rights to perform a specific set of operations by the user.
2. **Access Rights, or Authorization, is activated after a user successfully does what?** Access rights are granted to a user once they are activated/assigned to a role.
3. **Explain how RBAC might benefit a business.** RBAC aligns with business policies. New employees can quickly gain the appropriate access rights by being assigned a role based on their job function. If the employee changes roles within the organization, the role can be updated for the user so that they are granted with additional access rights.
