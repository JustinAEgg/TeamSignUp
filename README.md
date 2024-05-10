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
![Screenshot 2024-05-07 060519](https://github.com/JustinAEgg/TeamSignUp/assets/116119742/224c3f17-1a4a-4c56-a221-00ed0ee9587e)





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

