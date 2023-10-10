Easy Start Kit for vue3

Contains the following packages and has completed the operation test
```
npm install
```
```
npm run dev
```

``eslint`` 
``prettier``
``axios`` 
``tailwindCSS`` 
``pinia`` 
``vueRouter`` 
``vueUse`` 
``vueMotion`` 
installed

.eslintrc.cjs and tailwind CSS, mian.js operation for vueMotion is complete. Need to edit settings.json in vscode to avoid conflict
```
setting.json

  "eslint.codeActionsOnSave.rules": null,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "markdown"
  ],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
```

vite port setup ``host: 127.0.0.1`` ``port: 3000`` in package.json
