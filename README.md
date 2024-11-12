# User Authentication System

A full-stack authentication system using JWT to secure user login and registration.

Built by **Phan Duong Quoc Dat - 20120268** for IA03 and IA04 assessment of the **Advanced Web App Development** course at **HCMUS**.

## Tech stack

-   Front-end: React, Tailwind CSS, Zustand (for state management)
-   Back-end: NestJS, JWT
-   Database: MongoDB

## How to run

Clone the repository:

```bash
git clone https://github.com/pdqdat/awp-ia03.git
```
PORT=8080

MONGODB_CONNECTION_STRING=
MONGODB_DATABASE_NAME=

JWT_SECRET=
```

The `frontend/.env.development` file has been pre-configured to connect to the back-end server at `localhost:8080`:

```env
VITE_BACKEND_URL="http://localhost:8080"
```

Install the dependencies, then run the Back-end server:

```bash
cd backend
npm install
npm run start:dev
```
In another terminal, install the dependencies, then run the Front-end server:

```bash
cd frontend
npm install
npm run dev
```
Open your browser and navigate to `http://localhost:5173` to access the application.

You can visit the deployed version at [https://nestjsauth.vercel.app/](https://nestjsauth.vercel.app/).

## References

-   [Tailwind CSS Documentation](https://tailwindcss.com/docs/)
-   [Nestjs Documentation](https://docs.nestjs.com/)
