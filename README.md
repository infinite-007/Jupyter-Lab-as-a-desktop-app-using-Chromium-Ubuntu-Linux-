# Jupyter-Lab-as-a-desktop-app-using-Chromium-Ubuntu-Linux
Running jupyter as chrome app is not possible by changing the jupyter-config file as mentioned in various internet blogs. Probably Chromium being a snap app and due to snap's limitation, it cannot access the runtime file of Jupyter-lab. The other way is to run few commands into the terminal which is a bit of hassle.

With the help of a .desktop file in Ubuntu/linux one can put those commands as a script so that with double click, without opening terminal and typing, one can easily open jupyter as a chromium app. In this repository I have uploaded the .desktop file. Just download it and place it in your desktop and allow launching.

You can also edit the file in any editor. For getting an icon of your launcher replace <user> in the icon field accordingly.

If you close your browser accidently the sever and process would continue running. If you want to terminate the process relaunch it and click on the 'shut down' option in jupyter-lab under file menu.

To relogin into a logged out session you would be asked for a token which you can find it by running the command "jupyter-lab list" in the terminal.

For understanding the command in the 'Exec' field in the .desktop file, just google them and you will get to know.
