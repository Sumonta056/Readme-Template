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

<img src ="./assets/bg-1.jpg" width="95%">
</div>

## 💡 Overview

FixHub is a powerful and intuitive issue tracker built using Next.js and SQL, designed to streamline bug management and project tracking. With a focus on efficiency and user-friendliness, FixHub allows for seamless creation, viewing, updating, and deletion of issues. Key features include:

## ✨ Features

- **🔐 User Authentication and Access Control:** Secure login and personalized access levels ensure that only authorized users can manage or view issues.
- **🌍 Issue Assignment:** Creating, Viewing, Updating and Deleting Issues. Assign tasks to team members effortlessly, keeping everyone accountable and informed.
- **🔍 Advanced Filtering & Sorting:** Easily filter and sort issues to quickly find and prioritize tasks.
- **📄 Pagination & Analytics:** Navigate through large lists of issues with pagination and gain insights with charts and a comprehensive dashboard.
- **🎯 Production-Ready Optimization:** Built for speed and reliability, FixHub is optimized for production environments, ensuring smooth performance at scale.
- **🔧 Customization & Flexibility:** Tailor FixHub to your needs with customizable settings and configurations.
- **📱 Responsive Design:** Access FixHub on any device with a responsive design that adapts to various screen sizes.

Whether you're a solo developer or part of a large team, FixHub is the perfect tool for tracking and resolving issues with ease.🐞

## 👩‍💻 Tech Stack

- **Next.js**: A React framework for building server-side rendering and static web applications.
- **Auth.js**: Free and open source Authentication for the Web.
- **Hono**: A lightweight web framework for building server-side applications with TypeScript.
- **Drizzle ORM**: TypeScript-first ORM for type-safe database access.
- **React Query**: Data-fetching library for managing server-state in React applications.
- **Bun**: A fast JavaScript runtime that includes a package manager, task runner, and more.

## 📖 Sources and external API's

- [quran-json](https://github.com/risan/quran-json) to get the text of the quran in different languages
- [everyayah](https://everyayah.com) to get the audio each aya
- [quran-tafseer](http://api.quran-tafseer.com/en/docs) to get the tafseer
- [explorequran](https://www.explorequran.org) random ayah source

## 📦 Getting Started

To get a local copy of this project up and running, follow these steps.

### 🚀 Prerequisites

- **Bun**: Ensure you have Bun installed. Follow the [official Bun installation guide](https://bun.sh/docs/installation).
- PostgreSQL (or another supported SQL database)

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mo-hassann/nextjs-quran-app.git
   cd nextjs-quran-app
   ```

2. **Install dependencies:**

   Using Bun:

   ```bash
   bun install
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
   bun run drizzle-kit migrate
   ```

5. **Start the development server:**

   ```bash
   bun dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

### ✔ Running the app

- **Development mode:** `bun dev`
- **Production mode:** `bun run build && bun start`

## 🤝 Contributing

We welcome contributions to this project. Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch** (`git checkout -b feature/your-feature-name`).
3. **Make your changes** and commit them (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature-name`).
5. **Open a pull request**.

Please make sure to update tests as appropriate.

## 🐛 Issues

If you encounter any issues while using or setting up the project, please check the [Issues](https://github.com/mo-hassann/nextjs-quran-app/issues) section to see if it has already been reported. If not, feel free to open a new issue detailing the problem.

When reporting an issue, please include:

- A clear and descriptive title.
- A detailed description of the problem.
- Steps to reproduce the issue.
- Any relevant logs or screenshots.
- The environment in which the issue occurs (OS, browser, Node.js version, etc.).

## 📜 License

Distributed under the MIT License. See [License](/LICENSE) for more information.
