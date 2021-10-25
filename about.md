---
layout: page
title: About Me
description: When building a website it's helpful to see what the focus of your site is. This page is an example of how to show a website's focus.
sitemap:
    priority: 0.7
    lastmod: 2021-08-31
    changefreq: weekly
---
## Acerca de mí y esta página

<span class="image left"><img src="{{ "/images/pic04.jpg" | absolute_url }}" alt="" />

Me llamo Sebastián. Soy estudiante, desarrollador de backend para una empresa, y a veces desarrollador freelance, depende como vaya mi día.

Creé esta página como una mánera de expresar algunas cosas que se me ocurran que puedan gustar a personas con gustos parecidos al mío. En este blog puede que no suba artículos que se parezcan los títulos pero yo creo que son interesantes. La imagen de la izquierda es un ejemplo de como poner imágenes con esta plantilla y se va a quedar ahí.

### ¿Qué sé y tengo experiencia?
- **Python**: Lenguaje de programación que más utilizo, me siento cómodo y me gusta. Es un lenguaje muy flexible con el que he trabajado, haciendo desde páginas web hasta funciones lambda en AWS.
- **Amazon Web Services**: Servicio Cloud que me hicieron aprender y se puede hacer un millón de cosas, algo sencillo como solo tener un servidor Web en EC2 es muy fácil de iniciar y mantener de manera grauita pero la mejor son los servicios más avanzados, como montar tu propio cluster de Kubernetes.
- **Linux**: (Explico con detalle más adelante) *Server Windows* < < < < *Server Linux*
- **Docker**: Sistema que automatiza el despliegue de aplicaciones dentro de contenedores. Tuve que aprender de Docker porque no encontraba la manera de ingresar Ffmpeg en AWS lambda :(, cosa que ya pude :) pero aprendí un montón de sistemas operativos con esto y no me arrepiento para nada, mi último proyecto en Docker actualmente es montar Pi-Hole y Plex en Docker dentro de una Raspberry Pi 4.
- **Git y Github**: Autoexplicativo. Solo tengo que decir que desde que aprendí Git cada vez que inicio un nuevo proyecto sé que debo iniciar con un "*git init*".
- **Tecnologías Web**: He puesto tecnologías web(HTML, CSS y JavaScript) hasta el final debido a que no he trabajado mucho con esto, me considero más de backend pero sí sé un poco y me defiendo.

### Linux

<span class="image right"><img src="{{ "/images/neofetch.png" | absolute_url }}" alt="Ubuntu in Neofetch" />

Esto debe de tener su apartado. Soy fan de muchas distribuciones de Linux, tengo experiencia usando:
- Ubuntu (Actualmente en WSL y lo utilizo en sevidores)
- Q4OS (Actualmente tengo una PC Familiar con este sistema)
- Amazon Linux 2 (Servidores)
- Arch (Manjaro, un tiempo)
- Linux Mint (Un tiempo en una laptop limitada)

A pesar que mi subreddit favorito es [r/unixporn](https://www.reddit.com/r/unixporn/) que es una delicia de ver, no logro encontrar un sabor que haga click conmigo, así que sigo estancado en Windows. He intentado cambiar en muchas ocasiones y me veo siempre volviendo por motivos que no logro solucionar.

Para las personas como yo que les encanta Linux pero por algunos motivos sigue en Windows, existe **WSL**(Windows Subsystem for Linux). Que es una herramienta que permite tener un nucleo de Linux corriendo en una máquina virtual administrada por Windows. Esto es de lo primero que instalo cuando hago un formateo, me perdonarás Powershell(que ha mejorado mucho a comparación del CMD) pero tener una bash en Windows para mí ahora es indispensable.

El único problema que tengo es lo que llega a gastar si no tienes cuidado, por defecto puede consumir hasta la mitad de tu RAM con un máximo de 16GB (que serían 8GB para WSL). Yo tengo 16GB y claro que está bien, pero sí esto lo juntas con Docker, que también necesita de WSL ya puede suponer un problema. Se puede llegar a limitar con el archivo *.wslconfig* en la carpeta de usuario, [más info aquí.](https://docs.microsoft.com/en-us/windows/wsl/wsl-config#configure-settings-with-wslconfig-and-wslconf)


### ¿Qué quisiera aprender?
- **Lenguaje de Programación**: Con Python me siento cómodo pero también quisiera aprender algo más, he estado pensando en *Go* o *Kotlin*.
- **Kubernetes**: Sé lo básico y no lo he agarrado más porque voy bien solo con Docker pero sí debería hacer algún proyecto con esta tecnología.


