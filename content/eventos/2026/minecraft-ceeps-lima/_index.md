+++
date = '2026-02-27T17:42:33+01:00'
draft = true
title = 'Servidor Minecraft CE-EPS LIMA'
[params]
    subtitle = 'La escuela ya cuenta con servidor de minecraft propio.'
+++

{{< figure src="./images/mc_social_logo.png" width="20%" alt="Logotipo simplificado del videojuego Minecraft" >}}

Con motivo de la celebración del día de la EPS 2026 nace el servidor de minecraft oficial de la EPS.

En colaboración con el Consejo de Estudiantes y la Dirección de la Escuela, la **Asociación LIMA** 🍋‍🟩  ofrecerá un servidor vanilla disponible a todos los estudiantes de la EPS durante todas las horas del día.

## Información básica

- Versión del juego: vanilla `1.21.11`, con actualizaciones cuando salgan versiones posteriores.
- Modo híbrido premium / no-premium: los jugadores sin el juego comprado pueden acceder al servidor siempre que no usen un nombre de usuario premium.
  Podéis usar [namemc](https://namemc.com), por ejemplo, para comprobar si el nombre de usuario que queráis usar está registrado a una cuenta de pago.
- [VoiceChat](https://modrinth.com/plugin/simple-voice-chat) para hablar directamente desde el juego.
- Se permite el uso de mods de cliente y packs de texturas siempre que entren dentro de las **siguientes categorías**:
  - mods de optimización.
  - fullbright, `gamma:10.0`, no-fog, etc.
  - overlays de desgaste de armadura, tiempo restante de efectos, etc.
  - previews de shulker boxes.
- Quedan explícitamente prohibidos mods de tipo x-ray, mini-mapa, ESP, etc.
  Preguntar en caso de duda 😄.
- Se aplicarán normas básicas de comportamiento como por ejemplo: no destruir construcciones ajenas sin permiso, atacar a desconocidos, robar, máquinas de lag, etc.
  En cualquier caso nos reservamos el derecho de retirar acceso al servidor si consideramos que vuestro comportamiento está siendo negativo para el servidor o sus jugadores.

## ¿Cómo me conecto?

El servicio está reservado para miembros de la Escuela Politécnica Superior.
Para conectarte debes seguir los siguientes pasos:
1. Conéctate a `mc.ceeps.lima.sh` para registrar tu nombre de usuario.
1. Manda un correo electrónico desde tu **dirección institucional** (@\*.uam.es) a [whitelist.mc.ceeps@lima.sh](mailto:whitelist.mc.ceeps@lima.sh?subject=Whitelist%20MC%20EPS%20LIMA&body=IGN) con los siguientes datos:
    - asunto: `Whitelist MC EPS LIMA`,
    - cuerpo: `<nombre de usuario minecraft>`.
1. Espera un minuto.
1. Ya puedes jugar a través de `mc.ceeps.lima.sh`.

**Nota:** el sistema de whitelist por correo electrónico es automático, por lo que el cuerpo y asunto deben coincidir exactamente con lo especificado para que funcione 🤓.
También se comprueba la dirección del remitente para limitarlo a miembros de la comunidad.
_Usad únicamente el correo institucional_.

{{< notice >}}
Este servicio está actualmente en pruebas.
Estamos trabajando para mejorar las prestaciones de la máquina y los juegos que ofrecemos.
Por el momento el número máximo de jugadores concurrentes estará limitado a **20**.
Además, puede que resetemos el mapa unas semanas una vez obtengamos una máquina más potente.
{{< /notice >}}

## Detalles técnicos

- VPS: AMD EPYC CPU con 4 vCores 3.0GHz y 8GB RAM.
- Servidor fabric con mods de optimización detrás de un proxy velocity.
- Distancia de renderizado y procesado del servidor dinámica en función de la carga.

En caso de cualquier incidencia escribir a [lima.asociacion@uam.es](mailto:lima.asociacion@uam.es)

[← volver al inicio](/)
