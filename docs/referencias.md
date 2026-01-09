# 7. Referencias y Recursos

## 7.1 Enlaces útiles

### **Repositorios y documentación:**

- **📁 Repositorio GitHub:** [github.com/tu-usuario/taskmaster-pro](https://github.com/tu-usuario/taskmaster-pro)
- **📚 Documentación API:** [api.taskmaster.example.com/docs](https://api.taskmaster.example.com/docs)
- **🐛 Reportar bugs:** [github.com/tu-usuario/taskmaster-pro/issues](https://github.com/tu-usuario/taskmaster-pro/issues)

### **Tecnologías utilizadas:**

- **Node.js:** [nodejs.org/es/docs](https://nodejs.org/es/docs)
- **React:** [es.reactjs.org/docs](https://es.reactjs.org/docs)
- **Express:** [expressjs.com/es](https://expressjs.com/es)
- **SQLite:** [sqlite.org/docs.html](https://sqlite.org/docs.html)

## 7.2 APIs utilizadas

### **APIs internas desarrolladas:**

| Endpoint | Método | Descripción | Ejemplo de uso |
|----------|--------|-------------|----------------|
| `/api/tareas` | GET | Obtener todas las tareas | `fetch('/api/tareas')` |
| `/api/tareas` | POST | Crear nueva tarea | `fetch('/api/tareas', {method: 'POST', body: {...}})` |
| `/api/tareas/:id` | PUT | Actualizar tarea | `fetch('/api/tareas/123', {method: 'PUT', body: {...}})` |
| `/api/tareas/:id` | DELETE | Eliminar tarea | `fetch('/api/tareas/123', {method: 'DELETE'})` |
| `/api/auth/login` | POST | Iniciar sesión | `fetch('/api/auth/login', {method: 'POST', body: {email, password}})` |

### **Código ejemplo de consumo:**
```javascript
// Ejemplo: Obtener tareas pendientes
async function getPendingTasks() {
  try {
    const response = await fetch('/api/tareas?estado=pendiente');
    const tareas = await response.json();
    return tareas;
  } catch (error) {
    console.error('Error obteniendo tareas:', error);
    return [];
  }
}
```
## 7.3 Documentación externa

### Guías y tutoriales consultados

#### Desarrollo Full Stack
- **Full Stack Open** – Curso completo de React y Node.js  
- **The Odin Project** – Ruta de aprendizaje Full Stack  

#### Buenas prácticas
- **Airbnb JavaScript Style Guide** – Estilo de código  
- **Conventional Commits** – Mensajes de commit estandarizados  

#### Seguridad
- **OWASP Top 10** – Vulnerabilidades web más comunes  
- **JWT Best Practices** – Uso seguro de JSON Web Tokens  

---

### Libros recomendados

| Título              | Autor               | Año  | Enlace |
|---------------------|---------------------|------|--------|
| Eloquent JavaScript | Marijn Haverbeke    | 2018 | eloquentjavascript.net |
| You Don't Know JS   | Kyle Simpson        | 2015 | github.com/getify/You-Dont-Know-JS |
| Clean Code          | Robert C. Martin    | 2008 | amazon.es/Clean-Code-Handbook-Software-Craftsmanship |

---

### Herramientas de desarrollo

| Herramienta              | Uso               | Enlace |
|--------------------------|-------------------|--------|
| Visual Studio Code       | Editor principal  | code.visualstudio.com |
| Postman                  | Testing de APIs   | postman.com |
| GitHub Desktop           | Control de versiones | desktop.github.com |
| DB Browser for SQLite    | Visualización de BD | sqlitebrowser.org |

---

### Comunidades y foros

- **Stack Overflow**  
  stackoverflow.com/questions/tagged/react  

- **Reddit – r/learnprogramming**  
  reddit.com/r/learnprogramming  

- **Discord JavaScript**  
  discord.gg/javascript  
