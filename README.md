# M133 Kanban Board
#### Description
This is the kanbard board project for our school module M133

#### Group Members
* Aleksandar Mesaros
* Florian Beqiraj

#### Project Structure
* Frontend Module (01_frontend)
* Backend Module (02_backend)

#### Requirments
* Deno v1.4.6 (if not installed, instructions gonnna be given)
* IDEA (Preferably Visual Studio Code)

#### Setup
1) Open this project in VS Code.
2) Install Deno
I. Open new terminal in VS Code
II. Run following command: 
For Windows: ```iwr https://deno.land/x/install/install.ps1 -useb | iex``` 
For Linux ```curl -fsSL https://deno.land/x/install/install.sh | sh```
III. If needed, upgrade to 1.4.6: ```deno upgrade --version 1.4.6```

#### Run Project
1) Open "kanban.html"
2) Run following command in terminal: ```deno run --allow-net 02_backend/kanban.js```

#### Use Kanban Board
1) Click on the + symbol to add a new task-item
2) Specify a name and click on "Create"
3) Drag the task-items to where ever you want
3) To delete a task, click on "Delete"