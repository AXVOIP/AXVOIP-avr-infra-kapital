# KAPITAL CUSTOMIZATIONS - AVR

## Customizações aplicadas pela Kapital

### 1. Configuração em Português Brasileiro
- **ANTHROPIC_SYSTEM_PROMPT**: Configurado para atendimento em PT-BR
- **Modelo**: Claude Sonnet 4 (claude-sonnet-4-20250514)
- **Contexto**: Crédito Consignado INSS e Servidor Público

### 2. Configurações de API
- Deepgram STT: nova-2-phonecall model
- Deepgram TTS: Incluído no plano STT
- Claude: Sonnet 4 com 4096 max tokens

### 3. Admin UI
- Username: admin
- Password: Kapital@2026 (alterar em produção)

### 4. Network
- AVR Network: 172.20.0.0/24
- AudioSocket Port: 5001
- Admin UI Port: 3001

## Deployment
Deploy na VPS 187.77.40.98 (Ubuntu 24.04 LTS)

## Documentação
Ver: /opt/kapital/docs/MAPA-SISTEMA-CALLCENTER.md

---
**Mantido por**: AXVOIP
**Data**: 12/02/2026
