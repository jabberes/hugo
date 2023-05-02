---
title: Introducción a Jabber/XMPP
categories:
  - "Jabber"
menu:
  jabber:
    weight: 15
---

---

- Con Jabber puedes enviar mensajes a usuarios desconectados, conectar a tu cuenta desde varios sitios al mismo tiempo, conectar a otras redes (como MSN, AIM o Yahoo!), poner tu estado en una web y mucho más...
- Los servidores Jabber de todo el mundo conforman una federación de mensajería instantánea en la que todo el mundo puede hablar entre sí sin restricción alguna.
- Jabber está basado en XMPP, un protocolo extensible, abierto y estándar basado en XML para el intercambio en tiempo real de mensajes y presencia entre dos puntos en Internet.

---

Jabber es un protocolo abierto basado en el estándar XML para el intercambio en tiempo real de mensajes y presencia entre dos puntos en Internet. La principal aplicación de la tecnología Jabber es una extensible plataforma de mensajería y una red de MI (Mensajería Instantánea) que ofrece una funcionalidad similar a la de otros sistemas como AIM, ICQ, MSN Messenger y Yahoo.

Jabber destaca porque es distinto:

- Es **abierto** -- el protocolo de Jabber es gratuito, abierto, público y comprensible. Además, existen múltiples implementaciones de código abierto para Servidores Jabber (consulta la lista de servidores públicos) como numerosos clientes y librerías de desarrollo.

- Es **extensible** -- usando el potencial del lenguaje XML, cualquiera puede extender el protocolo de Jabber para una funcionalidad personalizada. Claro que para mantener la interoperatibilidad, las extensiones comunes son controladas por la Jabber Software Foundation.

- Es **descentralizado** -- cualquiera puede montar su propio servidor de Jabber, además está libre de patentes y no depende de ninguna empresa de modo que se puede usar ahora y siempre con total libertad.

- Es **seguro** -- Cualquier servidor de Jabber puede ser aislado de la red pública Jabber, cualquier implementación del servidor usa SSL para las comunicaciones cliente-servidor y numerosos clientes soportan PGP-GPG para encriptar las comunicaciones de cliente a cliente. Además, está en desarrollo una seguridad más robusta gracias al uso de SASL y contraseñas de sesión.

Jabber puede crear confusión en un principio respecto a otros sistemas de mensajería instantánea porque habitualmente, en otros IM, se identifica el cliente con el protocolo. En el caso de Jabber esto no es así: existe un protocolo y cada uno de los clientes es una implementación.

---

**La red Jabber**

Al nivel más básico, si dos contactos tienen cuentas creadas en el mismo servidor, podrán hablar entre ellos.

Aqui se puede ver a dos usuarios que se conectan a sus cuentas del servidor 'jabberes.org', y hablan entre ellos directamente:

![](/img/jabber-intro-uno.png)

Existe una gran red de servidores Jabber interconectados entre sí, a la vez que independientes los unos de los otros. La mayoría de estos servidores son privados, en el sentido de que son mantenidos por personas o asociaciones particulares, aunque de acceso público, por lo que cualquier usuario puede usar sus servicios sin ninguna restricción.

Así, usuarios de distintos servidores conectados a la red Jabber pueden hablar entre ellos sin ningún problema, ya que cada usuario está conectado a su servidor, y los servidores de estos usuarios se intercambian los mensajes:

![](/img/jabber-intro-dos.png)

Podemos elegir entre muchos servidores, cada uno de ellos suele ofrecer diferentes servicios al usuario, y en nuestras manos está escoger el servidor que más nos guste o convenga. Al fin y al cabo, independientemente del servidor que escojamos para acceder a la red de Jabber, podremos conversar con contactos de otros servidores y añadirlos a nuestra lista de contactos.

En este gráfico se muestra a ocho usuarios Jabber, cada uno conectado al servidor que prefirió, incluso hay uno que está conectado a dos servidores simultáneamente. Todos ellos pueden hablar entre sí, ya que sus servidores están integrados en la red Jabber:

![](/img/jabber-intro-tres.png)

En Jabber la dirección de cada usuario dependerá del servidor en el que tenga la cuenta, siguiendo el esquema siguiente: nombre_de_usuario@nombre_de_servidor.

Por ejemplo, si nos conectamos a Jabber a través del servidor jabberes.org, nuestra cuenta será
`nombre_usuario@jabberes.org`

Colaboraciones: Kuasar y Raulex
