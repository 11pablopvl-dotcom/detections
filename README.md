# detections

Reglas de detección en SPL (Splunk) y KQL (Microsoft Sentinel) escritas y probadas en producción, con mapeo a MITRE ATT&CK, falsos positivos conocidos y guía de respuesta.

Autor: Pablo Piedrabuena · Detection & Response, Tier III · [ghosintel.es](https://ghosintel.es)

## Estructura

```
rules/
  splunk-spl/<tecnica>-<nombre>/   rule.spl · README.md · tests/
  sentinel-kql/<tecnica>-<nombre>/ rule.kql · README.md · tests/
```

Cada regla documenta: objetivo, técnica ATT&CK, fuentes de log requeridas, lógica, umbrales, falsos positivos observados y pasos de triaje.

## Índice

| Regla | Plataforma | ATT&CK | Estado |
| --- | --- | --- | --- |
| _pendiente_ | | | |

## Criterio

Alta fidelidad antes que cobertura: cada regla nace de un caso real, se mide por volumen de falsos positivos y se retira si no aguanta. Es el mismo criterio con el que se redujo un 30 % el ruido en un SOC Tier III.
