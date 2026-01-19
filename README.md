# React + Supabase Project

This repository is a React application that connects to Supabase for backend services like database and authentication.

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository
```bash
git clone <your-repo-url>
````

### 2. Create your `.env` file

Copy the example env file and update it with your Supabase credentials:

```bash
cp .env.example .env
```

Then open `.env` and add your Supabase keys:

```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 3. Install dependencies

```bash
npm install
```

### 4. Run the development server

```bash
npm run dev
```

## 🧠 Notes

* Make sure you have a Supabase project set up.
* Your `.env` file should **not** be committed to version control.

## 📦 Tech Stack

* React
* Supabase
* Vite (or your chosen React setup)
