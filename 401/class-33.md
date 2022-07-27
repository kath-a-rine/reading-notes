# `<Login />` and `<Auth />`

## [What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

**What is Role Based Access Control (RBAC)?**

RBAC "*restricts network access based on a person's role within and organization.*"

**Share some an example of RBAC including all possible CRUD operations and correlating roles.**

- *Management role scope – it limits what objects the role group is allowed to manage.*
- *Management role group – you can add and remove members.*
- *Management role – these are the types of tasks that can be performed by a specific role group.*
- *Management role assignment – this links a role to a role group.*
- *Primary – the primary contact for a specific account or role.*
- *Billing – access for one end-user to the billing account.*
- *Technical – assigned to users that perform technical tasks.*
- *Administrative – access for users that perform administrative tasks.*

**What are the Benefits of RBAC?**

- Reducing admin work and IT support
- Maximizing operation efficiency
- Improving compliance

## react-cookie library / react-cookies component

**Describe some `react-cookie` features.**

- `<CookiesProvider>`: set user cookies
- `useCookies([dependencies])`: access and modify React hooks
  - `setCookie(name, value, [options])`: set cookie value
  - `removeCookie(name, [options])`: remove a cookie
- `withCookies(Component)`: give access to cookies anywhere. Add these props to your component:  cookies and allCookies

- `get(name, [options])`: get cookie value
- `getAll([options])`: get all cookies
- `set(name, value, [options])`: set cookie value
- `remove(name, [options])`: remove a cookie

**Describe some `react-cookies` features.**

- `plugToRequest` and `setRawCookie`: allows the ability to access user cookies while server-rendering.
- 
**Which library would you prefer would you prefer? Why?**
`react-cookie` seems simpler,  more straight forward, works with Hooks, and has more recent updates and downloads.