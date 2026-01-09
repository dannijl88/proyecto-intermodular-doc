# 3. Instalación

## 3.1 Requisitos

### **Requisitos mínimos del sistema:**

| Componente | Mínimo | Recomendado |
|------------|--------|-------------|
| **Node.js** | v14.x | v18.x |
| **NPM** | v6.x | v9.x |
| **RAM** | 512 MB | 1 GB |
| **Disco** | 100 MB | 500 MB |

### **Software necesario:**
```bash
# Verificar instalaciones
node --version
npm --version
git --version
```
## 3.2 Pasos de instalación
### 1. Clonar repositorio
git clone https://github.com/tu-usuario/taskmaster-pro.git
cd taskmaster-pro

### 2. Instalar dependencias
npm install

### 3. Configurar variables
cp .env.example .env

### 4. Iniciar aplicación
npm start

## 3.3 Variables de entorno
### Configuración principal
PORT=3000
NODE_ENV=development

### Base de datos (SQLite para desarrollo)
DB_PATH=./database.sqlite

### Email (opcional)
EMAIL_HOST=smtp.gmail.com
EMAIL_USER=tu-email@gmail.com
EMAIL_PASS=tu-contraseña

### Seguridad
JWT_SECRET=mi-clave-secreta-123
