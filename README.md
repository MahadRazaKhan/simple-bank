# Simple Bank

A full-stack banking application built with Node.js, Express, and MySQL. It uses regional database sharding across four provinces of Pakistan, with JWT authentication, email verification, and a ledger-based transaction system.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/MahadRazaKhan/simple-bank/blob/main/ss01.png.png" alt="Login Page" width="400"/>
      <br/>
      <sub></sub>
    </td>
    <td align="center">
      <img src="https://github.com/MahadRazaKhan/simple-bank/blob/main/ss02.png.png" alt="Dashboard" width="400"/>
      <br/>
      <sub></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/MahadRazaKhan/simple-bank/blob/main/ss03.png.png" alt="Transaction" width="400"/>
      <br/>
      <sub></sub>
    </td>
    <td align="center">
      <img src="https://github.com/MahadRazaKhan/simple-bank/blob/main/ss04.png.png" alt="Ledger" width="400"/>
      <br/>
      <sub></sub>
    </td>
  </tr>
</table>

---

## Features

- User signup and login with JWT authentication
- Password hashing with bcrypt
- Email verification using Nodemailer
- Regional sharding across Punjab, Sindh, KPK, and Balochistan
- Metadata database for users and account routing
- Deposit and withdraw with row-level locking
- Transaction history
- Delete account with automatic logout
- Loading screen during authentication
- Responsive dark-themed UI

---

## Tech Stack

**Backend:** Node.js, Express, MySQL (mysql2), JWT, bcryptjs, Nodemailer, dotenv, CORS

**Frontend:** HTML5, CSS3, Vanilla JavaScript

**Database:** MySQL 8 with five databases (one metadata, four regional)
