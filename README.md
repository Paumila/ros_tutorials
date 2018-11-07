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

# tutorial 10: Crear un missatge i un servei ROS

Segueix el tutorial 10 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/CreatingMsgAndSrv

Creat carpeta "msg" amb un document i un missatge ```msg/Num.msg```
Creat una carpeta "srv" amb un servei ```srv/AddTwoInts.srv```

# Tutorial 11: Writing a Simple Publisher and Subscriber (C++)

Segueix el tutorial 11 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28c%2B%2B%29

En aquest tutorial afegim un "talker" i un "listener" en C++. 

# Tutorial 12. Writing a Simple Publisher and Subscriber (Python)

Segueix el tutorial 12 des de la següent web:

http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29

En aquest tutorial afegim un "talker" i un "listener" en Python.
