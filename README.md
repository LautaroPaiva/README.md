# README.md
Captura de pantalla de la instantanea:


<img width="960" height="739" alt="image" src="https://github.com/user-attachments/assets/49ea9402-6ee6-4f97-896e-833d1383e760" />

Modo de adaptador solo anfitrion:


Use el adaptador de Solo anfitrión ya que la VM queda aislada de tu red local no “aparece” como un dispositivo más en la red logrando disminuir alcance para escaneo/ataques y el acceso suele quedar restringido al host en vez de Internet/tu LAN.


El motivo por el cual no se use el adaptador "Puente" fue porque al abrir mi maquina virtual con esta opcion,te conectaría a la misma red que tu host, entonces sería más alcanzable desde otros equipos de la red logrando una mayor posibilidad de escaneos/ataques y depende unicamente de la seguridad de esa red/host.


Captura de pantalla de la configuracion de red:
<img width="825" height="507" alt="image" src="https://github.com/user-attachments/assets/889d49ab-4051-471c-a6c8-782c8bfe7535" />
