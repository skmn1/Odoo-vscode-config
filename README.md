Odoo developers sturuggle a lot, since testing every change after modifiying the python part of the project requires a restart of the odoo service from the task manager and then an upgrade of the application from the app page.
In this projet, we will help you not only start, restart, and close the odoo service from the visual studio code editor, but also debug the python part.



After opening VSCode, from the top menu, select run -> add configuration

That will generate the launch.json file with its default content

Copy paste the content of the launch.json file given (the targeted files like python.exe, otherwise give the right path)

Now find the file odoo.conf under the odoo xx folder, the comment the line log file

Stop the odoo service from the task manager 

Now we are good to go, you can run the service from vs code by clicking the run button (the green triangle)

Refresh your odoo tab in your browser in check if everything works fine



