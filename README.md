# React-Lab-Exercise-1-Understanding-React-File-Structure
# Name: Dakshinamurthy.V
# Roll no: 2305001006
# Department: CSE
# AIM
To create a React application using Vite, understand its file structure, and develop reusable components.
# PROGRAM
i) Student.jsx
```
function Student() {
 return (
 <div>
 <h2>Student Details</h2>
 <p>Name: Dakshinamurthy.V </p>
 <p>Register Number: 2305001006</p>
 <p>Department: CSE</p>
 </div>
 );
}
export default Student;
```
ii) Course.jsx
```
function Course() {
 return (
 <div>
 <h2>Course Details</h2>
 <p>Course: Web Technology</p>
 <p>Semester: VII</p>
 <p>Credits: 4</p>
 </div>
 );
}
export default Course;
```
iii) Faculty.jsx
```
function Faculty() {
 return (
 <div>
 <h2>Faculty Details</h2>
 <p>Name: Dr. Ajith Kumar</p>
 <p>Department: AIDS</p>
 <p>Designation: Professor</p>
 </div>
 );
}
export default Faculty;
```
iv) App.jsx
```
import Student from "./components/Student";
import Course from "./components/Course";
import Faculty from "./components/Faculty";
import "./App.css";
function App() {
 return ( <div className="container">
 <h1>Student Information System</h1>
 <Student />
 <Course />
 <Faculty />
 </div>
 );
}
export default App;
```
v) App.css
```
.container {
 text-align: center;
 padding: 30px;
 font-family: Arial, sans-serif;
}
.container h1 {
 color: #1976d2;
}
.container h2 {
 color: #333333;
}
.container p {
 color: #555555;
 font-size: 16px;
}
.container > div {
 border: 1p
x solid #cccccc;
 border-radius: 8px;
 padding: 20px;
 margin: 20px auto;
 max-width: 300px;
 background-color: #f5f9ff;
}
```
# OUTPUT
<img width="1024" height="354" alt="image" src="https://github.com/user-attachments/assets/10f6bf40-4877-4c37-b69c-328c0998c4bb" />

<img width="1024" height="532" alt="image" src="https://github.com/user-attachments/assets/e4bee552-56b5-4ef4-ae30-bc88fd520e14" />

