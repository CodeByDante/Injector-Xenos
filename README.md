# Injector de DLL para Windows

Un potente inyector de DLL para Windows, basado en la libreria **Blackbone**

![libreria](https://github.com/DarthTon/Blackbone/workflows/Library/badge.svg?branch=master)

---

## Características

- **Soporta procesos y módulos x86 y x64**
- **Función de inyección en modo kernel** (se requiere controlador)
- **Mapa manual de controladores del kernel** (se requiere controlador)
- **Inyección de imágenes administradas puras sin DLL proxy**
- **Inyección en sesiones y escritorios cruzados en Windows 7**
- **Inyección en procesos nativos** (aquellos que solo tienen cargado ntdll)
- **Llamada a una rutina de inicialización personalizada después de la inyección**
- **Desvinculación del módulo después de la inyección**
- **Inyección usando secuestro de hilos**
- **Inyección de imágenes x64 en procesos WOW64**
- **Mapeo manual de imágenes**

### Funciones de Mapa Manual

- **Relocaciones, importación, importación retrasada, importación vinculada**
- **Ocultamiento de la memoria de imagen asignada** (se requiere controlador)
- **TLS estático y callbacks de TLS**
- **Cookie de seguridad**
- **Manifiestos de imagen y SxS**
- **Hacer el módulo visible para GetModuleHandle, GetProcAddress, etc.**
- **Soporte para excepciones en memoria privada bajo DEP**
- **Imágenes C++/CLI son soportadas** (usa 'Agregar referencia de cargador' en este caso)

### Sistemas Operativos Soportados

- **Windows 7 - Windows 10 x64**
