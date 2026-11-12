# TrainCableViewer-Releases

Instaladores y actualizaciones de Train Cable Viewer. El código se mantiene en un repositorio separado.

## Versión estable actual

**Train Cable Viewer 1.0.1** → [releases/tag/product-1.0.1](https://github.com/AFernandezAvelli/TrainCableViewer-Releases/releases/tag/product-1.0.1)

## Esquema de tags

| Tag | Significado |
|-----|-------------|
| `product-X.Y.Z` | Release estable del producto. |
| `product-X.Y.Z-beta.N` | Release beta del producto. |
| `v7.*`, `v6.*`, `v1.0.0` | Históricos. No se usan para nuevas versiones. |
| `v7.10.17` | Puente de transición para instalaciones antiguas RC6/RC7. Debe seguir siendo el destino `latest` del feed antiguo. |
| `update-channels` | Release técnica que contiene los manifiestos firmados `latest.yml` / `beta.yml` para los clientes 1.x. **No borrar ni renombrar.** |

## Notas

- `product-1.0.2-beta.1` fue un portable para pruebas manuales, no una versión planificada.
- No renombrar, borrar ni re-apuntar tags o releases existentes: los clientes instalados dependen de ellos.
