# Node.js & npm Command Cheat Sheet

Here’s a practical **Node.js & npm Command Cheat Sheet** 🧰⚡ — perfect for developers working with JavaScript, TypeScript, or full-stack frameworks like Next.js.

---

## 🟢 Node.js CLI Basics

| Command                       | Description                            |
| ----------------------------- | -------------------------------------- |
| `node -v`                     | Show Node.js version                   |
| `node script.js`              | Run a JavaScript file                  |
| `node`                        | Start Node REPL                        |
| `node --watch script.js`      | Auto-reload on file changes (Node 18+) |
| `node --inspect script.js`    | Debug with Chrome DevTools             |
| `node --trace-warnings`       | Show detailed warnings                 |
| `node --experimental-modules` | Enable ES modules (older versions)     |

---

## 📦 npm Essentials

| Command                       | Description                            |
| ----------------------------- | -------------------------------------- |
| `npm init`                    | Start interactive project setup        |
| `npm init -y`                 | Quick setup with defaults              |
| `npm install`                 | Install dependencies from package.json |
| `npm install package_name`    | Install a package locally              |
| `npm install -g package_name` | Install globally                       |
| `npm install package@version` | Install specific version               |
| `npm uninstall package_name`  | Remove a package                       |
| `npm update`                  | Update all packages                    |
| `npm outdated`                | Check for outdated packages            |
| `npm run script_name`         | Run a script from package.json         |
| `npm start`                   | Run the `start` script                 |
| `npm test`                    | Run the `test` script                  |

---

## 📁 Package Management & Lockfiles

| Command                   | Description                             |
| ------------------------- | --------------------------------------- |
| `npm list`                | Show installed packages                 |
| `npm list -g`             | Show global packages                    |
| `npm ls package_name`     | Show dependency tree for a package      |
| `npm audit`               | Security audit of dependencies          |
| `npm audit fix`           | Auto-fix vulnerabilities                |
| `npm ci`                  | Clean install from lockfile (for CI/CD) |
| `npm cache clean --force` | Clear npm cache                         |

---

## 🧪 Scripts in package.json

```json
"scripts": {
  "start": "node index.js",
  "dev": "nodemon index.js",
  "build": "webpack --config webpack.config.js",
  "test": "jest"
}
```

Run with:

```bash
npm run dev
npm run build
```

---

## 🔧 Useful Tools

| Tool      | Purpose                                   |
| --------- | ----------------------------------------- |
| `npx`     | Run CLI tools without installing globally |
| `nodemon` | Auto-restart Node app on changes          |
| `eslint`  | Linting JavaScript/TypeScript             |
| `ts-node` | Run TypeScript files directly             |
| `webpack` | Bundle JS/CSS assets                      |
| `vite`    | Fast frontend bundler                     |
| `pm2`     | Process manager for Node apps             |

---
