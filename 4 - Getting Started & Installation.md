## 💻 Getting Started

To get a local copy of this project up and running, follow these steps.

### ✔ Prerequisites

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