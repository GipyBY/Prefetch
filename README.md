# HookPrefetch

Un **hook de prefetch** simple que bloquea la creación de un archivo prefetch específico.

---

## Cómo usarlo

1. Descarga el código fuente y localiza el archivo llamado `prefetchname`.  
2. Reemplaza `prefetchname` con el nombre exacto del prefetch que deseas bloquear.  
3. Compila el proyecto para generar el archivo DLL.  
4. Inyecta el DLL compilado en el servicio `SysMain` para activar el hook.

---

## ¿Qué es esto?

Este proyecto implementa un hook de prefetch diseñado para evitar la creación de un archivo prefetch específico por nombre, ayudándote a controlar o bloquear operaciones de prefetch no deseadas en tu sistema.

---

## Aviso

Usa esta herramienta con responsabilidad y asegúrate de entender las implicaciones de bloquear archivos prefetch del sistema.
