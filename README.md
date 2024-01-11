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

## Deployment on Cyclic
Our backend services can be easily deployed on Cyclic. Follow these steps to set up the deployment:

1. **Visit Cyclic:**
   - Go to [Cyclic website](https://cyclic.sh/) and sign in or create a new account.

2. **Create a New Project:**
   - Once logged in, create a new project on Cyclic.

3. **Link GitHub Repository:**
   - During project creation, link your GitHub repository to the Cyclic project.
   - Cyclic will automatically detect the backend folder and set up the deployment.

4. **Configure Environment Variables:**
   - Set up any necessary environment variables in the Cyclic dashboard, such as database connection strings or API keys.

5. **Deploy Backend:**
   - Trigger the deployment process on Cyclic to deploy the backend services.
   - Cyclic will provide you with a unique URL for your deployed backend.

6. **Access Deployed Backend:**
   - Visit the provided URL to access your deployed backend.
   - Explore and interact with the API endpoints as needed.

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

