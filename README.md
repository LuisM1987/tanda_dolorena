# Tanda Doloreña (TDD)

Sistema de ahorro rotativo vecinal construido con TDD (Flutter). Logica de negocio en Dart puro
(`lib/logica`, `lib/modelos`), interfaz animada en `lib/presentation`.

## Como ponerlo a andar

1. Descomprime el zip y abre la carpeta `tanda_dolorena` en VS Code.
2. En la terminal, dentro de la carpeta, agrega las plataformas:

       flutter create . --platforms=android,web

3. Descarga dependencias y corre las pruebas (deben pasar 11 en verde):

       flutter pub get
       flutter test

4. Ejecuta la app:

       flutter run -d edge        # web
       flutter run                # Android (con emulador o telefono conectado)
