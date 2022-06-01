# Interview Scheduler
This is a single-page app built on React.js that allows users to book, edit or cancel interviews for each day of the week (Monday to Friday).
This app is online, you can visit it [here](https://competent-kepler-8ba31c.netlify.com).

## Screenshots
Regular view of appointments
!["Regular appointments"](https://github.com/JCyan90/scheduler/blob/master/docs/appointments.png?raw=true)

Form when creating/editing an interview
!["Create/Edit form"](https://github.com/JCyan90/scheduler/blob/master/docs/create_edit_form.png?raw=true)

Confirmation message before deleting an interview
!["Delete confirmation"](https://github.com/JCyan90/scheduler/blob/master/docs/delete_confirmation.png?raw=true)

## If you want to run the app locally
1. Fork this repository, then clone your fork of this repository.
2. Go to the [scheduler-api repository](https://github.com/NateBainer/scheduler-api) that contains the database and fork it, then clone your fork of this repository.
3. Install dependencies in both folders (scheduler & shceduler-api) using the `npm install` command.
4. Open two terminals, one for scheduler and the second for scheduler-api.
5. Run the both servers using the `npm start` command.
6. Go to <http://localhost:8000/> in your browser and tinker with the app.
7. (Optional): Run the Jest Test Framework using `npm test` in an other terminal.
8. (Optional): Run the Storybook Visual Testbed using `npm run storybook` in an other terminal.