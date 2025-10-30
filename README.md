IDIT :: PROYECTO QUIMERA (SOTANO-B)

ADVERTENCIA: NO MODIFICAR NADA SIN AUTORIZACIÓN DEL DR. CUERVO.

Este repositorio es un espejo de la rama de producción legacy-B85. Toda la telemetría está comprometida.

ESTADO ACTUAL

El corvus-node principal no responde. Estamos en un bucle de autenticación infinito en la terminal 4428. La interfaz de Quimera está desconectada y no podemos acceder al core del sistema.

NO INTENTEN REINICIAR EL SERVIDOR.

COMPONENTES DEL SISTEMA

idit-core (Compilador principal)

logger-B85 (Actualmente fallando, logs corruptos)

chimera-interface (Desconectada)

security.env (Módulo de inyección de variables - ¡NO TOCAR!)

INSTRUCCIONES DE DESPLIEGUE (OBSOLETAS)

NO EJECUTAR. SOLO COMO REFERENCIA.

Clonar el repositorio: git clone ...

npm install --legacy-peer-deps (El package-lock.json está corrupto)

docker-compose up -d --build (El corvus-node fallará)

Inyectar security.env manualmente en el contenedor del corvus-node (Ruta desconocida).

Ejecutar run_B85.py (Script de Python obsoleto, no funcionará con la nueva API de Node).

NOTAS URGENTES

[ ] AISLAR LA TERMINAL 4428.

[ ] ¿QUIÉN SUBIÓ EL ARCHIVO DE CONFIGURACIÓN? ¡¡CONTIENE CREDENCIALES DE SOPORTE!!

[ ] Migrar todo de legacy-B85 antes del colapso total. El Dr. no responde.