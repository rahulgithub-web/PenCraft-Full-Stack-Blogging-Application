<div align="center">

# PenCraft

<i>A modern, full-stack blogging platform powered by React and Cloudflare Workers</i>

</div>

<table align="center">
  <thead align="center">
    <tr>
      <td><b>🌟 Stars</b></td>
      <td><b>🍴 Forks</b></td>
      <td><b>🐞 Issues</b></td>
      <td><b>🔓 Open PRs</b></td>
      <td><b>🔒 Closed PRs</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application?style=flat&logo=github"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application?style=flat&logo=github"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application?style=flat&logo=github"/></td>
      <td><img alt="Open PRs" src="https://img.shields.io/github/issues-pr/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application?style=flat&logo=github"/></td>
      <td><img alt="Closed PRs" src="https://img.shields.io/github/issues-pr-closed/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application?style=flat&logo=github"/></td>
    </tr>
  </tbody>
</table>

---

## 🚀 Project Overview

PenCraft is a full-stack blogging platform designed to offer users a seamless experience for creating and managing blog content. With a frontend built using React and a serverless backend powered by Cloudflare Workers, PenCraft is fast, scalable, and secure.

---

## ⚙️ Tech Stack

<div align="center">

[![React](https://img.shields.io/badge/React-61DAFB.svg?style=for-the-badge&logo=React&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748.svg?style=for-the-badge&logo=Prisma&logoColor=white)](https://prisma.io/)
[![Node.js](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=Node.js&logoColor=white)](https://nodejs.org/)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020.svg?style=for-the-badge&logo=Cloudflare&logoColor=white)](https://www.cloudflare.com/products/cloudflare-workers/)
[![PostgresSQL](https://img.shields.io/badge/PostgresSQL-4169E1.svg?style=for-the-badge&logo=PostgreSQL&logoColor=white)](https://www.postgresql.org/)

</div>

---

## ✨ Features

- **Bookmarking:** Save your favorite posts for easy access.
- **Search:** Find posts by keywords or tags.
- **Authentication:** Secure JWT-based authentication with cookies for session management.
- **Rich Text Editor:** Use Jodit for rich content creation.
- **Image Uploads:** Add images to blog posts (coming soon).
- **Responsive UI:** Built with Tailwind CSS for a sleek, responsive design.

---

## Technologies Used

- **Frontend:**

  - React: A popular JavaScript library for building user interfaces.
  - Zod: A TypeScript-first schema declaration and validation library.
  - TypeScript: A statically typed superset of JavaScript that compiles to plain JavaScript.

  - **Styling:**
  - Tailwind CSS: A utility-first CSS framework that provides low-level utility classes to build custom designs.
  - Aceternity UI: A collection of reusable UI components built with Tailwind CSS, designed for rapid development and consistent styling.

- **Backend:**
  - Cloudflare Workers: A serverless execution environment that allows you to create lightweight, scalable backend applications.
  - Prisma: A modern database toolkit for TypeScript and Node.js that simplifies database access.
  - Postgres: A powerful, open-source relational database system.
  - JWT (JSON Web Tokens): A compact, URL-safe means of representing claims to be transferred between two parties securely.
  - Using WebCrypto for hashing passsword before storing in the database.

## Setup Instructions

### Frontend

1. Navigate to the `frontend` directory.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Access the development server at `http://localhost:3000`.

### Backend

1. Navigate to the `backend` directory.
2. Run `npm install` to install dependencies.
3. Set up your Postgres database and configure the connection in `prisma/schema.prisma`.
4. Run `npx prisma migrate dev` to apply migrations and generate Prisma client.
5. Run `npm run dev` to start the backend server.
6. Access the backend server at `http://localhost:8080`.

## 🔐 Authentication Flow

PenCraft uses JWT-based authentication:

1. After login, the server issues a JWT.
2. The JWT is stored in an HTTP-only cookie.
3. On subsequent requests, the JWT is sent in the cookie header.
4. The backend validates the token for access to protected routes.

## Additional Functionalities

### Bookmark Functionality

Users can bookmark their favorite posts for quick access.

### Search Functionality

Users can search for posts based on keywords or tags.

### Delete Bookmark with Confirmation Model

Users can delete bookmarks with a confirmation model to prevent accidental deletion.

###

## Image Upload Feature

Working on to supports image uploads, allowing users to enhance their blog posts with images. (Will add it after I get my credit card)

## Add rich text editor

Added jodit editor .

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<div align="center">
  <h2 style="font-size:3rem;">Our Contributors <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" alt="Red Heart" width="40" height="40" /></h2>
  <h3>Thank you for contributing to our repository</h3>
<a href="https://github.com/AkshitLakhera/PenCraft-Full-Stack-Blogging-Application/graphs/contributors">
<img src="https://contrib.rocks/image?repo=AkshitLakhera/PenCraft-Full-Stack-Blogging-Application"/>
</a>
<p style="font-family:var(--ff-philosopher);font-size:3rem;"><b> Show some <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" alt="Red Heart" width="40" height="40" /> by starring this awesome repository!
</div>

<center>
<h3 style="font-size:2rem;">
If you find this project helpful, please consider giving it a star! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/tarikul-islam-anik/main/assets/images/Star.png" width="30" height="30"></p>
</center>
