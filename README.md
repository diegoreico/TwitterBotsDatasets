# TwitterBotsDatasets

Este repositorio contiene una serie de conjuntos de datos que se han capturado en base  a  unas  series  de  listas de  cuentas  con  usuarios  etiquetados  como  bots  o  no. Teniendo  en  cuenta  estos  conjuntos  de  datos,  que  contienen  diferentes  listas  de  usuarios,  he  procedido  a  registrarme  en  la  API  de  desarrolladores  de  Twitter,  lo  que permite  extraer  datos  de  Twitter  de  forma  controlada.  Una vez  registrado,  he  desarrollado  una  pequeña  aplicación  en Python3 que dado un archivo consistente de tuplas `usuario, clasificación`, la aplicación se conecta a la API de Twitter y extrae:

1. Todos los datos que esta proporciona para los per-files de Twitter de cada uno de los usuarios.
2. Toda  la  informaci on  disponible  de  los  tuits  de  un usuario, para los ́ultimos 100 tuits del mismo. Este par ametro  es  regulable  y  se  pueden  extraer  más  o menos  tuits  de  los  usuarios  a  la  hora  de  realizar la  captura  de  datos,  pero  para  este  trabajo  se  ha seleccionado  el  valor  de  100  para  sobrepasar  los límites de descarga de datos establecido por Twitter para su API

Esta aplicación desarrollada se encuentra disponible en un repositorio de la plataforma https://github.com/diegoreico/TwitterBotsDetector y lo único necesario para usarla son unas credenciales de desarrollador de la API de Twitter

Volviendo a los conjuntos de datos, las listas de usuarios se encuentran proporcionadas por la web "BotRepository" https://botometer.iuni.iu.edu/bot-repository/datasets.html

