
# 🔐 Relatório de Análise de Redes - Desafio Final Módulo 1 
**Formação:** CyberSec - Módulo 1  
**Versão:** Desafio Final


## 📌 Visão Geral

Este repositório contém um relatório técnico baseado na análise de um ambiente de laboratório simulado com redes segmentadas utilizando Docker. Foram identificados diversos serviços expostos, vulnerabilidades e oportunidades de melhorias de segurança.

---

## 🧭 Objetivo

Analisar as redes criadas no ambiente de laboratório para:

- Identificar IPs e serviços ativos
- Detectar vulnerabilidades
- Avaliar a segmentação e isolamento das redes

---

## 🧪 Metodologia

### Ferramentas utilizadas:
- Nmap
- RustScan
- Netdiscover
- Ping
- Curl
- Arp

### Etapas:
- Descoberta de hosts e portas abertas
- Mapeamento de serviços e vulnerabilidades
- Teste de conectividade 
- Comparação com boas práticas de segurança

---

## ⚠️ Vulnerabilidades Encontradas
                     
- Acesso fraco sem autenticação                  
- Portas exploráveis por malwares                
- Serviço exposto e desatualizado                
- PHP obsoleto e painel acessível                
- Softwares antigos, sem uso, risco elevado      

---

## 🔧 Recomendações

- 🚫 Desligar serviços inseguros (como FTP)
- 🔥 Instalar e configurar firewalls
- 🔐 Aplicar autenticação forte no MySQL e LDAP
- 🚫 Restringir pastas compartilhadas no Samba
- ⬆️ Atualizar versões de software expostas

---

## 🚀 Plano de Ação 80/20

| Ação                                  | Impacto | Facilidade | Prioridade |
|---------------------------------------|---------|------------|------------|
| Desativar FTP                         | Alto    | Alta       | Alta       |
| Isolar servidor legado                | Alto    | Média      | Alta       |
| Configurar firewall                   | Médio   | Alta       | Alta       |
| Restringir SMB                        | Médio   | Média      | Média      |
| Atualizar Samba                       | Alto    | Média      | Alta       |

---

## 🧩 Conclusão

Com pequenas mudanças no ambiente de rede, é possível **reduzir riscos significativamente**.
A análise demonstrou como serviços mal configurados, ausência de firewall e exposição desnecessária podem comprometer a segurança.

Essa experiência foi essencial para desenvolver habilidades práticas em varredura, análise e correção de vulnerabilidades em redes corporativas.

---

## 🗺️ Diagrama da Rede

O diagrama de topologia foi desenvolvido no [draw.io](https://app.diagrams.net)  
<img width="1310" height="1073" alt="Diagrama de redes1 drawio" src="https://github.com/user-attachments/assets/997fa75b-8797-49dd-8ed0-4885bf84c4ee" />

---




> 





