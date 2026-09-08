# Attraction Domain — Domain Map

## Purpose

Mapa vivo del dominio ATRACCIÓN y de los componentes que lo materializan.

```text
                                  COS
                                   │
                           ATTRACTION DOMAIN
                                   │
         ┌─────────────────────────┼─────────────────────────┐
         ↓                         ↓                         ↓
  HERMES MARKETING        ATLAS MARKETING v2       SUPPLIER INGESTION
         │                         │                         │
         └─────────────────────── SYNC ──────────────────────┘
                                   │
                           CONTENIDO & COPY
                                   │
                          PUBLICACIÓN / META
                                   │
                           CAPTURA DE INTENCIÓN
                                   │
                      HANDOFF HACIA CONVERSIÓN
                                   │
                     FEEDBACK DE VENTAS (OUTCOME)
                                   │
                         LEARNING & OPTIMIZACIÓN
```

## Domain Boundary

### In Scope
- Monitoreo de inventario y tarifas promocionales.
- Ingesta estructurada de bloqueos de proveedores.
- Generación de copys para redes sociales y WhatsApp.
- Generación de prompts y artes visuales.
- Campañas Always-On y lanzamientos promocionales.
- Captura de prospectos y telemetría de clics/vistas.
- Paso de contexto enriquecido ("La Pelota") al Dominio de Conversión.
- Aprendizaje derivado del retorno de inversión y efectividad por canal/hotel.

### Out of Scope
- Negociación y cotización directa con clientes (pertenece a Conversión).
- Cobro, emisión de vouchers y facturación (pertenece a Operaciones).
- Autorizaciones de políticas constitucionales (pertenece al Director).

## Navigation Rule: La Pelota de Atracción

```text
OFERTA / HOTEL
+ DESTINO
+ TARIFA_DESDE
+ FECHAS_DISPONIBLES
+ CANAL_PUBLICACION
+ COPY_APROBADO
+ ARTE_VISUAL
+ ENLACE_LANDING / WHATSAPP_TRIGGER
+ LEAD_ID_CAPTURADO
```
