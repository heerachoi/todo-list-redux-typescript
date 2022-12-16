<h1 align="center"> Todolist with Redux </h1> 
<h5 align="center"> Project Duration: 2022.12.13 - 12.15</h5>

<p align="center">
<img src="https://user-images.githubusercontent.com/29205152/208035136-1868a013-570b-4850-bc48-c164ad65d792.gif" alt="GIF" width="70%">
</p>

<h2>📖 Table of Contents</h2>
<ul>
  <li><a href="#about-the-project">📝 About The Project</a></li>
  <li><a href="#skills-stack">💡 Skills Stack</a></li>
  <li><a href="##project-link">📍 Project Link</a></li>
  <li><a href="#directory-layout">🗂 Directory Layout</a></li>
  <li><a href="#getting-started">🎯 Getting Started</a></li>
</ul>

</br>

<!-- Introduction -->
<h2 id="about-the-project">📝 About The Project</h2>
리덕스를 활용한 할일들을 추가, 삭제, 및 상세보기가 가능합니다.

</br>

<!-- Skills Stack -->
<h2 id="skills-stack">💡 Skills Stack</h2>
<p align="center">
<img alt="React" src ="https://img.shields.io/badge/react-282C34.svg?&style=for-the-badge&logo=react&logoColor=61DAFB"/> <img alt="Styled Components" src ="https://img.shields.io/badge/styled components-282C34.svg?&style=for-the-badge&logo=styledcomponents&logoColor=DB7093"/> 
</p>

</br>

<!-- Project Link -->
<h2 id="project-link">📍 Project Link</h2>
https://react-to-do-list-alpha.vercel.app/

</br>

<!-- Directory Layout -->
<h2 id="directory-layout">🗂 Directory Layout</h2>
<code>
📦src
 ┣ 📂app
 ┣ 📂component
 ┃ ┣ 📂Details
 ┃ ┃ ┣ 📜TopdoDetails.jsx
 ┃ ┃ ┗ 📜style.js
 ┃ ┣ 📂Form
 ┃ ┃ ┣ 📜Form.jsx
 ┃ ┃ ┗ 📜style.js
 ┃ ┣ 📂Header
 ┃ ┃ ┣ 📜Header.jsx
 ┃ ┃ ┗ 📜style.js
 ┃ ┣ 📂TodoItem
 ┃ ┃ ┣ 📜TodoItem.jsx
 ┃ ┃ ┗ 📜style.js
 ┃ ┗ 📂TodoList
 ┃ ┃ ┣ 📜TodoList.jsx
 ┃ ┃ ┗ 📜style.js
 ┣ 📂pages
 ┃ ┣ 📜Details.jsx
 ┃ ┣ 📜Home.jsx
 ┃ ┗ 📜style.js
 ┣ 📂redux
 ┃ ┣ 📂config
 ┃ ┃ ┗ 📜configStore.js
 ┃ ┗ 📂modules
 ┃ ┃ ┗ 📜todos.js
 ┣ 📂routers
 ┃ ┗ 📜Router.js
 ┣ 📜.DS_Store
 ┣ 📜App.jsx
 ┣ 📜index.css
 ┣ 📜index.js
 ┗ 📜setupTests.js
 </code>

</br>

<!-- Setting Up -->
<h2 id="setting-up">🎯 Setting Up</h2>
```sh
npx npx create-react-app todo-list-redux --template redux
cd todo-list-redux
npm start
```
