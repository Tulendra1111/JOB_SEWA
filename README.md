# JobSewa

JobSewa is a unique e-job portal designed to directly connect laborers such as plumbers, electricians, carpenters, and other similar professionals with job employers. The platform provides better accessibility and more opportunities for local workers, enabling them to connect directly with potential employers quickly and efficiently.

## Features 🔥

- **User Authentication**
  - SignIn / SignUp
  - Forgot Password functionality
  - JWT validation for authorized requests
- **Job Management**
  - Post a Job
  - View All Jobs
  - View Job Details
  - Bookmark Jobs
  - Track Bookmarked Jobs in a DataTable
  - Track Applied Jobs in a DataTable
  - Track Posted Jobs and view Submitted Applications
  - Accept/Reject Applications with status updates
- **CV Management** (Only in local environment due to Vercel limitations)
  - View or download Applicant CVs

## Tech Stack 🛠

- **Frontend:** Next.js, Tailwind CSS
- **State Management:** Redux Toolkit
- **Validation:** Joi
- **Database:** MongoDB
- **API Fetching:** SWR Hooks
  
<h3 align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png">
</h3>

## About JobSewa

JobSewa directly connects employers with skilled workers such as painters, electricians, carpenters, and more, primarily serving the VIT Bhopal remote areas and beyond. By simplifying the hiring process, it aims to provide job opportunities to those who may struggle due to socio-economic conditions, allowing them to secure work and provide for their families.

### Categories of Workers :
- Painters
- Daily Wage Workers
- Plumbers
- Electricians
- Carpenters
- Mechanics
- Housemaids
- Drivers

### Job Seekers' Actions :
- Register, edit, or delete profiles
- Receive notifications for matching job opportunities

### Employers' Actions :
- Create, edit, and delete profiles
- Search for job seekers based on skill set, location, and availability
- Contact job seekers directly through the platform

### NGO Integration :
NGOs can create profiles, post job openings, and send notifications to registered workers.

### Dashboard Features :

- Track the status of job applications
- Receive notifications about job openings and application updates

### Working Principle : Login or Register and User Authentication

1. **SignUp/Login:** Users can sign up to access the platform and log in using their credentials.
2. **Job Seekers:** Registered workers can edit their profiles and receive job alerts based on their location and skills.
3. **Employers:** Employers can search for job seekers based on criteria like location and skill set.

<h3 align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png">
</h3>

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DB_URI` = Your mongoDB URL

`JWT_SECREAT` = Your custom JWT_SECREAT key

`NEXT_PUBLIC_API_BASE_URL` = Base URL for localhost => http://localhost:3000

----------


## Installation
Install my-project with npm
```bash
  npm install
  npm run dev (for development server)
  npm run build (for Production)
  npm run preview (To View Production Server )
```

----------


```javascript

if (youEnjoyed) {

    starThisRepository();
}

```

----------


# Epics-Project-Jobsearch
