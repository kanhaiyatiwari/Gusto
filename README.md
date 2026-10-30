# Payroll & HR Website (inspired by Gusto)

<p align="center">
  <img src="https://user-images.githubusercontent.com/107475338/217636606-5602a7e4-7d2d-4d56-a84f-5f47a3dc72bc.png" alt="Home page" width="750">
</p>

<p align="center">
  <a href="https://verdant-panda-50245c.netlify.app/"><b>Live demo</b></a> ·
  <a href="#setup--installation">Run locally</a> ·
  <a href="#screenshots">Screenshots</a>
</p>

## Project Description

A multi-page website for an online payroll, benefits and HR platform for small businesses, built as a recreation of the Gusto website. It covers the marketing pages (home, why Gusto, payroll, employee benefits, people advisory) and a working sign-up and sign-in flow that stores users in the browser.

Built in 5 days by a team of 5 at Masai School. **My part:** the Employee Benefits page and the People Advisory page.

## Tech Stack

| Area | Tools |
|---|---|
| Markup & styling | HTML5, CSS3 (Flexbox, custom web fonts) |
| Logic | JavaScript (ES6), DOM manipulation |
| Storage | Browser localStorage for sign-up and sign-in |
| Hosting | Netlify |

## Key Features

- Responsive marketing pages with a shared navbar and footer
- Sign-up with form validation; accounts saved in localStorage
- Sign-in that checks saved accounts and redirects on success
- Thank-you page after sign-up
- Reusable components for the navbar and footer

## Setup & Installation

No build step is needed.

1. Clone the repository
   ```bash
   git clone https://github.com/kanhaiyatiwari/Gusto.git
   cd Gusto
   ```
2. Open `index.html` in a browser, or serve the folder (recommended, so components load correctly):
   ```bash
   npx serve .
   ```
   or use the **Live Server** extension in VS Code.

## Screenshots

| Why Gusto | Payroll |
|---|---|
| ![Why Gusto](https://user-images.githubusercontent.com/107475338/217637447-e0d880b5-a711-4db1-b9f4-26913a674750.png) | ![Payroll](https://user-images.githubusercontent.com/107475338/217637533-8663fe65-98da-44aa-a39d-6e25591a1e41.png) |

| Employee Benefits | People Advisory |
|---|---|
| ![Employee Benefits](https://user-images.githubusercontent.com/107475338/217637643-824622c9-264b-4711-9e9a-5a8488a84eb8.png) | ![People Advisory](https://user-images.githubusercontent.com/107475338/217637794-e4b31e6e-0618-4f42-a4ed-3f512b753456.png) |

| Sign up | Sign in |
|---|---|
| ![Sign up](https://user-images.githubusercontent.com/107475338/217638125-5a713b70-8b89-4ce4-9341-0c8e4629367c.png) | ![Sign in](https://user-images.githubusercontent.com/107475338/217638171-af5c50d6-0aa7-4ac9-8745-7d53734ca2b0.png) |

## Team

- Amit Kumar Saini – [Portfolio](https://iamamitkumarsaini.github.io/)
- Shivendra Shrivastwa – [Portfolio](https://shivendra0852.github.io/)
- Kanhaiya Tiwari – [Portfolio](https://kanhaiyatiwari.github.io/)
- Pradeep Singh
- Shivalika Sharma

> Built for learning purposes. Gusto is a trademark of its owner; this project is not affiliated with it.
