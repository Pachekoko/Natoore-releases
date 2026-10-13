# Natoore

Instaladores del consultorio homeopático de escritorio. Cada versión está en [Releases](https://github.com/Pachekoko/Natoore-releases/releases).

El código fuente no está en este repositorio. Tampoco hay expedientes ni credenciales de la base del sitio.

## Qué es

Aplicación para el equipo del médico: agenda, expedientes, consulta de remedios y síntomas, y receta para imprimir o enviar por WhatsApp. Muestra fuentes y grados; no prescribe.

Los datos del consultorio se guardan en el equipo. Con internet se sincronizan con [natooree.onrender.com](https://natooree.onrender.com). Después del primer ingreso se puede seguir trabajando sin red.

## Qué descargar

| Archivo | Sistema | Actualizaciones |
|---|---|---|
| `Natoore-<versión>.AppImage` | Linux de 64 bits | Automáticas |
| `natoore_<versión>_amd64.deb` | Debian, Ubuntu y derivadas | Manuales: hay que instalar el paquete nuevo |
| `Natoore-<versión>-setup.exe` | Windows de 64 bits | Automáticas |

En Linux, el AppImage es el que se actualiza solo. El `.deb` no.

## Instalar

Linux, AppImage: descarga el archivo, márcalo como ejecutable y ábrelo.

Linux, paquete Debian:

```bash
sudo apt install ./natoore_<versión>_amd64.deb
```

Windows: ejecuta el `setup.exe`. SmartScreen puede avisar porque el instalador no está firmado; se puede continuar. Queda un acceso directo en el escritorio.

El primer ingreso pide internet y una cuenta aprobada en el sitio. Después la agenda y los expedientes siguen disponibles sin conexión.

## Qué se sincroniza

Con red: perfil, pacientes, citas, consultas terminadas y expedientes compartidos. Los borradores de consulta se quedan en el equipo. El repertorio no viaja de un equipo a otro.

No subas a este repositorio bases de datos ni archivos de pacientes.
