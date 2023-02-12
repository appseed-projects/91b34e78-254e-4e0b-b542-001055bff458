# React Argon Design `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Argon Design* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

- 👉 [React Argon Design](https://react-argon-design.appseed-srv1.com/login-page) - LIVE Demo (from a similar product)

- 🚀 Built with [React App Generator](https://appseed.us/generator/react/), timestamp `2023-02-12 17:29`

<br />

![React Argon Design - Open-Source Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/206225228-85e663a2-40e6-4346-bff2-c5c3ebd7dc4b.png)



<br >

## ✨ `React` Argon Design System

- Design crafted by *[Creative-Tim](https://bit.ly/3fKQZaL)*
- Innovative **Material Kit Design**
- Full-stack ready
- `UI Kit`: 750+ components, `4 Sample Pages`  

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ❌ |
| `v15.0.0` | ✅ | ❌ | 
| `v16.15.0` | ✅ | ✅ | 


<br />

## ✨ `Flask API` Features

- Stack: `Flask` / `Flask-RestX` / **SQLite** 
- **DB Layer**: `SqlAlchemyORM`, `SQLite` persistence
- **Auth**: JWT tokens managed via `Flask-jwt_extended`
- [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server


<br /> 

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-flask`

```bash
$ cd api-server-flask
```

<br >

> **Step 2** - Install dependencies using a `virtual environment`

```bash
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ pip install -r requirements.txt
```

<br />

> **Step 3** - Setup the `Flask` environment 

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
// OR 
$ (Windows CMD) set FLASK_APP=run.py
$ (Windows CMD) set FLASK_ENV=development
$
$ (Powershell) $env:FLASK_APP = ".\run.py"
$ (Powershell) $env:FLASK_ENV = "development"
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ flask run
```

Use the API via `POSTMAN` or `Swagger Dashboard` at `localhost:5000`.

<br /> 

## 👉 Codebase Structure

```bash
< ROOT  >
    |
   api-server-flask/
    ├── api
    │   ├── config.py
    │   ├── __init__.py
    │   ├── models.py
    │   └── routes.py
    ├── requirements.txt
    ├── run.py
    └── tests.py
```

<br />



<br />

## [React Argon Design PRO](https://appseed.us/product/argon-design-system-pro/full-stack/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

`Argon Design React PRO` is built with over 100 frontend individual elements, like buttons, inputs, navbars, alerts or cards, giving you the freedom of choosing and combining. The product comes with a simple JWT authentication flow: login/register/logout. 

- 👉 [React Argon Design PRO](https://appseed.us/product/argon-design-system-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Argon Design PRO - Premium Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/206378423-541acda7-1022-419e-998e-716ade757906.png)

<br />

---
**React Argon Design** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
