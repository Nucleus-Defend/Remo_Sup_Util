Nucleus Defend
------------------
Este repositorio contiene las herramientas autorizadas por MTMR - Group y Nucleus Defend para realizar conexiones remotas seguras a sistemas de clientes con contrato de soporte activo.
Solo personal autorizado puede utilizar estos recursos.

🛡️ Normas de Seguridad

✅ Todas las conexiones deben usar encriptación E2E (Extremo a Extremo).

✅ Verificar la identidad del cliente antes de iniciar la conexión.

✅ Nunca acceder a sistemas sin consentimiento explícito del cliente.

✅ Registar todas las sesiones con fines de auditoría (ID_Sesión + Timestamp).

✅ Los archivos de credenciales (ej: .env, keys) deben excluirse del repositorio.

🔐 Protocolo de Conexión

Obtener consentimiento del cliente (vía email/teléfono).
Validar identidad con pregunta de seguridad (ej: ID de contrato).
Iniciar conexión con la herramienta correspondiente.
Registrar la sesión en /logs/sessions.csv.
Cerrar conexión y notificar al cliente.

🚨 Solución de Problemas

Error de conexión: Verificar firewall del cliente.
Acceso denegado: Revisar vigencia del contrato en Portal Nucleus.
Herramienta no responde: Usar alternativa de respaldo (ej: TeamViewer si AnyDesk falla).

📞 Soporte

Soporte técnico interno: mmorales@ntmr.local
Urgencias: USA: +1-877-648-0860 / CR: +506-2505-5004
Documentación oficial: Nucleus Defend Knowledge Base

📜 Licencia
Este repositorio es de uso interno de Nucleus Defend LLC.
Queda prohibida su distribución a terceros sin autorización escrita.
