# AS-IS: Supplier Ingestion B2B

**Rol:** Ingesta y normalización de bloqueos de mayoristas (GNIALL, Sun Paradise, Lopesan, etc.) para alimentar la atracción y la venta.

### Estado de la Evidencia:
- Binding para Marketing (`atlas_state.hallazgo_evidence_attempt_binding_05sep`): **RESUELTO**.
- Binding para Supplier Ingestion B2B: **GAP ABIERTO** en investigación forense (`raw_supplier_evidence` $\rightarrow$ `ingestion_attempt`).
- Secuencia Invariante:
  $$\text{Supplier Input} \rightarrow \text{Raw Evidence} \rightarrow \text{Attempt} \rightarrow \text{Parsed} \rightarrow \text{Identity} \rightarrow \text{Norm} \rightarrow \text{Valid} \rightarrow \text{Classification} \rightarrow \text{Structured Supply}$$
