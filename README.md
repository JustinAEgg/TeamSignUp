<h1 align= "Center">Team Sign Up Web Application
</h1>

<table border = "1">
    <tr>
        <td align="center">
        The Team Sign Up website was a project I worked that was planned to be used by the university I attended, UTD. The goal was to create a streamlined experience for students to create groups and choose projects for their computer science project course as there was no alternative at the moment and teams have to be formed individually through their sole efforts.
        </td>
    </tr>
</table>

<h2> Technologies Used </h2>

- HTML & CSS
- EJS
- Node.js & Express.js
- mySQL

<h2> Screenshots </h2>
Screenshots of some the main pages:
![Screenshot 2024-05-07 060506](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/e2d0b5bb-0f08-4d11-8b42-b3f651810a92)
![Screenshot 2024-05-07 060638](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/257fb4d1-1e88-4f40-9374-40f7be1ad615)
![Screenshot 2024-05-07 063524](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/145ccc29-7621-40a0-b9fd-9935e7e6f96f)
![Screenshot 2024-05-07 063547](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/43d1bb79-10ba-4f43-a7d2-cc0204c47907)
![Screenshot 2024-05-07 063627](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/20642ae4-13d4-43b2-b486-6670bd28f85b)





<h2> To Run </h2>
Assuming you have already forked, cloned, and navigated to the project on your own system:
 
### MYSQL Configuration

| Variable Name   | Description                                           |
|-----------------|-------------------------------------------------------|
| MYSQL_HOST      | The host of the MySQL database.                       |
| MYSQL_USER      | The username for accessing the MySQL database.        |
| MYSQL_PASSWORD  | The password for accessing the MySQL database.        |
| MYSQL_DATABASE  | The name of the MySQL database to connect to.         |
| SESSION_SECRET  | Text                                                  |

### Email Configuration with MailTrap

![Screenshot_2024-04-12_at_12 02 27_PM](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/1060b07c-8203-45ce-a85d-e80108d5cbdb)
Screenshot provided for where to look.
| Variable Name   | Description                                           |
|-----------------|-------------------------------------------------------|
| EMAIL_USER      | The username for accessing the email service.         |
| EMAIL_PASSWORD  | The password for accessing the email service.         |
| EMAIL_HOST      | The host address of the email service.                |
| EMAIL_PORT      | The port number for connecting to the email service.  |

### Other Configuration

| Variable Name   | Description                                           |
|-----------------|-------------------------------------------------------|
| ADMIN_PASSWORD  | The password for the initial admin account in the database. The email is admin@example.com. |

## To Run
1. Create a .env file with the following variables in the table above.

2. Run: node main

3. (optional) Run Dummy Data (fullDummyDataNOTFINAL.sql) We need to initialize admin first with running main.js to not mess it up when we run the dummy data.

