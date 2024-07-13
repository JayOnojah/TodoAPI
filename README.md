# TodoAPI in TypeScript/Express

Utilized TypeScript for back-end development using NodeJS, Express, TypeORM and MySQL.

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/JayOnojah/todo-backend.git
cd todo-backend
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
PORT=3200
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_DATABASE=
MYSQL_HOST=
```

Replace the placeholder values with your actual Database creadentials.

**Running the Project**

```bash
npm run dev
```

Use [http://localhost:3200](http://localhost:3200) to interract with the API endpoints.
