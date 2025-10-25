# SECURITY HANDOFF - HYDRA War-Room Dashboard

## Secretos y Variables de Entorno

### GitHub Actions (si se implementa auto-actualización)
- `GH_TOKEN`: Token de GitHub con permisos `public_repo`
- `REPO_NAME`: Nombre del repositorio (SSIA)
- `BRANCH`: Rama principal (main)

### APIs Externas (futuras integraciones)
- `CRM_API_KEY`: Clave API para sistema CRM
- `MONITORING_API_KEY`: Clave API para métricas de monitoreo
- `SLACK_WEBHOOK`: Webhook para notificaciones Slack

### Configuración de Dominio
- **Dominio configurado**: www.tajamusa.online
- **DNS CNAME**: www → tahamuzza-ship-it.github.io
- **GitHub Pages**: Configurado en Settings → Pages

## Archivos Sensibles
- `.env` - NO incluir en el repositorio
- `config/secrets.json` - NO incluir en el repositorio
- Tokens en scripts - Usar variables de entorno

## Notas de Seguridad
1. Todos los tokens deben tener permisos mínimos necesarios
2. Rotar tokens cada 90 días
3. Usar GitHub Secrets para workflows automáticos
4. No hardcodear credenciales en código fuente

## Contacto
Para acceso a secretos, contactar al administrador del proyecto.

---
**Generado**: 2025-10-25T08:15:00Z  
**Versión**: 1.0
