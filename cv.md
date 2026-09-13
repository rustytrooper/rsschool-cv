# Diana Solovey
**Fullstack-developer (Trainee / Junior)**
 
📧 diansolo40@gmail.com 
📍 Minsk 
💻 [GitHub](https://github.com/rustytrooper) 


## About me
[An aspiring frontend developer with practical internship experience at an IT company. My primary goal is to become a top-tier web development specialist by creating useful, high-tech products. I am looking for a team of professionals where I can not only apply my skills (React, Next.js, TypeScript) but also learn daily from more experienced colleagues, adopting best engineering practices and architectural solutions. I am ready to dedicate my energy to product development, delivering value to the business and growing alongside a strong team.]

---

## Skils

| **Languages** | JavaScript (ES6+), TypeScript  |
| **Frameworks/ librares** | React, Next.js, Node.js (basic) |
| **Styling** | CSS3, Tailwind CSS, Styled Components, БЭМ |
| **Databases / API** | REST API, Swagger/OpenAPI, MongoDB, PostgreSQL (basic) |
| **Tools и VCS** | Git, GitHub, Webpack, Vite, Figma, Postman |
| **Methodologics** | Agile/Scrum, code reviews |

---

## Code examples

```javascript
import { useState, useEffect } from 'react';

const TodoList = () => {
  const [todos, setTodos] = useState([]);

  useEffect(() => {
    fetch('/api/todos')
      .then(res => res.json())
      .then(data => setTodos(data));
  }, []);

  return (
    <ul className="flex flex-col gap-2">
      {todos.map(todo => (
        <li key={todo.id} className="p-4 bg-white shadow rounded">
          {todo.title}
        </li>
      ))}
    </ul>
  );
};
```

---

## Work expirience

Courses at RS school (pre-school 2022, js/fe 2023, react 2025, js/fe 2025, node js 2025, react 2026, currently- fullstack 2026), trainersheep at Andersen, 2025

Projects:
💻 (https://github.com/rustytrooper/react2026Q2) - repo for react 2026 course with all projects
💻 (https://github.com/rustytrooper/NodeFileManagerApplication) - repo for node file manager app

---

## Language level - b2
