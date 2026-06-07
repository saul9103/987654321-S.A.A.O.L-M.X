{
"audit_trail": {
"system": "S.A.A.O.L M.X.",
"folio": "AUDIT-TRAIL-2026-0606-001",
"generated_at": "2026-06-06T00:00:00Z",
"retention_period": "10 years",
"hash_algorithm": "SHA-256",
"events": [
{
"event_id": "AT-0001",
"timestamp": "2026-06-06T08:00:00Z",
"event_type": "DOCUMENT_CREATED",
"asset_id": "DOC-001",
"actor": "S.A.A.O.L M.X.",
"action": "Creación de documento de seguimiento",
"source": "Internal System",
"integrity_status": "Verified",
"hash": "PENDIENTE_SHA256",
"risk_level": "Low"
},
{
"event_id": "AT-0002",
"timestamp": "2026-06-06T08:15:00Z",
"event_type": "CASE_UPDATED",
"asset_id": "UN2892685",
"actor": "Analyst",
"action": "Actualización de estado documental",
"source": "Case Management",
"integrity_status": "Verified",
"hash": "PENDIENTE_SHA256",
"risk_level": "Medium"
},
{
"event_id": "AT-0003",
"timestamp": "2026-06-06T08:30:00Z",
"event_type": "EMAIL_RECEIVED",
"asset_id": "MAIL-001",
"actor": "External Entity",
"action": "Recepción de comunicación",
"source": "Email Gateway",
"integrity_status": "Verified",
"hash": "PENDIENTE_SHA256",
"risk_level": "Low"
},
{
"event_id": "AT-0004",
"timestamp": "2026-06-06T09:00:00Z",
"event_type": "EVIDENCE_ARCHIVED",
"asset_id": "EV-001",
"actor": "Custodian",
"action": "Resguardo de evidencia digital",
"source": "Evidence Repository",
"integrity_status": "Verified",
"hash": "PENDIENTE_SHA256",
"risk_level": "Low"
},
{
"event_id": "AT-0005",
"timestamp": "2026-06-06T09:30:00Z",
"event_type": "AUDIT_REVIEW",
"asset_id": "AUD-001",
"actor": "Audit Officer",
"action": "Revisión de controles y trazabilidad",
"source": "Audit Module",
"integrity_status": "Verified",
"hash": "PENDIENTE_SHA256",
"risk_level": "Medium"
}
],
"chain_of_custody": {
"custodian": "S.A.A.O.L M.X.",
"repository": "Evidence Vault",
"tamper_detection": true,
"audit_log_enabled": true,
"immutable_storage": true
},
"compliance_mapping": {
"ISO27001": [
"A.5",
"A.8",
"A.12"
],
"ISO37301": [
"Compliance Monitoring",
"Corrective Actions"
],
"COSO": [
"Control Activities",
"Monitoring Activities",
"Risk Assessment"
]
}
}
}
