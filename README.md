<p align="center">
  <a href="https://impensa.studio/">
  <img src="./client/public/images/media2.png" />
    </a>
</p>

<div align="center">

### Simple, effective expense management app.

</div>

[![StackShare](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/impensa/impensa)

## Impensa is an open-source expense management app

- See where all your money goes by easily adding and categorizing new expenses
- Analyze your expenditure using data visualization tools
- Export .xlsx report with all your expenses

## What's cool about this?

Impensa is an open-source project, meaning you can easily access needed app functional and modify lines of code.

We are an open-source alternative to products such as Mint, Simplifi or PocketGuard. Although the functionality of the app is not as advanced, we're designed to be more developer-friendly.

It has been made with love.

## Technologies

Let's talk about the architecture of this mono repo:

- **Full-stack JavaScript**: We use Node.js to power our servers, and React to power our frontend. Almost all of the code you'll touch in this codebase will be JavaScript.
- Here is a list of all the big technologies we use:
  - **PostgreSQL**: Object-relational database
  - **Express JS**: Our backend framework of choice
  - **React**: Frontend framework
  - **React Chart.js 2**: JavaScript library for Data Visualization
  - **Microsoft Azure**: To deploy React app

#### Folder structure

```sh
Impensa/
├── .github       # Files used by github
├── client        # React frontend
├── middleware    # Authorization middleware
├── routes        # Dashboard and authentication routes
├── utils         # JWT token generation
```

<details>
  <summary>Click to learn about code style</summary>

#### Code Style

We run Prettier on-commit, which means you can write code in whatever style you want and it will be automatically formatted according to the common style when you run `git commit`. We also have ESLint set up, although we've disabled all stylistic rules since Prettier takes care of those.

</details>

## Contributors👑

<a href="https://github.com/tmneth"><img src="https://avatars.githubusercontent.com/u/80415416?s=400&u=f561810823dc78213f14431aae7f2bd119a4ed90&v=4" width="50" height="50" alt=""/></a> <a href="https://github.com/richard96292"><img src="https://avatars.githubusercontent.com/u/68248740?v=4" width="50" height="50" alt=""/></a>
