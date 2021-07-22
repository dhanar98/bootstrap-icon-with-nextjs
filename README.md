## 🔗 MEDIUM STORY LINK
[![MEDIUM](https://img.shields.io/badge/how_to_add_bootstrap_icons_in_nextjs-000?style=for-the-badge&logo=MEDIUM&logoColor=white)](https://medium.com/@dhanar98/how-to-add-bootstrap-icons-in-next-js-c691a21e7e4c)

## ➡️ Clone My Project

Clone  project to run this commands

**`step-1:`**

clone a 

[![github](https://img.shields.io/badge/github-ffd200?style=for-the-badge&logo=github&logoColor=black)](https://github.com/) 

project

```bash
git clone https://github.com/dhanar98/bootstrap-icon-with-nextjs.git
```

**`step-2:`**

Install

[![npm](https://img.shields.io/badge/npm-cc0a00?style=for-the-badge&logo=npm&logoColor=black)](https://npm.org/) 

Dependencies

```bash
npm install
```


**`step-3:`**

build a 

[![nextjs](https://img.shields.io/badge/next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/) 

project 

```bash
npm run build
```


**`step-4`**
  
start a 

[![nextjs](https://img.shields.io/badge/next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/) 

project

```bash
npm  start

(or)

npx next -p [portnumber]
E.X: npx next -p 1998
```

## 🥺 Issue:
If the project throws Es-lint issue while starting a project

Add the code in `next.config.js` file

```
module.exports = {
  extends: [
    'plugin:@next/next/recommended',
  ],
}
```
Repeat **Step-4**

**(OR)**

if it throws an issue already running in port 0:0:0:3000 port

```
lsof -ti:3000 | xargs kill -9
```

Repeat **Step-4**

Smile please 😁

Now the Issues are Solved.
