# Tutorials de ROS

# Instal·lació del ROS

Segueix les instruccions de la següent web per descargar i configurar el ROS:

http://wiki.ros.org/melodic/Installation/Ubuntu.

# Tutorial 1: Instal·lació i configuració del entorn ROS

Segueix el tutorial 1 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment

En aquest tutorial aprenem i validem que la instal·lació i configuració del programa ROS estigui correcte

# Tutorial 2: Navagació amb el sistema ROS

Segueix el tutorial 2 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/NavigatingTheFilesystem

En aquest tutorial aprenem a utilitzar les seguents comandes de ros:

```rospack | roscd | rosls```

# Tutorial 3: Creació d'un paquet ROS

Segueix el tutorial 3 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/CreatingPackage

En aquest tutorial aprenem a crear paquets en el ROS. En aquest cas creem un paquet anomenat "Begginner_tutorial".

Dins d'aquest paquet creem un fitxer "package.xml" el qual modifiquem una seria d'informació.

# Tutorial 4: Construim el paquet

Segueix el tutorial 4 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/BuildingPackages

En aquest tutorial realitzem la compilació per construir el paquet i veure com apareix la carpeta ```/build``` i ```/devel```

La compilació es similar que la del ```cmake``` pero amb ```catkin_make```

# Tutorial 5: Entendre els Nodes de ROS

Segueix el tutorial 5 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/UnderstandingNodes

En aquest tutorial aprenem a executar el ```roscore``` per poder visualitzar llistes dels nodes executant-se. En un dels punts del tutorial utilitzem la comanda ```rosrun turtlesim turtlesim_node``` per activar una finestra amb una pantalla blava i una tortuga

# Tutorial 6: Entendre els temes de ROS

Segueix el tutorial 6 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/UnderstandingTopics

En aquest tutorial comencem a jugar amb les següents comandes:

``` turtlesim | rqt_graph | rostopic | rosmsg | rqt_plot```

# Tutorial 7: Entendre serveis i parametres de ROS

Segueix el tutorial 7 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/UnderstandingServicesParams

En aquest tutorial utilitzem rosservice i rosparams per apendre a manipular el serveis i parametres que te ROS. Principalment amb la finestra del ```turtleslim``` creem més tortugues i canviem el color de fons de la finestra

10. Creating a ROS msg and srv
Followed tutorial for Creating a ROS msg and srv.

Created msg/Num.msg a srv/AddTwoInts.srv files as explained in tutorials, compiled and installed. Only issue found was creating the message file outside msg folder by mistake.

11. Writing a Simple Publisher and Subscriber (C++)
Followed tutorial for Writing a Simple Publisher and Subscriber (C++).

Adding a talker and a listener in C++ from the tutorials. I'm going to suppose there are no errors in code execution, because in compilation there was none.

12. Writing a Simple Publisher and Subscriber (Python)
Followed tutorial for Writing a Simple Publisher and Subscriber (Python).

Adding a talker and a listener in Python from the tutorials. No changes in CMakeLists.txt, no wonder why.
