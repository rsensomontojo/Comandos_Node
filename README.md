# Comandos Node / Node.js Cheat Sheet

## 📉 Información básica de Node.js
Node.js es un entorno de ejecución para JavaScript en el servidor. Estos son algunos comandos útiles para trabajar con Node.js.

| Comando | Descripción |
|---------|------------|
| `node -v` | Muestra la versión instalada de Node.js. |
| `npm -v` | Muestra la versión de npm instalada. |
| `npx -v` | Muestra la versión de npx instalada. |
| `node` | Inicia un REPL interactivo de Node.js. |

---

## 📦 Gestión de paquetes con npm/yarn
Node.js usa npm o yarn para la gestión de paquetes y dependencias en proyectos.

| Comando | Descripción |
|---------|------------|
| `npm init` / `yarn init` | Crea un `package.json`. |
| `npm install <paquete>` / `yarn add <paquete>` | Instala un paquete en el proyecto. |
| `npm install -g <paquete>` / `yarn global add <paquete>` | Instala un paquete globalmente. |
| `npm update` / `yarn upgrade` | Actualiza los paquetes instalados. |
| `npm uninstall <paquete>` / `yarn remove <paquete>` | Elimina un paquete del proyecto. |

---

## 👨‍💻 Gestión de scripts en Node.js
Los scripts en `package.json` permiten automatizar tareas en el desarrollo.

| Comando | Descripción |
|---------|------------|
| `npm start` | Ejecuta el script `start` definido en `package.json`. |
| `npm run <script>` | Ejecuta un script personalizado definido en `package.json`. |
| `npm test` | Ejecuta el script de pruebas. |

---

## 📊 Monitoreo y depuración
Comandos para analizar y depurar aplicaciones en Node.js.

| Comando | Descripción |
|---------|------------|
| `node --inspect <archivo>` | Inicia Node.js con la herramienta de inspección. |
| `npm ls` / `yarn list` | Lista todas las dependencias instaladas. |
| `npm outdated` | Muestra paquetes desactualizados. |

---

## 🛠️ Limpieza y mantenimiento
Comandos para mantener un entorno limpio y sin errores.

| Comando | Descripción |
|---------|------------|
| `npm cache clean --force` | Limpia la caché de npm. |
| `rm -rf node_modules package-lock.json && npm install` | Elimina `node_modules` y reinstala dependencias. |
| `npm dedupe` | Elimina paquetes duplicados en `node_modules`. |

---

### 🚀 Con estos comandos, gestionar proyectos Node.js será mucho más fácil. 💪

