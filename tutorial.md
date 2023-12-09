- ng new ngFlix --standalone=false
  -- (con scss, sin ssr)

- npm run start

- En la carpeta assets se añaden: logos, fonts, icons, etc

- Instalar extensiones vscode: "Angular Language Service"

- Instalar Prettier:
  -- Instalar extensiones vscode: "Prettier"
  -- Ejecutar comando: npm install prettier -D --save-exact
  -- Crear fichero: ".prettierrc" y ponerle el contenido que se indica en la url: "prettier.io/docs/en/configuration.html" , es decir:
  {
  "trailingComma": "es5",
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true
  }
  -- Pulsar en vscode: "ctrl + shift + p" y escribir y seleccionar: "Format Document"
  --

- Installing ESLint

- Extensions To Speed Up The Coding Productivity

==== Application Initialization ======

- Design Overview and Page Structure
  -- Header (No cambia al navegar entre páginas)
  --- Logo
  --- Navigation
  -- Page Content (SI Cambia al navegar entre páginas)
  -- Footer (No cambia al navegar entre páginas)

- Installing and Configuring Fonts (Google Fonts)
  -- Ir a Google Fonts Web Site -> Click en una font
