  
Developer Tooling:
Visual Studio Code as IDE
Github Repo for PR and commenting for preserving comments
VS code Extension (OpenAPI (Swagger) Editor, openapi-designer for schema resolution)
OpenAPI (Swagger) Editor: Setup Preview to SwggerUI(default) or Redoc
Live Share for live collaboration and commenting and editing will not preserve any comments
To change to ReDoc (cmd + ,) in vs code to open preferences and setting and search for OpenApi

From root api sec file (opeapi.yaml) Cmd +shift+ P > Openapi Designer: Compile Schema to generate resolved openapi json


Steps to manually configure in your own repository

1. Download opensource swagger UI distribution: https://github.com/swagger-api/swagger-ui/releases
2. Extract the contents and copy the "dist" directory to the root of your repository.

Move the file "index.html" from the directory "dist" to the root of your repository.
