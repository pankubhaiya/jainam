# jainam

**technology stack**
**Front End : Angular**
**Backend : Nodejs**



**API endpoints :**

**1. Student and Instructor Management:**
- **Create Student Profile:**
  - POST `/api/students`
- **Get Student Profile:**
  - GET `/api/students/{student_id}`
- **Update Student Profile:**
  - PUT `/api/students/{student_id}`
- **Delete Student Profile:**
  - DELETE `/api/students/{student_id}`
- **List Instructors:**
  - GET `/api/instructors`
- **Create Instructor Profile:**
  - POST `/api/instructors`
- **Get Instructor Profile:**
  - GET `/api/instructors/{instructor_id}`
- **Update Instructor Profile:**
  - PUT `/api/instructors/{instructor_id}`
- **Delete Instructor Profile:**
  - DELETE `/api/instructors/{instructor_id}`
**2. Course Management:**

- **List Departments:**
  - GET `/api/departments`
- **Create Department:**
  - POST `/api/departments`
- **Get Department Details:**
  - GET `/api/departments/{department_id}`
- **Update Department:**
  - PUT `/api/departments/{department_id}`
- **Delete Department:**
  - DELETE `/api/departments/{department_id}`
- **List Courses in Department:**
  - GET `/api/departments/{department_id}/courses`
- **Create Course in Department:**
  - POST `/api/departments/{department_id}/courses`
- **Get Course Details:**
  - GET `/api/courses/{course_id}`
- **Update Course:**
  - PUT `/api/courses/{course_id}`
- **Delete Course:**
  - DELETE `/api/courses/{course_id}`

**3. Enrollment and Attendance:**
- **Enroll Student in Course:**
  - POST `/api/courses/{course_id}/enrollments`
- **List Enrolled Students in Course:**
  - GET `/api/courses/{course_id}/enrollments`
- **Mark Attendance for Student:**
  - POST `/api/courses/{course_id}/attendance`
- **Get Attendance for Student:**
  - GET `/api/courses/{course_id}/attendance/{student_id}`

**4. Assignment and Submission:**
- **Create Assignment:**
  - POST `/api/courses/{course_id}/assignments`
- **Get Assignment Details:**
  - GET `/api/courses/{course_id}/assignments/{assignment_id}`
- **Update Assignment:**
  - PUT `/api/courses/{course_id}/assignments/{assignment_id}`
- **Delete Assignment:**
  - DELETE `/api/courses/{course_id}/assignments/{assignment_id}`
- **Submit Assignment:**
  - POST `/api/courses/{course_id}/assignments/{assignment_id}/submissions`
- **Get Submission Status:**
  - GET `/api/courses/{course_id}/assignments/{assignment_id}/submissions/{student_id}`

**5. Course Dashboard:**
- **Course Dashboard Information:**
  - GET `/api/courses/{course_id}/dashboard`

**6. Automated Communication:**
- **Send Reminder:**
  - POST `/api/communication/reminders`
