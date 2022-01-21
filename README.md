# Track It

An application to help the user track their daily habits, where it's possible to sign-up and sign-in to create a personal space! <br/>
First time using libs like ```react-circular-progressbar``` and ```dayjs```!

## Table of Contents

- [Overview](#overview)
  - [About](#about)
- [Built with](#built-with)
- [How to run](#how-to-run)
- [Author](#author)

## Overview

<div align='center'>
  <img style='ustify-content: center' src='/src/assets/img/TrackIt.gif' />
</div>

<br />


### About

This app has the following features:
  - Enables the user to sign in their account
  - In case they don't have any, it's possible to create one in the sign up page
    - To sign up, the user needs to inform their Email, Password, Name and an valid URL image chosen by them.
  - After logging in, the ```TodayPage``` is shown, in which the user can:
    -  Check their daily habits, if they have any
    -  Click on the checkmark to mark it as done in that day
    -  Track their current streak and record of days that task/habit has been done
    -  And shows the user their daily progress in a circular progress bar on the botton center of the page
  - In the case the user has no habits to be tracked, they can go to the ```HabitsPage```, being able to:
    - Create their habits
    - Choose the days to do the habit
    - Save or Cancel the habits' creation
    - And delete the habit by clicking on the trashcan icon
  - Besides that, on the ```HystoryPage``` the user can track their progress on a month calendar, where it's possible to track the days the habis have been done or not
    - <i>To be implemented</i>

## Built with

The following tools and libs were used in the construction of the project: <br />

<p>
  <img style='margin: 5px' src='https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E'>
  <img style='margin: 5px' src='https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white'>
  <img style='margin: 5px' src='https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/axios%20-%2320232a.svg?&style=for-the-badge&color=informational'>
  <img style='margin: 5px;' src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
  <img style='margin: 5px;' src='https://img.shields.io/badge/styled-components%20-%2320232a.svg?&style=for-the-badge&color=b8679e&logo=styled-components&logoColor=%3a3a3a'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/react-dayjs%20-%2320232a.svg?&style=for-the-badge&color=fe5f4c&logo=react&logoColor=%FE5F4C'>  
  <img style='margin: 5px;' src='https://img.shields.io/badge/react-circular_progressbar%20-%2320232a.svg?&style=for-the-badge&color=3E98C7&logo=react&logoColor=%3E98C7'>
  <img style='margin: 5px;' src="https://img.shields.io/badge/react-app%20-%2320232a.svg?&style=for-the-badge&color=60ddf9&logo=react&logoColor=%2361DAFB">
  <img style='margin: 5px;' src="https://img.shields.io/badge/react_router%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB">
  
</p>

## How to run

1. Clone this repository

2. Install dependencies
```bash
npm i
```

3. Run the app with
```bash
npm start
```

<!-- 4. You can optionally build the project running
```bash
npm run build
``` -->

4. Finally, access http://localhost:3000 (the port ':3000' is subjected to changes) on your favorite browser (unless it is Internet Explorer. In this case, review your life decisions)

## Author


