# Configure and run Odoo inside the VS Code editor
Run odoo service directly from the vs code editor

From the top menu, select run -> add configuration file

That will generate the launch.json file with its default content

Copy paste the content of the launch.json file given (the targeted files like python.exe, otherwise give the right path)

Now find the file odoo.conf under the odoo xx folder, the comment the line log file

Stop the odoo service from the task manager 

Now we are good to go, you can run the service from vs code by clicking the run button (the green triangle)

Refresh your odoo tab in your browser in check if everything works fine



