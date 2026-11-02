# React Attendance App
welcome to my app , this app use for manage attendance of teachers and students.

##Feature 
- Teacher and student login
- Mark attendance (present, absent, late, excused) for each class
- View attendance history by day, week, or month
- Manage students, teachers, and classes
- Attendance reports and summaries
- Export attendance data (CSV/Excel)
- Responsive design for desktop, tablet, and mobile.
##Tech Stack
- [React](https://react.dev)
- [Vite](https://vitejs.dev) (or Create React App)
- [React Route](https://reactroute.com/) for navigation
- [Axios](https://axios-http.com) for API requests
- CSS / Tailwind CSS for styling

> Update this list to match the libraries your project actually uses.

## Screenshots

| Dashbord | Take Attendance |
| ![Dashboard](./screenshots/dashboard.png) | ![Attendance](./screenshots/attendance.png) |

## Getting Started

## Prerequisites

- Node.js 18 or higher
- npm, yarn, or pnpm

### Installation

  ``` bash
  git clone https://github.com/your-username/your-repo.git
  cd your-repo
  npm install
  ```
### Run the app

  ```bash
  npm run dev
  ```

the open http://localhost:5173 in your browser.
(If you use Create React App, run `npm start` and open http://localhost:3000.)

### Build for production 

```bash
npm run build
```

## Environment Variables

Create a `.env` file in the project root:

```
VITE_API_URL=http://localhost:8000/api
```

## Project Structure

```
src/
├── components/   # Reusable UI components (tables, buttons, forms)
├── pages/        # Pages: Login, Dashboard, Attendance, Reports
├── hooks/        # Custom React hooks
├── services/     # API calls
├── context/      # Auth and global state
├── assets/       # Images and icons
├── App.jsx
└── main.jsx
```
## How to Use

1. Log in as a teacher or admin.
2. Choose a class and date.
3. Mark each student as present, absent, late, or excused.
4. Save the attendance.
5. Open **Reports** to review attendance history and export it.

## User Roles

| Role    | What they can do                                      |
| ------- | ----------------------------------------------------- |
| Admin   | Manage teachers, students, classes, and view all data |
| Teacher | Take attendance and view reports for their classes    |
| Student | View their own attendance record                      |

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contact

Your Name – your.email@example.com
Project link: https://github.com/your-username/your-repo
