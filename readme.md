
# Example Project setup using VS Code development Container and pipenv
This provides the starting point for setting up a vs code docker development container using pipenv

## Starting development container in VS Code
- Open folder

- Adjust Docker image that is used as the starting point in Dockerfile (currently: "python:3.8-slim" could be adjusted when tesorflow or pytorch is required)

- Adjust the required packages in the "Pipfile" 

- Build the contain and open as development container 

    ```(Strg+Shift+P): >Remote-Containers: Open Folder in Container```


## Update dependencies
- To add packages update Pipfile and then run:     
    ```pipenv install --dev```
