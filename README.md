# React Query Example

This project demonstrates how to use React Query (TanStack Query) for data fetching and state management in a React application, integrated with an AdonisJS backend API.

## Project Structure

- `adonis-api-backend/` - Backend API built with AdonisJS
- `react-query-example/` - Frontend React application using React Query

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd adonis-api-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database (if required) and run migrations:
   ```bash
   node ace migration:run
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

The backend will be running on `http://localhost:3333` (default AdonisJS port).

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd react-query-example
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install React Query:
   ```bash
   npm install @tanstack/react-query
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

The frontend will be running on `http://localhost:5173` (default Vite port).

## Features

- React Query for efficient data fetching and caching
- Tailwind CSS for styling (font sizes: `text-sm` for headings, `text-xs` for paragraphs, `text-base` for main headings)
- TypeScript support
- ESLint for code linting
- Vite for fast development builds

## Usage

1. Start both the backend and frontend servers as described above.
2. Open your browser and navigate to `http://localhost:5173`.
3. The React app will demonstrate various React Query features like:
   - Fetching data
   - Caching
   - Mutations
   - Error handling
   - Loading states

## API Endpoints

The backend provides the following endpoints (example):

- `GET /api/posts` - Fetch all posts
- `POST /api/posts` - Create a new post
- `PUT /api/posts/:id` - Update a post
- `DELETE /api/posts/:id` - Delete a post

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is licensed under the MIT License.