<p align='center'>
  <img width='200' heigth='225' src='https://user-images.githubusercontent.com/62605744/171186764-43f7aae0-81a9-4b6e-b4ce-af963564eafb.png'>
</p>

# flutter_uv
A brief example of a web multiplatform application for Android and IOS in Flutter

## Autores
- David Alberto Guzmán Ardila
- Miguel Angel Fernández Villaquiran

## Aclaraciones
- La instalación de Flutter se hizo para windows.
- Si no se entiende como ejecutar la aplicación con esta guia, pueden ir a este tutorial de YT (creditos a Fernando Herrera): https://www.youtube.com/watch?v=pcchmeVAqwg
- Si se va a ejecutar esta aplicación desde un dispositivo físico, debe estar configurado con opciones de desarrollador y tener habilitadas las opciones para depurar USB e instalar vía USB, además debe permitirse la transferencia de archivos vía USB.
- La plantilla se obtuvo originalmente de este repositorio de github: https://github.com/mitesh77/Best-Flutter-UI-Templates

## Requisitos
### Versiones de aplicaciones
Se instaló para esta aplicación esta versión de Flutter:
![image](https://github.com/Daga2001/flutter_uv/assets/62605744/2b449999-93cd-4104-bf76-dc9cce16f94f)

### Requisitos de software ( Kits de Desarrollo de Software (SDK), IDEs y demás ).
1. Descargar flutter SDK, para ello vamos a la siguiente página: https://docs.flutter.dev/get-started/install y poner el SDK en las variables de entorno de windows
2. Descargar e instalar el bash de Git en: https://git-scm.com/downloads, también se puede usar powershell.
3. Tener instalado VS Code, con los plugins de flutter y dart.
4. Tener instalado Android Studio, se descarga en: https://developer.android.com/studio?hl=es-419
Se instala con las configuraciones recomendadas.
5. En el IDE de Android Studio, tener estos plugins instalados si se desea trabajar desde dicho IDE:
- Dart: el lenguaje donde desarrollamos apps en flutter.
- Flutter: para que soporte el Kit de desarrollo de software de flutter.
6. Tener instalado Android SDK CLI desde Android studio.

### Requisitos de hardware
- Tener aproximadamente 10 GB libres.
- SO: Windows >= 10 (de preferencia WIN 11).
- RAM: 8 gb como mínimo, se recomiendan al menos 12 gb de RAM.

## Ejecución de la aplicación:
1. Verifiquemos si tenemos todo listo para usar flutter
```powershell
flutter doctor
```
3. Si nos hace falta aceptamos las licencias de android con: 
```powershell
flutter doctor --android-licenses
```
y decimos que sí a todos los mensajes que aparezcan.
3. Descargamos todas las dependencias de la aplicación con:
```powershell
flutter pub get
```
4. Si es necesario hacer ajustes, nos guiamos por el comando:
```powershell
dart fix --dry-run
```
Este comando es para realizar un análisis estático del código y mostrar los problemas que se pueden corregir automáticamente sin aplicar realmente las correcciones. La opción **--dry-run** se utiliza para simular la ejecución del comando sin realizar cambios en los archivos. Esto es útil para ver qué cambios propone Dart Fix antes de aplicarlos de manera definitiva.
5. Si es necesario, aplicamos correcciones que sugiere Dart con:
```powershell
dart fix --apply
```
6. Seleccionamos el dispositivo donde ejecutaremos la aplicación, puede ser físico o virtual.
7. Ejecutamos la aplicación desde **lib/main.dart** en vs code con **f5** o **Run -> Start Debugging**
8. Esperamos bastante tiempo, no preocuparse si no vemos que se ejecuta de inmediato, la demora se debe al proceso de compilación de la aplicación. Normalmente tarda entre 10-15 min.

