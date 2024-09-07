<div align= "center">

⭐ **If you like this project, please star the repository!** ⭐ <br>
------- 👇 **Template Demo Below** 👇 --------

<hr>
</div>

<div align="center">
<a href="https://github.com/Sumonta056/FixHub-Issue-Tracker-Website" target="blank">
<img src="./assets/chatBot.png" width="90" alt="Logo" />
</a>

<h2> Project Name : Readme Template </h2>

![](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![](https://img.shields.io/badge/Radix_UI-6200EE?style=for-the-badge&logo=radix-ui&logoColor=white)

<img src ="./assets/bg-3.webp" width="80%">

</div>

## 💡 Overview

FixHub is a powerful and intuitive issue tracker built using Next.js and SQL, designed to streamline bug management and project tracking. With a focus on efficiency and user-friendliness, FixHub allows for seamless creation, viewing, updating, and deletion of issues. Key features include:

## ✨ Features

- **🔐 User Authentication:** Secure login with personalized access levels.
- **🌍 Issue Management:** Create, view, update, and delete issues; assign tasks to team members.
- **🔍 Filtering & Sorting:** Advanced options to quickly find and prioritize tasks.
- **📄 Pagination & Analytics:** Navigate large lists and gain insights with charts and dashboards.
- **🎯 Production Optimization:** Built for speed and reliability in production environments.
- **🔧 Customization:** Tailor settings and configurations to your needs.
- **📱 Responsive Design:** Access on any device with adaptive design.

Whether you're a solo developer or part of a large team, FixHub is the perfect tool for tracking and resolving issues with ease.🐞

## 👩‍💻 Tech Stack

- **Next.js**: A React framework for building server-side rendering and static web applications.
- **Auth.js**: Free and open source Authentication for the Web.
- **Hono**: A lightweight web framework for building server-side applications with TypeScript.
- **Drizzle ORM**: TypeScript-first ORM for type-safe database access.
- **React Query**: Data-fetching library for managing server-state in React applications.
- **Npm Package**: A fast JavaScript runtime that includes a package manager, task runner, and more.

## 📖 Sources and external API's

- [NASA](https://www.nasa.gov) for space exploration and research
- [National Geographic](https://www.nationalgeographic.com) for nature and science articles
- [Stack Overflow](https://stackoverflow.com) for programming questions and answers
- [Wikipedia](https://www.wikipedia.org) for a wide range of information on various topics

## 📦 Getting Started

To get a local copy of this project up and running, follow these steps.

### 🚀 Prerequisites

- **Node.js** (v16.x or higher) and **npm** or **yarn**.
- **Npm** If you prefer using npm for package management and running scripts.
- **PostgreSQL** (or another supported SQL database).

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sumonta056/readme-template.git
   cd readme-template
   ```

2. **Install dependencies:**

   Using Npm:

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following variables:

   ```env
   NEXT_PUBLIC_APP_URL=http://localhost:3000

   #database
   DATABASE_URL=your_database_url
   DATABASE_SECRET=your_database_secret
   DRIZZLE_DATABASE_URL=your_database_url_for_drizzle

   #auth
   AUTH_SECRET=any_random_secret
   ```

4. **Run database migrations:**

   Ensure your database is running and then run:

   ```bash
   npm run drizzle-kit migrate
   ```

5. **Start the development server:**

   ```bash
   npm run dev
   ```

## 📖 Usage

### ✔ Running the Website

- **Development mode:** `npm run dev`, `yarn dev`, or `bun dev`.
- **Production mode:** `npm run build && npm start`, `yarn build && yarn start`, or `bun run build && bun start`.

> Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

### 📃 API Documentation

The API documentation for this application is available at [http://localhost:3000/api/docs](http://localhost:3000/api/docs). It details all endpoints and their usage.

## 🤝 Contributing

We welcome contributions to this project. Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch** (`git checkout -b feature/your-feature-name`).
3. **Make your changes** and commit them (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature-name`).
5. **Open a pull request**.

Please make sure to update tests as appropriate.

## 🐛 Issues

If you encounter any issues while using or setting up the project, please check the [Issues]() section to see if it has already been reported. If not, feel free to open a new issue detailing the problem.

When reporting an issue, please include:

- A clear and descriptive title.
- A detailed description of the problem.
- Steps to reproduce the issue.
- Any relevant logs or screenshots.
- The environment in which the issue occurs (OS, browser, Node.js version, etc.).

## 📜 License

Distributed under the MIT License. See [License](/LICENSE) for more information.
