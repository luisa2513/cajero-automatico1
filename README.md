# Cajero Automático

Proyecto integrador: simulación de un cajero automático en Java con programación orientada a objetos.

## Funciones
- Ingreso con tarjeta y PIN (la tarjeta se bloquea con 3 intentos fallidos)
- Consultar saldo
- Retirar dinero (máximo $1.000.000, en múltiplos de $10.000)
- Depositar
- Transferir entre cuentas
- Historial de movimientos

## Clases
Cliente, Tarjeta, Cuenta (abstracta), CuentaAhorros, CuentaCorriente, Transaccion, CajeroAutomatico y Main.

## Cómo ejecutarlo
Requiere JDK 17 o superior.

    cd src
    javac -encoding UTF-8 *.java
    java Main

Tarjeta de prueba: 4000123412341234
PIN: 1234
