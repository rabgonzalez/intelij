# Instalación del IDE IntelliJ IDEA
# Rubén Abreu González

- [Prerrequisitos](#prerrequisitos)
- [Instalación](#instalación)
- [Lanzamiento de Intellij](#lanzamiento-de-intellij)

## Prerrequisitos
Recuerda que para la instalación de Intelij debes de tener instalado Java. Los pasos para realizar su instalación y configuración se encuentra en el siguiente enlace.
Para verificarlo recuerda ejecutar el siguiente enlace:
java -version
<details>
<summay>salida</summary>

```code
openjdk version "11.0.20.1" 2023-08-24
OpenJDK Runtime Environment (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04)
OpenJDK 64-Bit Server VM (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04, mixed mode, sharing)
```
</details>

## Instalación
sudo su
<details>
<summay>salida</summary>

```
```
</details>

cd etc/apt/preferences.d/
<details>
<summay>salida</summary>

```code
```
</details>

/etc/apt/preferences.d# rm nosnap.pref
<details>
<summay>salida</summary>

```code
```
</details>

apt install snapd
<details>
<summay>salida</summary>

```code
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
Se instalarán los siguientes paquetes NUEVOS:
  snapd
0 actualizados, 1 nuevos se instalarán, 0 para eliminar y 218 no actualizados.
Se necesita descargar 23,8 MB de archivos.
Se utilizarán 102 MB de espacio de disco adicional después de esta operación.
Des:1 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 snapd amd64 2.58+22.04.1 [23,8 MB]
Descargados 23,8 MB en 1s (19,9 MB/s)
Seleccionando el paquete snapd previamente no seleccionado.
(Leyendo la base de datos ... 527996 ficheros o directorios instalados actualmen
te.)
Preparando para desempaquetar .../snapd_2.58+22.04.1_amd64.deb ...
Desempaquetando snapd (2.58+22.04.1) ...
Configurando snapd (2.58+22.04.1) ...
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.aa-prompt-list
ener.service → /lib/systemd/system/snapd.aa-prompt-listener.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.apparmor.servi
ce → /lib/systemd/system/snapd.apparmor.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.autoimport.ser
vice → /lib/systemd/system/snapd.autoimport.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.core-fixup.ser
vice → /lib/systemd/system/snapd.core-fixup.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.recovery-choos
er-trigger.service → /lib/systemd/system/snapd.recovery-chooser-trigger.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.seeded.service
 → /lib/systemd/system/snapd.seeded.service.
Created symlink /etc/systemd/system/cloud-final.service.wants/snapd.seeded.servi
ce → /lib/systemd/system/snapd.seeded.service.
Unit /lib/systemd/system/snapd.seeded.service is added as a dependency to a non-
existent unit cloud-final.service.
Created symlink /etc/systemd/system/multi-user.target.wants/snapd.service → /lib
/systemd/system/snapd.service.
Created symlink /etc/systemd/system/timers.target.wants/snapd.snap-repair.timer
→ /lib/systemd/system/snapd.snap-repair.timer.
Created symlink /etc/systemd/system/sockets.target.wants/snapd.socket → /lib/sys
temd/system/snapd.socket.
Created symlink /etc/systemd/system/final.target.wants/snapd.system-shutdown.ser
vice → /lib/systemd/system/snapd.system-shutdown.service.
snapd.failure.service is a disabled or a static unit, not starting it.
snapd.mounts-pre.target is a disabled or a static unit, not starting it.
snapd.mounts.target is a disabled or a static unit, not starting it.
snapd.snap-repair.service is a disabled or a static unit, not starting it.
Procesando disparadores para gnome-menus (3.36.0-1ubuntu3) ...
Procesando disparadores para man-db (2.10.2-1) ...
Procesando disparadores para dbus (1.12.20-2ubuntu4.1) ...
Procesando disparadores para mailcap (3.70+nmu1ubuntu1) ...
Procesando disparadores para desktop-file-utils (0.26+mint3+victoria) ...
root@rabgonzalez-VirtualBox:/etc/apt/preferences.d# sudo snap install intellij-idea-community --classic
2023-10-30T17:05:34Z INFO Waiting for automatic snapd restart...
Se ha instalado intellij-idea-community 2023.2.4 por jetbrains✓
```
</details>

## Lanzamiento de IntelliJ
> Nota: Para iniciar IntelliJ, le damos a la tecla de windows y buscamos el nombre de la aplicacion.


