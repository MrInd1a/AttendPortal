# AttendPortal

## Running Locally 
- Clone the repository
- Run `npm i`
- Run `npx expo start` and follow the instructions on the terminal

---


# Instructions

- In this project, an application has beeen developed which can be used to save time in taking attendance.
- It should work with a unique code which was set by the attendance taker and will be announced to
  all the attendees.
- Implementation has been done at both server side and the client side.
- User Types:

  1. Who wants to take the attendance
     a) Generally teacher. Teacher generates a unique code which will be given in class.
  2. Who gives the attendance
     a) Generally students. They enter the code given by the teacher in class to mark their attendance.
  3. Developer who update the software
     a) Maintains and creates the classes and other technical issues.

- *Requirements of student:*

  1. Students should get all the statistics of the classes he attended.
  2. Students can mark the attendance in the time span allotted. (only if code matches with the
     unique code generated by Teacher)

- *Requirements of teacher:*

  1. Get the statistics of all the classes he teaches.
  2. Start the attendance.
  3. Get possible proxies(Detect multiple attendances from the same IP)

- *Requirements of Admin:*

  1. Can create/delete/modify a course from the database.

- *Android application requirements:*
  1. Any user should have his own login/registration credentials.
  2. Option to login as student or teacher or admin
  3. Three different interfaces should be generated for all the three users for their tasks.

---
