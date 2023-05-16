# ✌️ Configurando IntelliJ & VSCode para GitHub Actions

En el vídeo hablamos sobre [JSON Schema Store](http://schemastore.org/json/)

## Particularidades del Visual Studio Code

El plugin a instalar es: [YAML](https://github.com/redhat-developer/vscode-yaml)
Y luego en nuestro fichero de configuración tendremos que poner algo similar a:

```json
"json.schemas": [
 {
  "fileMatch": [
   "ci.yml"
  ],
  "url": "http://json.schemastore.org/github-workflow"
 }
],
```

Donde el `ci.yml` será el nombre de nuestro fichero de WorkFlow
