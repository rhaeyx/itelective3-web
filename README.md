<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/rhaeyx/itelective3-web">
    <img src="images/logo.jpg" alt="Logo" width="200" height="200">
  </a>
<h1 align="center">Ateneo de Davao University - Business Management</h1>

<hr />

<h1 align="center">Attendance Monitoring System</h1>
<p align="center">
    A system that would automatically record attendance for students within the Ateneo de Davao - Business Management cluster.
    <br />
</p>
</div>

<hr />

## What?

The Attendance Monitoring System manages the checking, recording, and reporting of attendance for the Ateneo de Davao University - Business Management cluster. The program records and verifies the attendance of a student / faculty through the input of the faculty using the system. The system will then record all of the details regarding the attendance (time, date, etc.). The system will also feature a "generate report" where reports will be generated based on the parameters provided by the administrator.

<hr />

## What is it made with?

### FERN: Firestore - Express JS - React JS - Node JS

<p float="left" align="middle">
<a href="https://firebase.google.com/docs/firestore">
<img src="https://static.cdnlogo.com/logos/f/45/firestore.svg" width="24%" />
</a>
<a href="https://expressjs.com/">
<img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" width="24%" /> 
</a>
<a href="https://reactjs.org/">
<img src="https://static.cdnlogo.com/logos/r/63/react.svg" width="24%" />
</a>
<a href="https://nodejs.org/">
  <img src="https://static.cdnlogo.com/logos/n/49/node-js.svg" width="24%" />
</a>
</p>

## What else?

- Admin Panel

  - Manage Users (Add, Delete)
  - Manage Attendance (A)

- User Dashboard

  - Student
    - Manage account
    - View attendance
  - Faculty
    - Manage account
    - Add attendance
    - Modify attendance
    - Delete attendance

- Attendance Recorder

  - Records the attendance details.
    - When
    - Where
    - Who

+++ for version 2.0

- Report Generator
  - Generate a report based on parameters
    - "Who arrived in between 10:30 AM to 12:30 AM"
