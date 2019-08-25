Install the recommended extensions.  If you closed the notifcation you can find it again here:
![Image](https://i.imgur.com/Yu6CVPI.png)

Install Docker.
>Windows: https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe

>Linux: Your package manager should have it.

Run ```docker run -d -p 8888:8080 plantuml/plantuml-server:tomcat``` to setup the PlantUML Server

>If you install Docker with VSCode running you may need to restart VSCode for the docker command to work.

Ensure each file for projects include <file>.c4.doc.puml to show that it is the c4 level documentation of that file.

>Press Alt + D to view .puml files in visualized mode in realtime.


Include <file>.doc.md if you need to elaborate on design thoughts regarding the file.  Good notes now make life easier later.  Particular implementation details should be in comments in code still.

>Press Ctrl + Shift + V to preview Markdown in realtime.

If you need a quick refresher on the C4 model you can check https://c4model.com/.

>Cheatsheet: https://c4model.com/assets/visualising-software-architecture.pdf