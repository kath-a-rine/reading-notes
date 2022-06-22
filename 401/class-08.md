# Access Control

## 5 Steps to RBAC

*What is Role Based Access Control (RBAC) and why do we care?*

"The idea of assigning system access to users based on their role in an organization." 

*Describe a Role/Permission hierarchy that you might implement using RBAC*.

In an organization, those "higher ups" would have more permissions than those under them. Access it limited as it moves down the chain, meaning only only those who need it have the most access.

*What approach might you take to implement RBAC?*

- inventory your systems: know what resources are needing control access (email system, CMS, customer database)
- analyze workforce and create roles
- assign people to roles
- do not make one-off changes
- audit

## wiki - RBAC

*If Authentication is “you are who you say you are,” what is Authorization?*

Authorization is what an authenticated user has access to within the system.

*Name three primary rules defined for RBAC.*

- Role assignment
- Role authorization
- Permission authorization

*Describe RBAC to a non-technical friend.*

## RBAC Tutorial

*What Are access rights Associated with? The User? or The Role? Explain*.

Access rights are associated with the the role, not the user.

User -> Role -> Rights

*Access Rights, or Authorization, is activated after a user successfully does what?*

After a user is successfully authenticated.

*Explain how RBAC might benefit a business.*

Policies do not need to be updated when a person leaves a role within an organization, since authorization is tied to the role. It can be considered a form of "damage control." 