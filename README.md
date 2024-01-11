# Backend README

## Tech Stack
- Node.js
- Express
- MongoDB
- Packages:
  - nodemon
  - mongoose
  - express
  - dotenv
  - bcrypt
  - jsonwebtoken (jwt)
  - cors

## Installation
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the backend directory: `cd backend`
3. Install dependencies: `npm install`
4. Create a `.env` file based on the provided `.env.example` and configure it with your settings.
5. Run the development server: `npm run dev`

## API Documentation
### User Routes
- `/api/users/register` - Register a new user
- `/api/users/login` - Login a user and generate a JWT token

### Note Routes
- `/api/notes` - Get all notes
- `/api/notes/:id` - Get a specific note by ID
- `/api/notes/create` - Create a new note
- `/api/notes/:id/update` - Update a specific note by ID
- `/api/notes/:id/delete` - Delete a specific note by ID

## Database Structure
### Collections
- User Collection
- Note Collection

### Models
- UserModel
- NoteModel


## Contact Information
For questions or feedback, contact Prachi Verma at jiyasoni190800@gmail.com.

