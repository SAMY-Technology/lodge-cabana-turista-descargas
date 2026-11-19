# Lodge Cabaña Turista · descargas

Repositorio **público** solo para descargar el APK de prueba de la app Lodge Cabaña Turista (Samy Technology).
El código vive en un repositorio privado; aquí no hay código.

Enlace fijo del APK (siempre la última versión que pasó las pruebas automáticas):
https://github.com/SAMY-Technology/lodge-cabana-turista-descargas/releases/download/apk/lodge-cabana-turista.apk

Es una versión de prueba (Fase 1), con datos de demostración.

## Cómo llega el APK aquí
La nube del repo de la app (flujo `Nube`, en GitHub, sin el PC) arma el APK firmado con la clave de subida y lo deja en
Firebase Hosting (`/descargas/`). El flujo `Traer APK` de este repo revisa cada 15 minutos y, si hay una versión nueva
(su `sha256` cambió y coincide al bajarlo), la sube a la versión fija `apk`. No usa llaves de otros repos.
