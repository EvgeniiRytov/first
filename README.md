# ***My first project***
## ___Installing Angular___
1. ### To install the Angular CLI, open a terminal window and run the following command: 
    ```
    npm install -g @angular/cli
    ```
    On Windows client computers, PowerShell scripting is disabled by default. To allow PowerShell scripts to run, which is necessary for global npm binaries, you need to set the following parameters:
    ```
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
    ```
2. ### Create a workspace and an initial application
    You are developing applications in the context of the Angular workspace.

    To create a new workspace and an initial startup application
    
    1.Run the CLI ``ng new`` command and specify the name of ``my-app``, as shown here
    ```
    ng new my-app
    ```
    2.The ``ng new`` command asks for information about the features that need to be included in the source application. Accept the default values by pressing Enter or Return
    The Angular CLI installs the necessary Angular npm packages and other dependencies. It may take a few minutes.

    The command line interface creates a new workspace and a simple welcome application ready to launch.
 3. ### Launch the app 
    The Angular CLI includes a server where you can create and maintain your application locally.
    1.Navigate to the workspace folder, for example ``my-app``.
    2.Run the following command:
    ```
    cd my-app
    ng serve --open

    ```

