# v52-subgraph-hsk

Subgraph de HSK para consultar anclajes de expedientes Vector52. **Scaffold documental; implementación pendiente.**

## Entidades mínimas

- `CaseAnchor`
- `ManifestVersion`
- `AnchorIssuer`

## Consulta de demo

La demo debe demostrar:

```text
export .v52 → hash del manifest → anchor HSK
→ evento indexado → query del subgraph → hash coincidente
```

El README final debe incluir deployment ID, red, bloque inicial, dirección del contrato, query reproducible y comportamiento ante indexación atrasada.
