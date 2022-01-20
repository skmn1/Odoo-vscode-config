Odoo developers struggle a lot, since testing every change after modifying the python part of the project requires a restart of the odoo service from the task manager and then, an upgrade of the application from the app page.
In this project, we will help you not only to start, restart, and close the odoo service from the Visual Studio Code editor, but also debug the python part.



1.  After opening **VSCode**, from the top menu, select run -> **add configuration**, then chose **python file**. That will generate the launch.json file with a default content
![config](https://github.com/skmn1/Odoo-vscod-config/blob/main/addconfig.PNG)
1.  Copy/paste the content of the launch.json file given in the code section of this project (change the paths of the required files if necessary)

1.  Now find the file odoo.conf under the "odoo xx/server" folder. Open it and comment the line "_logfile = C:\Program Files (x86)\Odoo 12.0\server\odoo.log_" by adding a # at the beginning of the line (python comment)
![odooconffile](https://github.com/skmn1/Odoo-vscod-config/blob/main/odooconf.PNG)

1.  Stop the odoo service from the task manager

1. Now we are good to go, you can run the service from vs code by clicking the run button (the green triangle, see the following screenshot)
![run](https://github.com/skmn1/Odoo-vscod-config/blob/main/run1.PNG)

1. Refresh your odoo tab in your browser and check if everything works fine

1. In order to debug your application, create a breakpoint and then rerun the service (see the screenshot below)
![debug](https://github.com/skmn1/Odoo-vscod-config/blob/main/debug.PNG)
